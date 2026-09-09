# Marketing automation

Automation should remove repetitive coordination while preserving context and accountability. First make the process work manually; then automate clear rules and expose exceptions.

## Playbooks

| Workflow | Guide |
| --- | --- |
| Add useful company context | [Lead enrichment](lead-enrichment.md) |
| Give each lead an accountable owner | [Lead routing](lead-routing.md) |
| Send appropriate lifecycle messages | [Email automation](email-automation.md) |
| Handle expected, opted-in conversations | [WhatsApp automation](whatsapp-automation.md) |
| Coordinate launch, pacing and reporting | [Campaign automation](campaign-automation.md) |
| Use AI for bounded research and drafting | [AI workflows](ai-workflows.md) |

## End-to-end example

**Illustrative example: B2B SaaS.** RelayDesk uses this conceptual flow:

Lead submits form → Validate and deduplicate → Enrich company → Identify ICP fit → Score lead → Update CRM → Notify owner → Prepare relevant follow-up → Track engagement and disposition

An explicit demo request moves to an owner even if enrichment fails. An opt-out blocks promotional sends. A retry updates the existing record rather than creating a second lead.

## Before activation

- [ ] Trigger, conditions, action and exit are written down.
- [ ] One person owns the workflow and exception queue.
- [ ] Missing data and failures have defined paths.
- [ ] Test records cover replies, opt-outs, duplicates and ownership conflicts.
- [ ] There is a simple way to pause the workflow.

Judge workflows by response time, error rate and useful progression, not the number of automated steps. [Back to the playbook](../README.md).
