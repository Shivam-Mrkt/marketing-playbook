# Lead enrichment

## Objective

Add the minimum reliable context needed to qualify, segment or route a lead. More fields do not automatically produce a better decision.

## Framework

| Field | Decision it supports | Validation |
| --- | --- | --- |
| Company and domain | Account association | Check ambiguous or shared domains |
| Employee range | ICP fit | Source, date and range rather than false precision |
| Industry / model | Segment relevance | Inspect unclear classifications |
| Geography | Territory and service coverage | Distinguish person location from company headquarters |
| Technology | Product compatibility | Confirm important requirements before sales claims |
| Role | Relevant follow-up | Verify current responsibility where possible |

## Workflow

Form → Match existing record → Enrich missing fields → Store source/confidence → Check fit → Route or review

## Step-by-step process

1. Define which missing fields actually prevent a decision.
2. Use approved sources and retain provenance and refresh dates.
3. Preserve verified first-party information when sources conflict.
4. Send ambiguous company matches to review rather than forcing a match.
5. Let urgent requests proceed with a visible research task if enrichment fails.
6. Audit a sample for accuracy and remove fields that never affect action.

## Illustrative example: B2B SaaS

A fictional RelayDesk demo request includes a NorthstarOps work address. Enrichment suggests 180 employees but does not reliably identify the CRM. The record receives the supported size range and “CRM unknown”. The owner asks about the system during qualification; the workflow does not award compatibility points on a guess.

## Metrics and checklist

Track coverage of decision-critical fields, sampled accuracy, wrong account matches and time added before routing. A high fill rate can conceal bad data.

- [ ] Each field has a purpose and source.
- [ ] Verified data wins over uncertain estimates.
- [ ] Unknowns do not become invented facts.
- [ ] Direct buying requests are not held indefinitely.

**Experiment idea:** enrich only routing-critical fields immediately and defer the rest; compare response time and qualification completeness.

Related: [ICP framework](../abm/icp-framework.md) · [CRM workflows](../crm/crm-workflows.md) · [Automation](README.md).
