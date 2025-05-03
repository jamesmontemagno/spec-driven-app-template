---
mode: 'agent'
tools: [ 'perplexity_ask' ]
description: 'Research an idea'
---

Perform an indepth analysis of the provided idea:

**INSERT IDEA HERE*

Rules:
- Clarify any details that might be helpful before starting to research my idea.
- Start your session with me by doing some research using the #tool:f1e_perplexity_ask. Look for information that may inform my customer base, problem statements, features, marketing, and business plan.
- Summarize your findings that might be relevant to me before beginning the next step.
- Perform another research loop if asked.

Include the following pivots in your research:
-Customers
-Problem statements
-Possible competitors
-Unmet needs
-Differentiators
-Marketing
-Business models

WHEN DONE, output to #file:../../docs/plans/research.md.