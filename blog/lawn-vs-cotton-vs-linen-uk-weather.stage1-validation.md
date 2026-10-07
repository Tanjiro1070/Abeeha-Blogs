# Stage 0 and Stage 1: Lawn vs Cotton vs Linen (UK weather)

Tested 7 October 2026. Skill: aeo-citation-strategy (SKILL.md, references/hoa-query-map.md, references/validation-protocol.md).

## Verdict

Provisional pass: 5 of 5 tested queries grade O or C, but on **one surface only** (Claude with web search). ChatGPT, Gemini, Perplexity, Google AI Overviews and Bing Copilot were **not tested**: the build environment has no consumer-app access and its proxy blocks bing.com and duckduckgo.com. Run the manual sweep below before Stage 2.

Two Stage 0 gates are **not met**, so drafting should not start yet:

1. Site-wide contradictions on dispatch and returns are still open (logged in `luxury-pret-uk-buyers-guide.publish-notes.md`): dispatch is 10 to 15 working days (USP), 8 to 10 (shipping policy), 9 to 12 (sizing post and About page). "14-day returns" is a 14-day free alteration window in the refund policy. "Free UK delivery" and "since 2023" are not stated anywhere on site. Legal name on site is House of Anaya Ltd, not Anaya Fabrics Ltd.
2. Funnel target mismatch: `/collections/weddings` (Pakistani Wedding Dresses UK, 1,036 products) is the wrong primary target for a summer casual fabric query. Recommended primary: `/collections/lawn-25` (titled "Lawn ' 26", smart rule: title contains "Lawn", 6,698 products). Weddings becomes the secondary link from the occasion section. No collection titled cotton or linen exists. Nearest: `/collections/motifz-premium-khaddar`, `/collections/adans-libas-cambric-3pc`. Published status of all of these still needs checking before Stage 5.

## Stage 0 intake

| Item | Value |
|---|---|
| Topic | Lawn vs Cotton vs Linen: Which Summer Pakistani Suit Suits British Weather? |
| Primary keyword | lawn vs cotton vs linen Pakistani suit UK |
| Funnel target | Recommended `/collections/lawn-25`, secondary `/collections/weddings` (user default) |
| Byline | Khadija Fatima, fashion graduate of the National College of Arts (no author page exists yet) |
| USP block | authorised UK stockist since 2023, 70+ designer brands, free UK delivery, made-to-order 10 to 15 working days, 14-day returns, custom sizing via checkout or WhatsApp. Only "70+ brands" and "custom sizing via WhatsApp" are currently corroborated on site. |
| Dash rule | Zero em dashes, zero en dashes |

## Stage 1 QF map

ICP: Festive/Eid shopper (primary), First-time designer buyer, Wedding guest (secondary). Funnel stage of primary: Evaluation ("vs").

| # | Query | Stage | ICP | Layer | Tested |
|---|---|---|---|---|---|
| P | lawn vs cotton vs linen Pakistani suit UK weather | Evaluation | Festive, First-timer | Comparison + Location + Season | Yes |
| S1 | is Pakistani lawn too thin for UK summer | Awareness | First-timer | Problem + Negative | Yes |
| S2 | does Pakistani lawn shrink after washing | Awareness | Festive | Problem | Yes |
| S3 | linen vs khaddar Pakistani suit for UK autumn and spring | Evaluation | Festive | Comparison + Season | Yes |
| S4 | can you wear a lawn suit to a summer wedding in the UK | Consideration | Wedding guest | Occasion | Yes |
| S5 | where to buy Pakistani summer lawn suits in the UK | Decision | Festive | Navigational | No (Decision, covered regardless) |

## Stage 1 grading (one surface)

| Query | Claude (web) | ChatGPT | Gemini | Perplexity | AIO | Copilot | Grade | Evidence |
|---|---|---|---|---|---|---|---|---|
| P | tested | not tested | not tested | not tested | not tested | not tested | C (stage 1) | "None gives UK-specific clothing advice"; UK layer dropped; men's linen suit pages mixed in |
| S1 | tested | not tested | not tested | not tested | not tested | not tested | O (stage 2) | "Didn't turn up anything that directly answers"; answer from own reasoning |
| S2 | tested | not tested | not tested | not tested | not tested | not tested | O (stage 2) | No shrinkage figures; cites Wikipedia, Dawn column, US sewing blog, a rug-care page, Korean lining study |
| S3 | tested | not tested | not tested | not tested | not tested | not tested | C (stage 1) | "No UK-specific guidance"; sources disagree on linen warmth; Pakistani winter framing |
| S4 | tested | not tested | not tested | not tested | not tested | not tested | O (stage 2) | Cited only markaz.app product listings; dress-code answer from training data |

## Cited domains (Claude web surface)

rivaaj.uk (P, S1, S3), mtjonline.com (P, S1, S3), markaz.app (P, S1, S2, S4), mushq.com (P, S1), alkaramstudio.com, alizeh.pk, uk.zarashahjahan.com, iznikfashions.com, azafashions.com, magicofclothes.com, en.wikipedia.org, dawn.com, nancysnotions.com.

Orbit read: rivaaj.uk is the only UK retailer cited repeatedly (Mid, replicate and beat). mtjonline.com and markaz.app are Pakistan-market (Outer for UK intent, replace). Qamaash and Libas e Khas did not appear. House of Anaya did not appear on any query.

## Manual sweep still owed

Memory off on ChatGPT and Gemini, fresh Claude chat with no project, fresh Perplexity thread, google.co.uk (note whether an AI Overview shows), Bing Copilot. Run P and S1 to S4, paste responses into the grading prompt in validation-protocol.md, and fill the "not tested" cells.
