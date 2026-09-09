# Lead-scoring template

Use to agree criteria, data sources, caps and routing actions. This completed model mirrors the [lead-scoring playbook](../crm/lead-scoring.md); any working changes should be versioned in both the rules and reporting definitions.

## Illustrative example: B2B SaaS

Provisional RelayDesk model, version 1.0. Fit maximum 50; behaviour maximum 50. The weights are unvalidated planning choices.

| Component | Criteria | Points | Source / cap |
| --- | --- | ---: | --- |
| Company fit | B2B SaaS model | 15 | Verified company evidence; once |
| Company size | 50–500 employees | 10 | Current company evidence; once |
| Technology fit | Supported CRM in use | 10 | Verified first-party or reviewed evidence; once |
| Job seniority / role | Relevant operations owner or manager+ | 15 | Relevant practitioner gets 8 instead; choose one |
| Website behaviour | Evaluation or pricing-page visit | 10 | Appropriate first-party observation; once in 30 days |
| Intent signal | Explicit demo/evaluation request | 25 | Submitted request; once in 30 days |
| Engagement | Relevant session attended | 10 | Attendance record; once in 30 days |
| Engagement | Relevant guide downloaded | 5 | Fulfilled request; once in 30 days |

## Thresholds and actions

| Classification | Rule | Treatment |
| --- | --- | --- |
| Cold / nurture | Total under 60 or fit under 30, without explicit buying request | Eligible education or missing-fit research |
| MQL | Total at least 60 and fit at least 30, no disqualifier | Review and handoff |
| High Intent | Explicit buying request with fit at least 30 | Priority flag; do not wait for 60 total |
| SQL | Sales confirms fit, problem and agreed evaluation next step | Human-set lifecycle stage |
| Unknown-fit buying request | Explicit request, fit not established | Urgent human review |

Behaviour expires after 30 days unless renewed by a new qualifying action. Recheck fit every 90 days or on material change. Unknown criteria earn no points until verified; unknown does not mean confirmed poor fit. Disqualifiers prevent sales routing. Contact restrictions override promotional eligibility regardless of score.

## Worked check

**Illustrative example:** NorthstarOps contact with 50 fit points plus guide (5) and evaluation-page visit (10) totals 65: MQL. A demo request adds 25 to reach 90 and flags High Intent. SQL still requires sales confirmation.

## Validation checklist

- [ ] All criteria have an owner and source.
- [ ] Repeat events cannot inflate scores.
- [ ] Missing data and explicit requests have routes.
- [ ] Acceptance and low-score opportunities are reviewed monthly.

Related: [Lead qualification](../crm/lead-qualification.md) · [Lead routing](../automation/lead-routing.md) · [Templates](README.md).
