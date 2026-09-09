# Lead segmentation

## Objective

Group leads only when the grouping changes a message, offer, owner or next action. A segment nobody uses is extra maintenance.

## Framework

| Dimension | Example | Operational use |
| --- | --- | --- |
| Fit | Supported versus unknown CRM | Qualification or research |
| Need | Territory routing versus fair distribution | Different content and demo focus |
| Lifecycle | New lead, SQL, customer | Appropriate next step |
| Intent | Explicit evaluation request | Response priority |
| Engagement recency | Recent meaningful action versus inactive | Cadence and review |
| Contact eligibility | Eligible, opted out, restricted | Suppress or permit the relevant channel |

## Step-by-step process

1. Define the action before creating the segment.
2. Choose reliable fields and write exact inclusion rules.
3. Decide whether membership can overlap. For exclusive campaigns, set priority rules.
4. Add exclusions for customers, open opportunities and contact restrictions as appropriate.
5. Test membership with sample records and missing fields.
6. Review segment size, performance and stale data at a regular cadence.

## Illustrative example: B2B SaaS

RelayDesk creates a “territory evaluation” segment: known routing need, fit at least 30 and no active opportunity. Members receive a territory comparison if eligible. A demo request removes the lead from the automated education journey and alerts the owner. The person can remain tagged with the need for reporting while leaving the campaign audience.

## Metrics and mistakes

Compare qualified progression and opt-out rate by segment, with population size visible. Do not conclude a segment is better from a handful of outcomes or use engagement to overwrite durable fit information.

## Practical checklist

- [ ] Segment has a named treatment and owner.
- [ ] Membership rules are reproducible.
- [ ] Overlap and priority rules are explicit.
- [ ] Missing data has a route.
- [ ] Exclusions are checked at send time.

**Experiment idea:** compare need-based content with a general newsletter among otherwise similar eligible leads.

Related: [Lifecycle marketing](lifecycle-marketing.md) · [Email automation](../automation/email-automation.md) · [CRM](README.md).
