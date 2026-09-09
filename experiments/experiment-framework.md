# Experiment framework

## Objective

Reduce uncertainty around a specific marketing decision with the strongest feasible comparison. Not every change deserves an experiment; broken forms and incorrect claims should be fixed directly.

## Framework

| Stage | What to document |
| --- | --- |
| Problem | Observed constraint, audience and baseline evidence |
| Hypothesis | Why one change should affect a valuable outcome |
| Change | Treatment and what remains comparable |
| Metric | One primary outcome, diagnostics and guardrails |
| Test | Assignment, sample plan, duration and stop rules |
| Result | Actual counts, rates, data quality and uncertainty |
| Learning | What the evidence supports and leaves unresolved |
| Next action | Roll out, repeat, revise, stop or collect more evidence |

## Step-by-step process

1. Prioritise a decision using likely business value, evidence gap and effort. Avoid false precision in scoring.
2. State the smallest effect that would change the business decision.
3. Estimate sample needs from baseline rate, desired detectable effect and the chosen statistical approach. A calendar duration alone is not a sample plan.
4. Randomise where possible. Use account-level assignment for ABM/outbound to avoid exposing one company to both treatments; use stable visitor assignment for page tests.
5. Predefine the exposure window and allow time for qualification or sales outcomes. If traffic cannot support the sample, simplify the question or call it a directional pilot.
6. Check allocation, tracking, duplicates and major external changes. Unequal delivery and missing outcomes can invalidate a comparison.
7. Stop early for broken tracking, harmful customer experience or a pre-agreed loss limit. Do not repeatedly peek and end a fixed-horizon test when a preferred variant leads.
8. Report counts and rates with uncertainty. Use an appropriate interval or test for the design before making a statistical claim. No significance claim is implied by the small teaching examples here.

## Illustrative example: B2B SaaS

**Problem:** a generic page may not answer territory-routing searches. **Hypothesis:** a use-case page will improve qualified leads per visitor. **Change:** page message and workflow example. **Metric:** qualified leads per eligible visitor; form errors and qualified volume are guardrails. **Test:** stable split with the same traffic source and qualification window. **Result:** the pilot shows a promising difference but too few qualified outcomes. **Learning:** the message deserves more evaluation, not an immediate scale decision. **Next action:** plan a properly sized continuation as a new declared test.

## Common mistakes and checklist

Changing offer, audience and follow-up together prevents a clear explanation. Extending a test only because the result is disappointing also changes the decision process after seeing the data.

- [ ] Hypothesis has a plausible mechanism.
- [ ] Sample feasibility assessed before launch.
- [ ] Metric definitions and assignment are stable.
- [ ] Quality and experience guardrails included.
- [ ] Inconclusive is an acceptable outcome.

Related: [Experiment template](../templates/experiment-template.md) · [Conversion rate](../conversion/conversion-rate.md) · [Experiments](README.md).
