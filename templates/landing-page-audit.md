# Landing-page audit template

Use one row per finding and add evidence, priority, owner and acceptance criteria. “Looks dated” is not a useful finding unless it connects to an observed problem.

## Illustrative example: B2B SaaS

Fictional RelayDesk territory-routing demo page. Every observation is a teaching scenario, not a live audit.

| Area | Finding | Action / acceptance criterion | Priority and owner |
| --- | --- | --- | --- |
| Headline | Generic growth promise misses routing intent | Name territory-based lead assignment | High; content marketer |
| Value proposition | Intended customer is unclear | State the relevant team and workflow | High; product marketer |
| Proof | Generic illustration shows no workflow | Add a labelled sample rule; no invented customer outcome | Medium; product marketer |
| CTA | “Submit” does not explain next step | Describe the demo request and response expectation | Medium; content marketer |
| Trust | Support route is hard to find | Make real business and support details accessible | Medium; site owner |
| Objections | Implementation process is absent | Explain verified setup steps and limits | Medium; product specialist |
| Form | One mobile error prevents completion | Fix and verify successful submission | Critical; site owner |
| Mobile | Keyboard obscures an error message | Confirm visible errors on representative devices | High; site owner |
| Speed | Large visual delays useful content in the scenario | Reduce unnecessary asset weight and recheck experience | Medium; site owner |
| Tracking | Refresh repeats the conversion event | Count successful submission once and verify CRM total | Critical; analytics owner |

## Decision record

Fix form and tracking defects before running an optimisation test. Then compare the revised message against the existing message with qualified leads per eligible visitor as the primary metric. Keep functional repairs common to both variants.

## Completion checklist

- [ ] Evidence attached in the live working copy.
- [ ] Each issue has an owner and verification step.
- [ ] Repairs separated from uncertain improvements.
- [ ] Mobile journey reaches the CRM successfully.

Related: [Audit playbook](../conversion/landing-page-audit.md) · [Conversion rate](../conversion/conversion-rate.md) · [Templates](README.md).
