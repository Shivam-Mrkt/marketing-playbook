# Lead scoring

## Objective

Prioritise useful follow-up without pretending a score proves purchase readiness. Keep durable account fit separate from recent behaviour, then let sales validate the opportunity.

## Illustrative scoring model: B2B SaaS

This provisional model is for fictional RelayDesk. It is a starting hypothesis, not a validated benchmark. Fit totals at most 50; behaviour totals at most 50.

| Category | Criterion | Points | Rule |
| --- | --- | ---: | --- |
| Company fit | B2B SaaS industry and business model | 15 | Verified; otherwise 0 pending research |
| Company fit | 50–500 employees | 10 | Current evidence |
| Company fit | Supported CRM in use | 10 | Verified, not guessed |
| Job seniority / role | Revenue operations owner or relevant manager+ | 15 | 8 for relevant practitioner; choose one |
| Website behaviour | Pricing or product evaluation page visit | 10 | Once within 30 days, where appropriately observable |
| Intent signal | Explicit demo or evaluation request | 25 | Once within 30 days |
| Engagement | Attended relevant session | 10 | Once within 30 days |
| Engagement | Downloaded relevant guide | 5 | Once within 30 days |

Do not award repeated page views or downloads unlimited points. Email opens score zero because they are a weak, noisy signal. Behaviour points expire after 30 days unless a new qualifying action occurs. Recheck fit at least every 90 days or when a material change is reported.

## Thresholds and stages

| Status | Rule | Action |
| --- | --- | --- |
| Cold / nurture | Total below 60, or fit below 30; no explicit buying request | Relevant education if eligible; research unknown fit |
| Marketing Qualified | Total at least 60 **and** fit at least 30; no disqualifier | Marketing review and sales handoff under the agreed SLA |
| High Intent | Explicit demo/evaluation request and fit at least 30 | Priority flag; prompt human follow-up even below 60 total |
| Sales Qualified | Sales confirms fit, relevant problem and agreed evaluation next step | Set SQL stage; score alone cannot do this |

An explicit request with unknown fit enters urgent review rather than being silently buried in nurture. A confirmed unsupported requirement or poor-fit business exits sales routing with a reason. Opt-out is a contact restriction, not a negative score to be overridden by engagement.

## Step-by-step process

1. Agree criteria with sales and customer success.
2. Define each data source, refresh rule and missing-data treatment.
3. Test sample records manually, including disqualifiers and unknowns.
4. Activate the model with score components visible to owners.
5. Review accepted leads, rejected MQLs and low-score opportunities by cohort.
6. Adjust weights only after examining errors; version the model and effective date.

## Worked example

**Illustrative example: B2B SaaS.** A NorthstarOps revenue operations manager has all four fit attributes: 50 points. A relevant guide download and evaluation-page visit add 15, giving 65 total and MQL status. A subsequent demo request adds 25, giving 90 and a High Intent flag. Sales confirms a routing problem and an evaluation meeting before changing the lifecycle stage to SQL.

## Metrics and checklist

Track MQL acceptance, opportunity rate by score band, false positives, low-score opportunities and time to response. Use mature cohorts so recent leads are not judged prematurely.

- [ ] Fit and behaviour totals are visible separately.
- [ ] Repeat actions are capped and behaviour expires.
- [ ] Buying requests with unknown fit reach a person.
- [ ] SQL requires human qualification.
- [ ] Suppression overrides contact eligibility.

**Experiment idea:** run a revised threshold in shadow mode and compare which leads it would route before changing live treatment.

Related: [Lead qualification](../crm/lead-qualification.md) · [Lead-scoring template](../templates/lead-scoring-template.md) · [Lead routing](../automation/lead-routing.md) · [CRM](README.md).
