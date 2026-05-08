# IG/FB Landing-Page Parity — Priority List

**Goal:** every IG/FB ad creative should link directly to a polished product page, not the homepage. Today, 100% of IG and 80% of FB sessions land on `/` and produce 0 cart adds. Each product below is scored on whether its page is ready to be the destination of a paid ad.

**Source data:** Shopify analytics (90d sessions/orders), Shopify Admin API product metadata.
**Store:** urbnova.net | **Snapshot date:** 2026-05-08

---

## Scoring rubric

A product is "ad-ready" if it meets all of:
- Title under 80 chars, scannable hook
- 5+ images / media items
- Description ≥ 200 chars with a clear value prop
- Clean handle (no internal IDs, no `chatgpt-ai-` prefix, < 80 chars)
- Inventory > 20 (won't sell out mid-campaign)
- Price $10–$60 (impulse-buy band for IG/FB)

**Status legend:** ✅ ad-ready · ⚠️ needs minor fixes · ❌ blocked

---

## TIER 1 — HERO products (run ads here first)

### 1. ⭐ Medicube Korean Brightening Deodorant — Vanilla Pistachio
- **URL:** `/products/new-medicube-deodorant-vanilla-pistachio-fresh-that-lasts-24-hour-odor-control-no-aluminum-baking-soda-parabens-phthalates-ethanol-brightening-smoothing-for-dark-underarms-with-kojic-acid-turmeric-korean-skincare-k-beauty`
- **Status:** ✅ Ad-ready
- **Why:** **The only product converting in 90d** — 18 mobile sessions → 5 cart adds (28%) → 2 checkouts. Already won. Scale this.
- **Action:** Build IG/FB campaign immediately. Use this as the creative-and-LP template for all other Tier 1 products.
- **One fix:** Handle is 240+ chars — shorten to `/products/medicube-brightening-deodorant-vanilla-pistachio` for cleaner ad URLs.

### 2. Medicube Korean Brightening Deodorant — Original (Kojic Acid)
- **URL:** `/products/medicube-korean-brightening-deodorant`
- **Status:** ✅ Ad-ready
- **Why:** Top revenue product (2 orders, $70.64). Same product family as #1 — Korean K-beauty deodorant niche is the validated winner.
- **Action:** Bundle test against #1 in IG/FB ad set; whichever wins becomes flagship.

### 3. Tarte Big Stick Energy Duo (Shape Tape Concealer + Brush)
- **URL:** `/products/tarte-big-stick-energy-duo-shape-tape-concealer-stick-brush`
- **Status:** ✅ Ad-ready
- **Why:** 23 images, 15 variants, polished long-form description, $68.99. Tarte is a recognizable brand — high IG/FB CTR potential.
- **Watch:** Inventory only 30 — bump to 100+ before scaling spend.

### 4. JLO Beauty Star Filter Complexion Booster
- **URL:** `/products/jlo-beauty-that-star-filter-complexion-booster-glowy-skin-enhancer-with-mineral-pigments-vitamin-e-hydrators-for-radiant-skin-use-with-or-without-makeup`
- **Status:** ⚠️ Shorten handle
- **Why:** 13 images, 4 variants, $44.99 — celebrity brand pull.
- **Watch:** Inventory only 40.

### 5. One-Step Eyebrow Stamp & Stencil Kit
- **URL:** `/products/ptwop-one-step-eyebrow-stamp-shaping-kit-set-waterproof-women-makeup-brows-stencil-and-kit-tattoo-eyebrow-brush-shipping-free`
- **Status:** ⚠️ Shorten handle, raise price
- **Why:** 11 images, 5 variants, 4000 inventory, classic IG/TikTok viral product format.
- **Watch:** Listed at $3.90 — too cheap to cover ad CPC. Reprice to $14.99–$19.99 minimum.

### 6. Stainless Steel Tongue Scraper
- **URL:** `/products/stainless-steel-tongue-scraper`
- **Status:** ✅ Ad-ready
- **Why:** 11 images, 6 variants, clean handle, 6000 inventory. Hook ("Fresh Breath in 5 Seconds") is built for IG.
- **Watch:** $7.10 is below CPC viability — bundle as 2-pack at $14.99.

---

## TIER 2 — Already received social traffic (creative exists, fix the LP)

These pages have been ad destinations on FB/TikTok in the last 90 days but produced **zero cart adds**. The creative is reaching them — the *page* is failing to convert.

| # | Product | Channel | Sessions (90d) | Issue |
|---|---|---|---|---|
| 7 | Water Bank Blue Hyaluronic Moisturizer | TikTok | 4 | Handle is 200+ chars |
| 8 | Maybelline Super Stay Better Skin Powder | TikTok | 4 | Title is buried — no hook |
| 9 | Rouge Couture Satin Lipstick (Promenade) | TikTok | 4 | Vendor not branded; weak FOMO |
| 10 | Forever Natural Velvet Foundation 3N | TikTok | 2 | **Duplicate page** — see below |
| 11 | Addict Hydrating Shine Lipstick | TikTok | 2 | No urgency / social proof |
| 12 | Addict Lip Maximizer | TikTok | 1 | Same as above |
| 13 | Organic Face Sunscreen SPF 50 | Facebook | 1 | Weak hero image |
| 14 | Dr. Melaxin Cemenrete Eye Cream | Facebook | 1 | K-beauty vertical — pair with Medicube |
| 15 | Rootation Berberine Gummies (2-pack) | Facebook | 1 | Wellness vertical, separate audience |
| 16 | Lopeie Fluorescent Nectar Perfume | Facebook | 1 | Fragrance vertical, separate audience |
| 17 | MAC Retro Matte Ruby Woo Lipstick | Facebook | 1 | Iconic SKU — high IG/FB CTR potential |
| 18 | Korean Collagen Sheet Mask 5-Pack | Facebook | 1 | K-beauty hero — pair with Medicube |
| 19 | Rosewater Hyaluronic Toner | Facebook | 1 | Vegan/cruelty-free hook is good |
| 20 | Lip Perfector Peptide Plumping Gloss | Facebook | 1 | Vanilla scent + "instant shine" works on IG |
| 21 | Electric Shaver for Women | Facebook | 1 | Off-vertical for beauty audience |
| 22 | Right Wing Naturals Beef Tallow Balm | Facebook | 1 | Off-vertical; men's grooming |
| 23 | Organic Rosehip Seed Oil | Facebook | 1 | Clean-beauty hero |
| 24 | Fresh Skin Apricot Face Scrub | Facebook | 1 | Skincare hero |
| 25 | BB Cream Beauty Balm Medium | Facebook | 1 | **Duplicate page** — see below |
| 26 | Organic Beauty Hydrating Shampoo | Facebook | 1 | Hair-care vertical |

---

## TIER 3 — BLOCKED until handles/pages are fixed

These have **internal Shopify IDs leaking into URLs** — looks broken/spammy in ads, and breaks SEO. Must fix before any ad spend.

| # | Bad URL | Issue | Fix |
|---|---|---|---|
| 27 | `/products/69a1fde2091a2db7a8c8608f-bb-cream-beauty-balm-medium-hypoallergenic-and-fragrance-free-15-ounces` | Internal MongoDB ID prefix | Rename to `bb-cream-medium-hypoallergenic` |
| 28 | `/products/69a20311091a2db7a8c8609d-forever-natural-velvet-3n-neutral-by-christian-for-women-035-oz-foundation` | Internal MongoDB ID prefix; duplicate of TikTok-traffic page | Merge with `forever-natural-velvet-3n-neutral-…` and 301 redirect |
| 29 | `/collections/all-products-chatgpt-ai-product-description` | Collection name reveals AI-generated content publicly; **9 Google sessions in 90d** | Rename to `/collections/all-products` and 301 redirect |
| 30 | `/products_preview` | Internal preview path indexed; 17 sessions | Add to robots.txt; noindex |
| 31 | `/password` | Storefront partially gated; 6 sessions | Audit Online Store password settings |

---

## Summary

- **Run ads to first:** #1 (Medicube Vanilla Pistachio Deodorant) — proven 28% cart-add rate.
- **Build creative around Tier 1:** 6 products, all in $15–$70 range, all with rich content.
- **Audit/rewrite Tier 2 pages** before paying for more traffic to them.
- **Block all Tier 3 issues today** — they're costing trust on every impression.

## Cross-cutting fixes (apply to most products)

1. Handles >100 chars: shorten across the catalog. Set up 301s.
2. Add **trust badges** + **review widgets** above the fold (Loox/Judge.me).
3. Add **urgency/scarcity** ("Only X left") for Tier 1 — Shopify supports this natively.
4. Add an **email capture popup** to homepage and PDPs (feeds Klaviyo).
5. **Niche the brand:** the catalog mixes K-beauty, Western beauty, men's grooming, supplements, and travel bags. IG/FB ads convert when the audience is clear. Pick K-beauty + skincare as the lead vertical (Medicube is your proof).
