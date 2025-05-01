# UX-Interview Lab — Product Vision (v0.2)

## Core value
Run thousands of AI-simulated interviews on any digital product and deliver a statistically-backed PDF + live chat for deep-dive questions.

## Plans
Starter €49/mo → 10 000 interviews, 1 000 chat turns  
Growth €149/mo → 50 000 interviews, 5 000 chat turns
Scale €399/mo → 150 000 interviews, 10 000 Chat turns 
## Pipeline
1. Crawl URL ⇒ screenshot + DOM text  
2. Bulk persona interviews (configurable)  
3. Cluster + sentiment + cost estimate  
4. Summarise (GPT-4o)  
5. PDF report  
6. Chat endpoint over report JSON

### Token budget guard-rail
Keep **< $0.0006 per interview** average.

### GDPR
– User must confirm ownership / testing rights  
– Raw crawl & chat logs auto-delete after 30 days
