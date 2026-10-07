# Publish notes: What Is Luxury Pret? A UK Buyer's Guide to Pakistani Ready-to-Wear

Status: DRAFT, not publish-ready. Clear the blocking gates below first.
Article file: `blog/luxury-pret-uk-buyers-guide.html` (body plus Article, BreadcrumbList and FAQPage JSON-LD, paste into the Shopify article in HTML mode).

## Metadata

| Field | Value | Length |
|---|---|---|
| Title tag | Luxury Pret UK: A Buyer's Guide to Pakistani Ready-to-Wear | 58 characters |
| Meta description | Luxury pret is stitched Pakistani designer wear between everyday pret and bridal. See UK prices in pounds, how it fits, alteration costs and where to buy. | 154 characters |
| H1 | What Is Luxury Pret? A UK Buyer's Guide to Pakistani Ready-to-Wear | 66 characters |
| Shopify blog | News | |
| URL slug (handle) | `luxury-pret-uk-buyers-guide` | |
| Live URL | https://houseofanaya.co.uk/blogs/news/luxury-pret-uk-buyers-guide | |
| Byline | Khadija Fatima, fashion graduate of the National College of Arts | |
| Dates | Published 7 October 2026, last updated 7 October 2026 (set both to the real publish date) | |

## Image slots (3, all commented out in the HTML until real photos exist)

| Slot | Placement | Suggested filename | Alt text (match it to the photo actually used) |
|---|---|---|---|
| 1 | Hero, under the opening answer | `hue-pret-farasha-luxury-pret-set.webp` | Hue Pret Farasha luxury pret shirt, trouser and dupatta set laid out together |
| 2 | "What is luxury pret?" | `luxury-pret-neckline-embroidery-close-up.webp` | Close-up of embroidery on the neckline of a Pakistani luxury pret shirt |
| 3 | Inspection box, "How does luxury pret fit?" | `pre-dispatch-measurement-check-lahore.webp` | A stitched outfit being measured with a tape before dispatch at the House of Anaya workshop in Lahore |

Use original photos, not stock. Slot 3 only if a real photo of the pre-dispatch check exists. Once slot 1 is live, add its URL as `image` in the BlogPosting schema.

## Funnel note

- Primary money page: `/collections/weddings` ("Pakistani wedding dresses UK", 1,036 products). Two links: the third paragraph (about 195 words in, above the table of contents) and the closing section.
- Designer collections: `/collections/hue-pret` and `/collections/kanwal-malik` in the price table, `/collections/zara-shahjahan` in the designers section. All confirmed to exist with products on 7 October 2026.
- WhatsApp CTA (+44 7403 258324) in the fit section and the closing section.
- Supporting links (all confirmed published): ready-to-wear vs made-to-measure, Pakistani dress sizing in the UK, wedding designers UK, embroidery guide, fabrics guide, velvet outfits, first-wedding guest guide, nikkah, mehndi and baraat guides, wedding-outfit timeline, designer dress terms. Pages: stitching-guidelines, designers, disclaimer, about-us. Policies: shipping and refund.
- Open decision: a luxury pret reader is usually a guest or Eid shopper, so `/collections/formals` ("Luxe Formals", 350 products) may convert better than `/collections/weddings` as the lead link.
- Inbound links to add after publishing (not done): from the ready-to-wear vs made-to-measure post, the sizing guide, the first-wedding guest guide and the party wear guide, anchored on "luxury pret".

## Foundations: gates to clear before publishing

Blocking:

1. **Reconcile the store's contradictions.** The article avoids them; the store must not publish them.
   - Dispatch: your USP says 10 to 15 working days, the shipping policy says 8 to 10 (15 for heavy handwork), the sizing post says 9 to 12, the About page says 9 to 12 days delivered.
   - Stock model: the About page says some pieces ship ready from stock, the refund policy says every outfit is stitched to order after purchase.
   - Returns: the About page and two blog posts say ready-to-wear can be returned, the terms of service say returns are accepted on unstitched items only, the refund policy says sizing issues get alteration, not refund. "14-day returns" is really a 14-day free alteration window.
   - Cancellation: 24 hours (refund policy) versus 1 hour (shipping policy).
   - "Free UK delivery": not stated in any policy.
   - Legal name: policies and About page say House of Anaya Ltd (17366626). The AEO skill constant says Anaya Fabrics Ltd.
2. **Author page and ownership.** No Khadija Fatima page exists and the About page names only Aleem and Ali. Create the page, then change the byline link and the schema `author.url`. Khadija must review the draft, add one or two first-hand observations, and you decide whether to disclose AI assistance.
3. **Re-verify live prices on publish day.** Hue Pret ran from £274.95 to £354.95 (28 pieces). Kanwal Malik Maahi Festive 26, six sampled pieces, ran from £249.99 to £334.99. The date and figures appear in the opening answer, price section, FAQ and footer.
4. **Confirm owner-supplied claims.** "More than 70 designer brands" is supported by the collections list. "Since 2023" was removed because nothing on the site supports it, and company number 17366626 looks like a recent registration (an inference, check Companies House). "Authorised" is worded as the About page words it: a number of designer houses.

Non-blocking:

5. Bridals collection has placeholder prices (£0 and £2,000,000). Fix before any bridal pricing content.
6. Three unpublished drafts on luxury formal wear overlap this theme. Merge or hold them.
7. The `/policies/refund-policy` and `/policies/shipping-policy` URLs are standard Shopify paths referenced by your About page. They could not be fetched from the build environment, so click them once.
8. Add a named quote from Khadija and a featured image.
9. Not done: GSC near-miss pull, live-engine citation tests, and full competitor page teardowns (their sites were blocked from the build environment). Retest the query set at plus 4 and plus 8 weeks after publishing.
