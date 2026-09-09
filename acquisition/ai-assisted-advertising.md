# AI-assisted advertising

## Why it matters

AI can make research, drafting and review faster. It cannot establish whether a buyer insight is true or whether a campaign caused revenue. Use it to produce options and questions, then verify the inputs and decide what deserves a test.

## Framework

| Task | Useful input | Output | Human decision |
| --- | --- | --- | --- |
| Audience research | Anonymised interviews and objections | Themes with supporting excerpts | Is the sample representative? |
| Competitor analysis | Dated public pages and ads | Offer and positioning comparison | Are the claims and sources accurate? |
| Creative ideation | Buyer problem, product evidence, constraints | Distinct angles and hooks | Which are relevant and supportable? |
| Copy variations | Approved angle and facts | Headlines and descriptions | Are meaning and tone intact? |
| Search term analysis | Aggregated terms, spend and qualified outcomes | Proposed intent labels | Would a negative block useful demand? |
| Landing page analysis | Page content and audience brief | Message gaps and objections | What should actually change? |
| Reporting | Reconciled campaign and CRM totals | Observations and possible explanations | Which conclusions does the evidence support? |

## Step-by-step process

1. State the decision and provide the minimum necessary evidence. Remove personal and confidential information from material sent to unapproved tools.
2. Ask the model to distinguish observation, interpretation and unknowns.
3. Request materially different options, not synonyms of one headline.
4. Check every product claim, quotation and calculation against its source.
5. Select an experiment with a measurable outcome and spend limit.
6. Save the approved version, source dates and reviewer's decision.

## Prompts worth using

**Audience and competitor research**

> Using only the supplied interview notes and public competitor extracts, identify three recurring buyer problems. Cite the input passage for each. Separate customer evidence from competitor claims. Mark missing evidence as unknown. Do not infer competitor performance from ad visibility.

**Creative angles and copy**

> For a lead-routing product aimed at revenue operations managers, propose four distinct ad angles using the approved facts below. For each, give a buyer tension, a hook, a short ad and a matching landing-page promise. Do not invent customer names, savings, integrations or testimonials. Flag any claim that needs proof.

**Search term analysis**

> Classify these aggregated search terms as solution intent, research, irrelevant or uncertain. Explain each proposed exclusion. Consider qualified leads and conversion delay, not only CPL. Return proposed negatives for human review; do not treat low volume as proof of poor intent.

**Campaign insights and experiment generation**

> Review this reconciled report. Separate facts from hypotheses. Suggest three possible explanations for the quality decline and the evidence needed to distinguish them. Propose one test with a primary metric, guardrail and stopping rule. Do not claim causation from a before-and-after comparison.

## Illustrative example: B2B SaaS

RelayDesk supplies 20 anonymised interview excerpts. AI suggests that slow assignment is the main problem. A reviewer discovers most excerpts came from one large customer, so the team treats the idea as a segment hypothesis. It tests “clear ownership” against “faster assignment” without publishing an unsupported speed claim.

## Metrics and checklist

Measure approved-output rate, factual corrections, time to a usable brief and subsequent experiment performance. More generated copy is not itself a marketing outcome.

- [ ] Inputs are approved for the tool.
- [ ] Sources support every factual claim.
- [ ] Arithmetic checked independently.
- [ ] Human reviewer owns publishing and budget decisions.
- [ ] Uncertainty is retained in the report.

Related: [AI workflows](../automation/ai-workflows.md) · [Experiment framework](../experiments/experiment-framework.md) · [Competitor template](../templates/competitor-analysis.md) · [Acquisition](README.md).
