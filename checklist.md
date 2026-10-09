# AI Search Visibility Checklist

Use this worksheet for one site, one audience, and a short list of important questions. Record evidence and dates; do not treat an answer engine’s response as a stable ranking report.

## 1. Define the test

- [ ] State the audience and market being evaluated: ____________________
- [ ] Select 5–10 real questions a prospective customer might ask. Include informational and service-selection intent; do not use only branded queries.
- [ ] Select the pages that should help answer those questions. Map each question to one best page; note gaps rather than forcing an unrelated page to fit.
- [ ] Record language, country/region, date, device/context, answer product, and exact prompt/query wording.
- [ ] Save the baseline answers or notes and the URLs shown. Do not record personal account data or private conversation content.

**Question log**

| Date | Market/language | Product or search surface | Exact question | Expected useful page | What appeared / cited URL | Notes |
|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |

## 2. Check whether important pages can be found and indexed

Test a representative page, not just the homepage.

- [ ] The URL loads for a logged-out visitor and returns a successful page response rather than an error, login wall, or empty shell.
- [ ] The main content is available in the rendered page and is not dependent on a blocked or failed interaction to appear.
- [ ] The page is not unintentionally blocked by `robots.txt`, an access restriction, or a `noindex` directive.
- [ ] The page has one intended, consistent URL. Redirect variants resolve appropriately; internal links point to the preferred URL.
- [ ] The canonical points to the intended version where a canonical is needed; it is not accidentally pointing to another page or domain.
- [ ] Important, indexable pages are linked from relevant pages and included in the site’s sitemap where appropriate. The sitemap contains canonical URLs intended for search, not redirects or private pages.
- [ ] Use Search Console URL Inspection if you have verified property access. Compare the live test with Google’s indexed information; a live test does not itself prove indexing.
- [ ] Check Search Console indexing reports for repeated patterns, not just a one-off URL. Record the exact status and example URLs.

**Do not confuse crawling and indexing:** allowing a crawler to fetch a page is not a promise that the page will be indexed or shown.

## 3. Make the page understandable and worth referencing

- [ ] The title and main heading accurately state what the page is about and are distinct from those on other important pages.
- [ ] The opening explains the subject, intended reader, and useful answer without requiring a user to infer it from slogans.
- [ ] The page directly answers the mapped question with concrete steps, definitions, examples, decision criteria, or evidence appropriate to the topic.
- [ ] Claims are traceable to a source or clearly framed as the author’s analysis. Remove invented statistics, unsubstantiated superlatives, and guarantees.
- [ ] Distinguish fact, interpretation, and uncertainty. Give dates and scope for evidence that can change.
- [ ] The page provides original utility beyond a restatement of top search results. Include a usable worksheet, process, example, comparison, or primary evidence when appropriate.
- [ ] A reader can identify the author or responsible organization and a way to check important claims. Do not invent credentials, reviewers, or subject-matter experience.
- [ ] Important images have useful text alternatives where needed; tables and headings make the information navigable.
- [ ] Related pages are linked with descriptive anchor text. Avoid repeated exact-match anchors inserted only for ranking purposes.
- [ ] Content is current enough for its subject. Explain what was checked and when; update or remove stale instructions.

## 4. Check entities and business facts

For a business or organization page:

- [ ] Use one approved public name consistently across the site and profiles.
- [ ] Keep descriptions of services, products, locations, availability, contact channels, and operating hours aligned with current authoritative records.
- [ ] Mark unknown information as unknown. Do not fill gaps with assumed address, company size, client list, reviews, legal identity, awards, or certifications.
- [ ] Link to relevant first-party service pages and useful supporting material, not a generic destination by default.
- [ ] If structured data is used, verify that it describes visible, accurate page content and follows the rules for the specific Google Search feature. Do not add fake ratings, reviews, locations, or credentials.
- [ ] Do not expect structured data to guarantee a rich result or an AI citation.

## 5. Review usefulness, accessibility, and trust

- [ ] A visitor can reach the answer and the next relevant step without a forced signup or distracting interstitial.
- [ ] The page is usable on a phone and with keyboard navigation; headings, link text, and form labels make sense out of visual context.
- [ ] The page is secure, readable, and reasonably responsive on common devices. Use field data or a repeatable test where available; do not infer user experience from one synthetic score alone.
- [ ] Important recommendations cite primary sources when possible and show their scope and date.
- [ ] The page does not impersonate a person, organization, or customer; it does not manufacture social proof or imply independent endorsement.
- [ ] Any commercial relationship, product promotion, or sponsored content is disclosed as appropriate.

## 6. Measure without overclaiming

### Search performance

- [ ] In Search Console, review queries and pages for the same date range and search type. Record clicks, impressions, CTR, and average position, and note whether the view is grouped by property, page, or query.
- [ ] Compare like with like: same property, market, device, search type, and reasonably comparable time periods. Search Console data can be delayed and its query data is not a complete record of every search.
- [ ] Treat average position as an aggregate diagnostic, not a stable rank for every person or query. Prefer trends in impressions and clicks over a single position value.
- [ ] Annotate substantial page changes and external events so that later comparisons have context.

### Answer-engine sample

- [ ] Repeat the same small set of questions in the same products and market context where possible.
- [ ] Record whether the brand/site appeared, which URL was cited, whether the citation supported the answer, and any factual errors.
- [ ] Distinguish “mentioned” from “linked/cited.” Save the actual visible result and date; do not assume a citation is a followed backlink.
- [ ] Repeat more than once before drawing conclusions. Answers can change between runs even when the site does not.
- [ ] Report the sample size and test method. Do not convert a few prompts into a market-wide visibility percentage.
- [ ] If the test produces an incorrect answer, investigate what reliable first-party or independent sources say; do not respond by adding unsupported claims to the site.

## 7. Prioritize next actions

Use this order as a triage guide, not a ranking formula:

1. **Access blockers:** broken URLs, accidental `noindex`, crawler disallow, wrong canonical, or missing internal discovery paths.
2. **Accuracy blockers:** incorrect business facts, outdated instructions, unsupported claims, or conflicting first-party pages.
3. **Answer gaps:** important questions with no page that directly and usefully addresses them.
4. **Clarity improvements:** vague titles/headings, buried answers, weak internal links, or unclear authorship/source context.
5. **Measurement gaps:** no baseline, inconsistent question set, or no record of which page was intended to answer a question.

For each action, write the observed evidence, affected URL, smallest proposed change, owner, and a future recheck date. Make one coherent change at a time when practical, and avoid attributing a later change in answers to one edit without stronger evidence.

## Reusable action log

| Priority | Observation / evidence | URL | Smallest next action | Owner | Date changed | Recheck date | Result / caveat |
|---|---|---|---|---|---|---|---|
|  |  |  |  |  |  |  |  |

## Further help

If you want Exendia to review your goals and map possible next steps, [request a free Growth Plan](https://exendia.com/go/). The current page says the intake is human-reviewed and delivered by email; no specific visibility result is promised.

---

Original checklist text © 2026 Exendia, licensed under [CC BY 4.0](LICENSE). Attribution: “AI Search Visibility Checklist” by Exendia, with a link to this repository and the license; indicate if you made changes. Google and other third-party names are used for reference and are not covered by Exendia’s license.
