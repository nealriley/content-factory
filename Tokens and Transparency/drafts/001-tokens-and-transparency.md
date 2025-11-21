# Tokens and Transparency

Clear, buyer-ready take on pricing LLM work by the token—and how to make it fair.

## Why credits feel unfair
Elena Verna’s “My beef with AI credit pricing” (Nov 2024) calls out the pain: credits hide the real price, feel arbitrary, and make support teams absorb the anger when value silently shrinks.
> [!warning] REVIEW: confirm Elena Verna roles and affiliations before publishing.
Credits also block apples-to-apples comparisons. You buy an abstract bucket, then discover tokenization quirks, formatting overhead, and provider swaps change the burn rate midstream.
The result: buyers feel like the goalposts move, and vendors lose trust even when the tech is solid.

## The transparent alternative
Expose the commodity: model intelligence priced per token, with input and output separated.
Give buyers the same levers you use: model choice, context length, compression/formatting options, and clear multipliers for speed/quality tiers.
Keep the SKU map steady—if you swap models or tokenizers, flag it and show the effect on expected burn.

## Token basics
Tokens are the atomic units a model reads (input) and writes (output).
Input tokens cover prompts, system messages, retrieved snippets, and formatting overhead; output tokens cover generated text.
Tokenization differs by provider, so the same “100 words” can tokenize differently and skew cost.
Compression, casing, and formatting (tables, JSON, markdown) change token counts; longer context windows can reduce round-trips but raise per-call burn.

## Pricing models in play
Per-token (transparent, scalable): pay per 1M input/output tokens with clear tier multipliers.
Per-request (simple caps): predictable per-call fees work for fixed templates but hide token variance.
Bundles/credits (guardrails): prepaid pools cap spend but often obscure real unit costs.
Subscriptions (seat/outcome): best when value maps to user seats or clear deliverables, not raw model usage.

## When transparency works
Stable menu of named models and predictable tokenization.
Buyers who want cost control, comparability, and to tune prompts/contexts for efficiency.
Workloads where deterministic steps (retrieval, parsing) are separate and priced plainly.

## When transparency breaks
Vendors swap models or tokenizers behind the scenes, shifting burn with no notice.
Outputs vary widely (creative writing, ideation), making token forecasts loose.
Heavy orchestration hides deterministic steps inside one “action,” muddying what was generative vs. procedural.
Some value maps better to outcomes or seats, not raw tokens.

## Buyer checklist (normalize across vendors)
- Get a reference price per 1M input tokens and per 1M output tokens, with named models and assumed context lengths.
- Ask for slow/fast tier multipliers and whether they change model families.
- Verify caps, alerts, and graceful throttles (not hard stops) at run/day levels.
- Confirm whether models or tokenizers can change mid-contract and how changes are communicated.
- Separate deterministic charges (retrieval, parsing, hosting) from generative charges, and ask how they’re metered.

## Vendor checklist (make transparency lovable)
- Publish reference prices per 1M input/output tokens and keep a changelog when they move.
- Show preflight estimates of expected input/output burn for each run, with context-length assumptions.
- Expose speed/quality tiers plainly; explain when a tier implies a model change.
- Unbundle deterministic steps from LLM output; make their metering explicit or fixed-fee.
- Share efficiency gains with customers and offer guardrails (caps, alerts, graceful downgrades to slower/cheaper tiers).

## Social snippets
- “LLM pricing without fine print: price the commodity—tokens—instead of credits, and show the burn before you run.”
- “If vendors swap models or tokenizers quietly, transparency breaks. Publish reference token prices and preflight estimates or expect churn.”

## What to watch next
Token costs continue to fall, and buyers will push harder for clear per-token menus instead of credit pools.
Credits may stick around as spend guardrails for volatile workloads, but expect renewed pressure for transparent unit prices with caps and alerts on top.
