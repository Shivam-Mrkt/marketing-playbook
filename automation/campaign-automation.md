# Campaign automation

## Objective

Make recurring campaign operations consistent without letting rules spend money or suppress campaigns on misleading signals.

## Framework

| Task | Safe operating pattern | Human decision |
| --- | --- | --- |
| Launch readiness | Checklist and missing-item alerts | Confirm offer, claims and measurement |
| Budget pacing | Compare spend with planned pace | Approve reallocation after checking demand and quality |
| Tracking monitoring | Alert on missing or unusual events | Determine whether tracking or real behaviour changed |
| Lead delivery | Surface missing records and overdue owners | Resolve ownership or integration issue |
| Reporting | Refresh a consistent dataset and draft observations | Interpret causes and next actions |

## Step-by-step process

1. Document the task and the evidence needed to decide it manually.
2. Automate collection and alerts before budget-changing actions.
3. Define minimum volume, data freshness and conversion-delay checks.
4. Add spend limits, a named owner and a pause mechanism.
5. Test in notification-only mode before allowing bounded actions.
6. Log every change with its reason and monitor unexpected behaviour.

## Illustrative example: B2B SaaS

RelayDesk's fictional $12,000 monthly media plan has a pacing alert when cumulative spend differs materially from its planned curve. The alert shows spend, qualified leads and data freshness. A delayed CRM sync triggers a measurement investigation; it does not automatically pause the campaign because qualified-lead counts temporarily appear to be zero.

## Metrics and mistakes

Track time saved, false alerts, unreviewed exceptions and unauthorised spend deviations. A rule that pauses ads after one expensive day can interrupt useful learning; a report generated quickly can still contain wrong joins.

## Practical checklist

- [ ] Rule has a clear owner and business purpose.
- [ ] Data freshness and minimum evidence are checked.
- [ ] Financial actions have explicit limits.
- [ ] Changes are logged and reversible where practical.
- [ ] Notification-only trial completed.

**Experiment idea:** pilot automated pacing alerts with one campaign group and compare detection time and false alarms with the previous review process.

Related: [Campaign analysis](../analytics/campaign-analysis.md) · [AI workflows](ai-workflows.md) · [Automation](README.md).
