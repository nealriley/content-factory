# Tokens as a Pricing Instrument: An Academic Breakdown

Brief:
- Goal: ground “credits/tokens” in pricing theory, connect them to commercial strategies, and answer what else can solve token-based billing challenges.
- Audience: product, finance, and pricing leaders reconsidering metered AI pricing after Elena Verna’s critique.
- Promise: define tokens precisely, map them to workable models, and propose interventions beyond opaque credits.
- Source: Elena Verna, “My beef with AI credit pricing” (Lovable), plus internal snippets queried via bcup.

## 1. What are tokens in pricing terms?
With new technology comes new pricing models, but the one we’re all using right now is AI Credits. Companies use credits to make sure that usage doesn’t spike out of control and bankrupt them, but credits create problems. Tokens are a unitized meter for variable cost drivers; in microeconomics, they are the per-unit leg of a two-part tariff layered on top of access. Each company defines credits differently and doesn’t share definitions; some map credits to tokens 1:1, some 1:10, some 1:1000, others have “slow” unlimited tiers. Token billing has two dimensions—inputs (prompt tokens) and outputs (completion tokens)—and tokenizers differ across models, so even the meter is inconsistent. Value-added resale of LLM compute via opaque “credits” adds another layer of ambiguity because the underlying unit is neither defined nor stable.

## 2. How tokens map to commercial strategies
Pure per-token pricing maximally aligns price with cost but creates bill shock, volatile revenue, and support load. Baseline subscription plus metered overages keep a platform fee or seat minimum, then charge tokens for variable-heavy features. Prepaid usage blocks: sell token packs that roll over or expire quarterly, paired with a light base fee. Commit-to-consume: annual commitment priced on expected token use, reconciled quarterly; buyers get a discount for predictability, vendor protects revenue. Efficiency incentives: lower token burn for optimized workflows or off-peak usage; track burn rates by customer segment to adjust pools and discounts.

## 3. Failure modes of token-based billing (per Elena and industry)
You have no idea how much each action costs; lack of predictability deters customers and ties to fairness. Perception of how many credits an action should cost differs from actual compute cost; customers learn in retrospect and feel taken advantage of. Arbitrary definitions remove apples-to-apples comparison and create a support tax when customers try to estimate costs or dispute usage. Because the meter is arbitrary, vendors can silently make each action cost more credits to hit revenue targets. Industry-wide ambiguity compounds this: mismatched tokenizers across models, input vs. output splits, and opaque “credit” bundles for value-added LLM resale widen the gray area and make benchmarking harder.

## 4. What else can be done? Design interventions beyond opaque credits
Define the unit rigorously and publish it; map actions to expected burn so customers can see cost drivers. Show balances, burn rates, and forecasted runways in-product; let users simulate changes in usage to see savings. Offer a predictable anchor (base fee or seat floor) so finance can model spend, and use tokens only for variable-heavy value. Sell prepaid packs with rollover or quarterly expiry and use commit-and-true-up constructs to exchange predictability for discounts. Let customers toggle between user-based and metered options to fit their pattern, and reward efficiency by lowering burn for optimized workflows or off-peak usage instead of quietly inflating burn.

## 5. Closing: a path off opaque credits
Tokens are useful as meters, not as black boxes: visible meters paired with predictable anchors, customer choice of model, and efficiency incentives can deliver fairness, comparison, and predictability. As costs drop toward more normal profitability, companies will revert to measurable, transparent models (per-user or concrete units); until then, a defined meter plus clear contracts can keep tokens legible and trusted.
