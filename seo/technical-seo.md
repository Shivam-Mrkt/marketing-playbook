# Technical SEO for marketers

## Objective

Make important pages discoverable, accessible and usable. A marketer should be able to describe the business impact and acceptance criteria of a technical issue without prescribing the engineering solution.

## Audit framework

| Check | Marketing question | Useful evidence |
| --- | --- | --- |
| Discovery | Can search engines find the page? | Internal links and sitemap inclusion |
| Access | Can the page and its main content be retrieved? | Response status, crawler access, rendered page |
| Indexing | Is the preferred page eligible to appear? | Indexing report, noindex and canonical review |
| Duplication | Are several URLs competing for the same purpose? | URL variants and canonical destinations |
| Experience | Can someone read and act on mobile? | Real-device checks, field performance data |
| Changes | Did a migration break existing journeys? | Redirects, missing pages and traffic changes |

Google explains crawl access, rendered content and indexability in its [developer SEO guide](https://developers.google.com/search/docs/fundamentals/get-started-developers). A sitemap supports discovery; it does not guarantee indexing or rankings.

## Step-by-step process

1. List commercial and high-value educational pages first.
2. Check indexing and inspect a sample of affected URLs in Search Console.
3. Reproduce the problem on the actual page, including mobile and the form journey.
4. Prioritise by affected demand, severity and scale rather than a tool's warning count.
5. Write a clear issue: URL, observed behaviour, business effect, expected behaviour and owner.
6. After the fix, verify the page and monitor subsequent crawling and performance. Recrawling and indexing are not immediate.

## Illustrative example: B2B SaaS

RelayDesk's fictional routing page is accidentally marked noindex after a redesign. The ticket requests removal on that intended public page, confirms crawler access, and checks the preferred canonical. Marketing verifies the live state and requests reinspection; it does not promise a recovery date.

## Practical checklist

- [ ] Important pages return the intended status and content.
- [ ] Index directives and canonical choices match the publishing plan.
- [ ] Links and redirects reach the intended destination.
- [ ] Mobile CTA and form work.
- [ ] Fixes have owners and acceptance checks.

**Experiment idea:** measure a page-speed improvement against conversion behaviour, holding traffic comparable. An indexing repair is essential maintenance, not a randomised growth experiment.

Related: [Landing-page SEO](landing-page-seo.md) · [Landing-page audit](../conversion/landing-page-audit.md) · [SEO](README.md).
