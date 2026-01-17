# Analysis: Design for failure: Episode 87, Tetradian on Architectures

## Executive Summary
The video emphasizes designing enterprise architectures for inevitable failures rather than assuming a perfect "happy path," especially in IT-dependent operations. It stresses modeling business continuity, disaster recovery, service fungibility, and symmetrical treatment of IT and manual processes to ensure resilience.[3][1]

## Key Takeaways
- Enterprise architecture must account for all failure sources, including "unknown unknowns" like floods or lightning strikes (e.g., Hurricane Sandy submerging IT).[1]
- Prioritize risks by balancing probability against impact severity, distinguishing low-urgency fixes from mission-critical systems needing near-instant recovery.[1]
- Ensure **fungibility of services** by modeling manual processes symmetrically with IT as interchangeable applications for seamless substitution during outages.[1][2]
- Design for business continuity by planning overrides, recovery mechanisms, and symmetrical architecture layers to rebuild after failures.[1]
- Avoid IT-centrism and arbitrary constraints that fragment architecture, ensuring subsets connect to the whole enterprise for true resilience.[1]

## Actionable Insights / Tutorials
- **Identify failure sources**: List known risks (e.g., IT downtime, natural disasters) and acknowledge unknown unknowns; assess impacts and prioritize based on probability vs. severity trade-offs.[1]
- **Model service fungibility**: Treat manual processes (e.g., cash books in Starbucks during credit machine failure) as symmetrical to IT applications; design mechanisms to capture data offline and reconcile later.[1]
- **Plan recovery and continuity**: Build overrides for manual-IT transitions, ensure seamless substitution, and connect architecture across Zachman rows/columns (What, How, Where, When, Who, Why) without arbitrary constraints.[1][2]
- **Avoid common pitfalls**: Start from context needs, not hardwired assumptions; use adaptive frameworks like TOGAF done right to maintain whole-enterprise scope.[1][2]

## Quotes
- "one of our core concerns is how our architecture is going to support design for failure the fact that things are going to fail"[3]
- "a lot of enterprise architecture is done at present is that it seems to design only for a happy path where everything is going to work"[3]
- "we need to model it as if it's an application not as if it's something completely different at a completely different layer of the architecture they have to be considered to be symmetrical"[3]
- "in our architecture we need to design for failure rather than simply assume that it won't happen"[3]