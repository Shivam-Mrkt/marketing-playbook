# CRM workflows

## Objective

Make record creation, ownership and stage changes dependable enough that leads do not disappear between systems or teams.

## Core workflow

Form submission → Validate and deduplicate → Preserve source → Enrich → Assess fit → Score → Assign owner → Follow up → Record outcome

## Operating rules

| Event | Rule | Exception |
| --- | --- | --- |
| New lead | Create or update the correct person/account | Ambiguous duplicate goes to review |
| Existing account | Preserve account ownership | Escalate inactive or unavailable owner |
| New meaningful behaviour | Recalculate score with caps | Do not repeat an action because a sync retries |
| Explicit evaluation request | Flag for prompt review | Unknown fit stays visible in priority queue |
| Sales disposition | Record stage, reason and next action | Missing reason returns to owner |
| Opt-out | Update channel eligibility and suppress promotion | Do not erase required history blindly |

## Step-by-step process

1. Document fields, owners and the system that is authoritative for each field.
2. Define deduplication carefully; company matches do not mean two people are one lead.
3. Preserve first-touch source and store later touches separately.
4. Set response expectations and an escalation queue.
5. Test normal, duplicate, missing-data and failed-sync scenarios.
6. Review queue age, integration errors and unowned records daily during launch.

## Illustrative example: B2B SaaS

A fictional NorthstarOps contact submits a second RelayDesk form. The CRM adds the new request to the existing person, keeps the original acquisition source and alerts the current account owner. A failed enrichment step does not delay a direct demo request; it creates a research task alongside the handoff.

## Metrics and checklist

Track unowned leads, duplicate rate, failed syncs, response SLA compliance and disposition completeness. Measure actual first human response separately from automated acknowledgement.

- [ ] Source and ownership cannot be overwritten casually.
- [ ] Retries do not create duplicate actions.
- [ ] Failed records enter a visible queue.
- [ ] Stage changes retain timestamps.
- [ ] Suppression propagates to connected campaigns.

**Experiment idea:** pilot a simpler disposition menu with one team and compare completion and usefulness before rolling it out.

Related: [Lead routing](../automation/lead-routing.md) · [Lead enrichment](../automation/lead-enrichment.md) · [CRM](README.md).
