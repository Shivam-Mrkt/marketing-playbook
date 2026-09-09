# Lead routing

## Objective

Get a relevant request to the person who can act, with context and a response expectation. Assignment alone is not a completed handoff.

## Rule priority

| Priority | Condition | Action |
| --- | --- | --- |
| 1 | Existing customer or active opportunity | Current account or opportunity owner |
| 2 | Named strategic account | Named account owner |
| 3 | Territory or product-specific requirement | Eligible specialist or regional queue |
| 4 | General qualified enquiry | Capacity-aware round robin |
| 5 | Missing or conflicting data | Monitored exception queue |

Check contact eligibility before follow-up. Suppression does not justify losing an inbound service request; route it for appropriate handling.

## Workflow

New request → Existing ownership check → Fit/intent review → Apply priority rules → Notify owner → Confirm action → Escalate if overdue

## Step-by-step process

1. Agree rule precedence with sales so overlaps have a clear winner.
2. Define working hours, owner availability and fallback coverage.
3. Set a realistic response SLA. For the illustrative pilot, use one business hour for explicit buying requests and one business day for reviewed MQLs.
4. Include source, requested offer, fit evidence and relevant notes in the notification.
5. Escalate missed responses to a named backup, avoiding reassignment loops.
6. Test duplicates, absent owners, conflicting territories and unknown fit.

## Illustrative example: B2B SaaS

NorthstarOps submits a fictional RelayDesk demo request from Europe, but a US-based account owner already manages the company. Existing ownership takes precedence. If that owner is unavailable, the backup receives the request and context; it does not silently disappear into a regional queue.

## Metrics and checklist

Measure time to assignment, time to first human response, reassignment rate and overdue queue size. An automated receipt is not a sales response.

- [ ] Rule precedence is documented.
- [ ] Every route has a fallback owner.
- [ ] SLA uses business-hour definitions.
- [ ] Alerts include enough context to act.
- [ ] Escalation has been tested.

**Experiment idea:** compare capacity-aware distribution with simple round robin in a small team, guarding against unequal lead quality.

Related: [Lead scoring](../crm/lead-scoring.md) · [CRM workflows](../crm/crm-workflows.md) · [Automation](README.md).
