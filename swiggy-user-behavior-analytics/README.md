# Swiggy User Behavior & Web Analytics Dashboard

*Key finding: Direct traffic converts best (46.1%), organic traffic drives the most volume, and the "Contact Us" page quietly outperforms the homepage on conversion — a signal that intent-driven visits matter more than raw traffic type.*

## Problem Statement
Swiggy's marketing team was seeing high traffic but lower-than-expected conversion rates, and needed a way to understand *why* — which traffic sources, devices, pages, and campaigns were actually driving transactions, versus just driving visits. The task was to design a Tableau dashboard and story that turns raw web analytics into a clear, decision-ready view for a marketing team.

## Dataset
Website traffic data covering session-level details: traffic source, visitor type (new/returning), device/browser/OS, page views, session duration, bounce, and conversion outcome.

## Approach
- Started by selecting four core KPIs — Total Sessions, Conversion Rate, Bounce Rate, and Avg. Pages per Session — chosen because together they give a full picture of both *reach* (sessions) and *quality* (conversion, bounce, engagement), rather than just tracking traffic volume in isolation.
- Broke these KPIs down by traffic source, device/OS, geography, and landing page to find where the real differences in performance were hiding.
- Built this as both a standalone dashboard and a Tableau Story, structured to walk a reader from problem → observations → recommendations, one slide at a time, rather than dropping every chart on one page at once.

## Key Insights
- Organic traffic drives the most sessions (15,007) with solid conversion (45.5%), while Direct traffic converts best overall (46.1%) — suggesting returning/brand-aware users convert more reliably than newly acquired ones.
- The Spring Sale campaign generated the strongest engagement across states, standing out clearly against other campaigns.
- The Contact Us page drives the highest conversion among landing pages (46.2%) — ahead of the Homepage — suggesting users arriving with a specific intent convert better than general browsers.
- Checkout has the lowest conversion rate of any landing page (43.4%), flagging a possible drop-off point worth investigating further.

## Key Decisions
- I used **maps instead of bar charts** for the campaign-comparison section, since geography was a meaningful dimension here — a map shows reach, regional concentration, and conversion strength in one visual, which a bar chart would've flattened into a single number per campaign.
- I used a **consistent red-to-green color scale for conversion rate** across every chart on the dashboard — red for underperforming, green for strong — so a viewer could scan the whole dashboard at a glance and immediately spot where attention was needed, without reading every number individually.
- I built this as a **Tableau Story rather than a single dashboard**, sequencing it as problem → key observations → recommendations, so the marketing team could follow a narrative instead of having to interpret every chart unprompted.

*(Note: this was my first Tableau project — I've since built on these fundamentals in a second project with more advanced techniques.)*
