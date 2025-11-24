# Tokens and Transparency

Brief:
- Goal: explain how teams can use tokens/usage as a transparent meter without letting it dominate pricing.
- Audience: product and finance leads shaping hybrid usage models.
- Promise: give examples of transparent usage meters paired with predictable anchors.
- Source inspiration: Lovable management piece on AI credits (Elena Verna, “My beef with AI credit pricing,” Nov 14, 2025).

## Problem
Teams like the clarity of metered billing, but pure pay-per-use makes revenue volatile and buyers nervous about surprise bills. Product teams need a transparent meter without forcing customers to live entirely on tokens.

## Stakes
- Without a predictable anchor, finance leaders block deals because spend is hard to forecast.
- If usage meters are hidden or unclear, customers assume the vendor is gaming the bill.
- Over-indexing on flat plans starves heavy users and removes the incentive to optimize efficiency.

## Alternatives that mix predictability and tokens
- Baseline subscription plus metered overages: keep a platform fee or seat minimum, then charge tokens for variable-heavy features. Works when there is a clear “floor” of value each month.
- Prepaid usage blocks: sell token packs that roll over or expire quarterly, paired with a light base fee. Helps procurement budget an envelope while keeping usage variable.
- Tiered pools with visibility: buckets of included tokens per tier, with real-time balance shown in-app. Customers understand what is included and when they will pay more.
- Commit-to-consume: annual commitment priced on expected token use, reconciled quarterly. Buyers get a discount for predictability; vendor protects revenue.
- Efficiency incentives: lower token burn for optimized workflows or off-peak usage. Encourages behavior that benefits both sides without hiding the meter.

## Proof and examples
- Developer platforms often blend seats for collaboration with per-unit execution charges. [!warning] REVIEW: add concrete examples and ranges.
- Data vendors sell flat data access plus per-query compute to keep heavy users honest. [!warning] REVIEW: cite a public pricing page.
- Messaging APIs combine monthly minimums with per-message rates, signaling the meter while keeping invoices steady. [!warning] REVIEW: add reference link.
- Elena Verna (Lovable) lists why opaque credits fail: unpredictable bills, perceived unfairness, no apples-to-apples comparison, and easy exploitation; she expects a shift back to transparent meters as LLM costs drop.

## Action
- Choose a visible meter (tokens, requests, compute time) and expose it in-product.
- Anchor revenue with a base fee or minimum commit, then graduate usage when value scales.
- Publish the meter math in FAQs and invoices; let customers self-forecast before purchase.
- Track burn rates by customer segment to adjust pools, discounts, and efficiency incentives.

## Reuse map
- New snippets to cut: anchors for hybrid models; prepaid packs; commit-to-consume explainer; transparency checklist.
- Existing snippets: 001-hybrid-anchor, 002-prepaid-packs, 003-commit-to-consume, 004-transparency-checklist, 005-efficiency-incentives, 006-credit-unpredictability, 007-fairness-gap, 008-no-apples-to-apples, 009-support-burden, 010-exploit-incentives, 011-lovable-efficiency, 012-return-to-transparent.
