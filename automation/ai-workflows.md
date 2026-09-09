# AI workflows

## Objective

Use AI for bounded tasks with inspectable inputs and accountable review. A useful workflow produces a better decision or usable draft, not simply more text.

## Framework

Approved input → AI draft or classification → Evidence check → Human decision → Controlled action → Outcome review

| Workflow | AI contribution | Reviewer checks |
| --- | --- | --- |
| Account brief | Summarise supplied public evidence | Source dates, identity and unsupported inferences |
| Lead notes | Organise approved, minimised notes | No invented qualification or altered meaning |
| Content brief | Propose audience questions and outline | First-party contribution and factual grounding |
| Campaign review | Surface anomalies and hypotheses | Arithmetic, cohort alignment and data completeness |
| Follow-up draft | Adapt approved material to known context | Relevance, privacy, claims and contact eligibility |

## Step-by-step process

1. Choose a task with clear inputs and review criteria.
2. Remove unnecessary personal information and use only approved tools for business data.
3. Specify what the model may infer and what must stay unknown.
4. Require source references for factual output and reasons for classifications.
5. Compare drafts with a small set of manually reviewed examples, including difficult cases.
6. Keep publishing, lead rejection and material budget changes with an accountable human unless a separately approved bounded process exists.
7. Record corrections and revise the workflow when recurring errors appear.

## Illustrative example: B2B SaaS

For RelayDesk, AI receives an anonymised campaign table and drafts: “Qualified share fell while total leads rose.” It proposes traffic mix, form changes and sales-disposition delay as hypotheses. The marketer checks the CRM and finds a backlog. The report records incomplete qualification instead of declaring a targeting failure.

## Reusable prompt

> Use only the supplied evidence. Return: observed facts, possible explanations, missing information and one recommended next check. Cite the input row or passage behind each fact. Do not invent outcomes or turn correlation into causation. Flag records that need human review.

## Metrics and checklist

Measure accepted drafts, factual error rate, review time and decision usefulness. Count review time when estimating time saved.

- [ ] Input is appropriate for the tool.
- [ ] Unknowns remain explicit.
- [ ] Reviewer can trace factual claims.
- [ ] Output cannot silently change live spend or send messages.
- [ ] Corrections feed back into the process.

**Experiment idea:** compare AI-assisted and manual campaign summaries on accuracy and total review time using the same evidence.

Related: [AI-assisted advertising](../acquisition/ai-assisted-advertising.md) · [Campaign report](../templates/campaign-report.md) · [Automation](README.md).
