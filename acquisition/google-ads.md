# Google Ads

## Why it matters

Search can capture a buyer's stated need. That does not make every query commercially useful. I start with the searches a suitable customer would make, then follow those clicks through qualification and revenue.

## Objective

Generate sales-ready demand within a cost limit the business can support. Name the conversion event explicitly: a demo request, an accepted lead and a customer are different outcomes.

## Campaign framework

| Campaign | Role | What must be ready | Main risk |
| --- | --- | --- | --- |
| Search | Capture existing solution intent | Intent groups, relevant pages, reliable conversions | Paying for research with little buying intent |
| Performance Max | Explore conversion opportunities across Google's inventory | Quality feedback, assets, suitable URLs and exclusions | Optimising toward easy but poor-quality leads |
| Demand Gen | Introduce and demonstrate the offer through visual creative | Strong creative, clear audience hypothesis, longer evaluation window | Expecting cold audiences to convert like Search |

Performance Max combines inventory in one campaign; audience signals guide its learning rather than operating as a strict account list. Review URL expansion and brand controls before launch. Demand Gen is a distinct campaign type, not another name for Search. See Google's [Performance Max overview](https://support.google.com/google-ads/answer/10724817) and [Demand Gen guide](https://support.google.com/google-ads/answer/13695777).

## Step-by-step process

1. **Define the economics.** Agree on the qualified-lead definition, expected close rate and allowable customer acquisition cost. Work backwards to a provisional qualified-lead cost ceiling.
2. **Group intent.** Separate brand, category and specific use cases where budget control or reporting needs differ. Keep each ad group coherent enough to share an ad and landing page.
3. **Choose keywords.** Start with explicit solution phrases. Exact match includes the same meaning or intent; it is not literal-only. Phrase match reaches searches containing the keyword's meaning. Broad match reaches related searches and needs disciplined conversion signals and Smart Bidding. [Google's match-type guidance](https://support.google.com/google-ads/answer/7478529).
4. **Build negatives.** Review jobs, training, support, consumer use cases and unrelated meanings. Do not exclude “free” automatically if a trial is part of the offer. Negative matching behaves differently from positive matching; inspect variants before applying broad exclusions.
5. **Write responsive search ads.** Combine the problem, product category, supported proof and next step. Each asset should work in different combinations. Avoid unsupported “best” claims and invented savings.
6. **Match the page.** Repeat the relevant promise, show the workflow, explain who it suits and state what happens after the form. Send routing searches to a routing page, not a generic homepage.
7. **Verify tracking.** Count a successful form submission once, not every button click. Carry campaign information into the CRM. Keep low-value interactions secondary; return qualified-lead and customer outcomes where permitted and supported. Test duplicate handling and conversion lag.
8. **Set bidding deliberately.** Choose a goal that is both commercially meaningful and reported reliably. A tCPA is a bidding target for average cost per selected action, not a price guarantee. Set it from observed, mature data and economics; an unrealistic target can restrict delivery. [Google bidding guidance](https://support.google.com/google-ads/faq/10286469?hl=en).
9. **Review search terms.** Label visible terms as qualified intent, research, irrelevant or uncertain. Combine spend and CRM outcomes before adding negatives or expanding a theme. The report is not a complete record of every query.
10. **Optimise in order.** Fix broken tracking, wrong traffic and page mismatches before tuning bids. Log each meaningful change and allow the conversion delay before judging it.

## Illustrative example: B2B SaaS

RelayDesk is fictional. These are planning assumptions for a 30-day pilot, not achieved results.

| Decision | Plan |
| --- | --- |
| Objective | 40 qualified demo leads from 100 demo requests |
| Audience | Revenue operations managers at 50–500 employee B2B SaaS companies in the US |
| Offer | A demo using a sample inbound routing workflow |
| Structure | Brand Search; non-brand Search with routing and assignment ad groups |
| Keywords | “lead routing software”, “automated lead assignment”; start with exact and phrase |
| Ad angle | “Route inbound leads by territory. See assignment rules in a demo.” |
| Page | Product workflow, CRM compatibility, example rules, demo expectations |
| Media budget | $12,000 ceiling: $1,000 brand, $9,000 non-brand, $2,000 controlled Search test |
| Other campaigns | Performance Max and Demand Gen deferred until quality feedback and creative are ready |
| Planning KPIs | $120 blended CPL; 40% qualified rate; $300 per qualified lead |

At an assumed 20% qualified-lead-to-customer rate, 40 qualified leads imply eight customers and $1,500 media-only CAC after the sales cycle. This is a scenario to validate. Full CAC also includes relevant people, creative and tools. Brand and non-brand economics must be reported separately.

**Optimisation decisions:** remove a job-seeking query immediately; do not pause a relevant query after two unconverted clicks. If demo volume rises but qualified share falls, investigate query mix and conversion goals before adding budget. If non-brand demand is profitable and budget-limited, release the test allowance only after reviewing mature cohorts. A later Performance Max or Demand Gen pilot gets its own budget and question.

## Metrics

- **CPL:** ad spend ÷ unique leads.
- **CPA:** ad spend ÷ the explicitly named action; always label that action.
- **Qualified-lead cost:** ad spend ÷ qualified leads from the same cohort.
- **ROAS:** attributed revenue ÷ ad spend. Do not substitute open pipeline for revenue.
- **tCPA:** bidding input; compare the achieved CPA and quality with the target.

## Common mistakes

Combining brand and non-brand hides where demand originates. Treating downloads as demos trains the campaign toward the wrong event. Changing bidding, page and targeting together removes the ability to explain the outcome.

## Practical checklist

- [ ] Primary conversion tested through to the CRM.
- [ ] Search terms and negatives reviewed in context.
- [ ] Ad claims can be substantiated.
- [ ] Brand contribution separated.
- [ ] Sales feedback includes rejection reasons.
- [ ] Budget, test question and evaluation window documented.

## Experiment ideas

Test a use-case page against the general product page using a controlled split. Separately test broader matching only after conversion quality is reliable. Judge both on qualified-lead cost with volume as a guardrail.

Related: [Campaign analysis](../analytics/campaign-analysis.md) · [Lead quality](../conversion/lead-quality.md) · [Paid experiments](../experiments/paid-acquisition/README.md) · [Acquisition](README.md).
