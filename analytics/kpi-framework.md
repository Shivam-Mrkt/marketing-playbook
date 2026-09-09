# KPI framework

## Objective

Give each campaign one primary outcome, a few diagnostic measures and guardrails. A dashboard should make trade-offs visible rather than reward whichever number improved.

## Metric hierarchy

| Level | Metrics | Business interpretation |
| --- | --- | --- |
| Delivery | Impressions, reach, frequency | Was the intended audience exposed? |
| Response | Clicks, CTR, CPC | Did the message earn a visit at a workable cost? |
| Acquisition | Leads, CPL | Did visitors take the defined next step? |
| Quality | Qualified leads, qualified rate, qualified-lead cost | Were the enquiries suitable? |
| Pipeline | Opportunities, stage progression, cycle time | Are real evaluations advancing? |
| Commercial | New customers, CAC, revenue, contribution ROI | Is growth economically worthwhile? |

## Formula reference

- CTR = clicks ÷ impressions × 100.
- CPC = ad spend ÷ clicks.
- CPL = ad spend ÷ unique leads.
- Qualified rate = qualified leads ÷ defined unique lead cohort × 100.
- Opportunity rate = opportunities ÷ qualified leads × 100, with the denominator stated.
- Full CAC = defined sales and marketing acquisition cost ÷ new customers.
- ROAS = attributed revenue ÷ ad spend.

When a denominator is zero, report “not calculable”, not zero efficiency. Reach is distinct people or accounts as defined by the platform; do not sum cross-platform reach as if it were deduplicated.

## Illustrative example: B2B SaaS

For RelayDesk's fictional Search pilot, the primary early outcome is cost per qualified lead. Lead volume and qualified share are guardrails; CTR and CPC diagnose delivery. Customer CAC becomes assessable after the acquisition cohort has progressed through sales. No click target replaces the quality goal.

## Step-by-step process

1. State the commercial outcome and current bottleneck.
2. Select the nearest reliable metric that reflects it.
3. Define source, owner, denominator, currency and update cadence.
4. Add guardrails for quality, volume and customer experience.
5. Review whether the metric still fits the campaign's maturity.

## Practical checklist

- [ ] One primary metric guides the decision.
- [ ] Definitions and ownership are documented.
- [ ] Guardrails expose undesirable trade-offs.
- [ ] Revenue metrics use mature, reconciled data.

**Experiment idea:** revise the weekly review around qualified outcomes and track whether budget decisions change for defensible reasons.

Related: [ROI analysis](roi-analysis.md) · [Campaign report](../templates/campaign-report.md) · [Analytics](README.md).
