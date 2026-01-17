# Analysis: A question of timescale: Episode 102, Tetradian on Architectures

## Executive Summary
The video critiques fixed timescale assumptions in enterprise architecture, like those in TOGAF suited for 2-year cycles, emphasizing instead the need to address vast, interwoven timescales from microseconds to hundreds of thousands of years across industries. It highlights fractality in strategy, tactics, and operations, where boundaries are chosen rather than fixed, urging architects to adapt to domain-specific realities.

## Key Takeaways
- Enterprise architecture must accommodate diverse timescales, from sub-microsecond IT challenges (e.g., speed of light in telecoms and computing) to ultra-long ones like 100+ years in health data, 2,000 years in civil engineering (e.g., London sewers), and 250,000 years for nuclear waste labeling.
- Traditional frameworks like TOGAF assume short cycles (e.g., 2 years), ignoring real-world extremes such as "forever chemicals" or epidemiology spanning lifetimes.
- Timescales exhibit **fractality**: strategy-tactics-operations patterns repeat across scales, with one entity's strategy potentially being another's operations; boundaries (e.g., service edges) are human choices, not fixed.
- Fixed anchors include the enterprise vision (unchanging) and the "now-to-past" transition (irreversible), but other demarcations must be chosen wisely.

## Actionable Insights / Tutorials
- When architecting, map domain-specific timescales first: assess shortest (e.g., device lifecycles, nanosecond delays via Grace Hopper's wire demo) and longest (e.g., hazardous goods labeling) to avoid non-compliance traps like unextractable Fitbit health data.
- Apply **SCAN** framing for fractality: position strategy "above the plan" (big-picture fit), tactics in "before action" (planning), operations in "during action"; scale this pattern recursively across hierarchies.
- Choose boundaries deliberately in services, strategies, or operations—test for interweaving (e.g., your operations as upstream strategy) and revisit non-compliant designs iteratively until viable.

## Quotes
- "There's only one time scale that exists but... we have a huge range of timescales all interweaving with each other."
- "Strategy is kind of above the plan stage... tactics tends to sit [in plan phase]... operations is in the during phase but notice that this can have multiple... this pattern will stay the same across multiple time scales."
- "The boundaries are very much ones that we choose... it's important to choose wisely."