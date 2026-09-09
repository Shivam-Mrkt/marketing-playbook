# Attribution

## Why it matters

Attribution assigns credit to observed interactions. It helps organise reporting, but the assigned credit does not establish what would have happened without the marketing activity.

## Framework

| Approach | Useful question | Limitation |
| --- | --- | --- |
| First touch | Where did the observed relationship begin? | Misses earlier unobserved exposure |
| Last touch | What recorded interaction preceded conversion? | Can overcredit demand capture |
| Multi-touch | How was credit distributed across recorded interactions? | Depends on tracking coverage and model rules |
| Self-reported discovery | What does the buyer remember? | Recall is incomplete and subjective |
| Incrementality test | What changed because treatment was present? | Needs a credible comparison and sufficient evidence |

## Step-by-step process

1. Choose a primary reporting model for a named decision.
2. Define conversion, lookback window, identity matching and source hierarchy.
3. Preserve original acquisition source and later touch history.
4. Reconcile platform-attributed outcomes with CRM opportunities and finance revenue.
5. Show self-reported discovery separately from tracked sources.
6. Use controlled holdouts where feasible to investigate incremental impact.

## Illustrative example: B2B SaaS

A fictional RelayDesk buyer hears about the company in a peer discussion, reads a guide, clicks a branded search ad and books a demo. Last-touch reporting credits Search; self-report names the peer discussion. Neither record is necessarily wrong. They describe different parts of the journey.

## Pipeline rules

For a sample operating convention, **sourced pipeline** means the campaign initiated the recorded qualifying relationship before opportunity creation. **Influenced pipeline** means an eligible, meaningful campaign interaction occurred within the declared window around the buying journey. Specify the actual window and qualifying interaction in each report.

Count each opportunity once within a total. Do not add sourced and influenced figures if they overlap. Pipeline is open potential value, not realised revenue. Attribution models differ across platforms, so summing their claimed revenue can double-count the same customer.

## Practical checklist

- [ ] Model and window are visible.
- [ ] Unobserved activity is acknowledged.
- [ ] Opportunity and revenue totals are deduplicated.
- [ ] Credit is not described as proven causation.

**Experiment idea:** use an account-level holdout for an ABM campaign where practical; compare opportunity progression with balanced baseline fit and enough time for the buying cycle.

Related: [ABM campaign](../abm/abm-campaign.md) · [ROI analysis](roi-analysis.md) · [Analytics](README.md).
