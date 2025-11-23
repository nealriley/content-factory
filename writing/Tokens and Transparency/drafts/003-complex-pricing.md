# Pricing tokens is a complex world

- Audience: product and pricing leads selling AI-powered tooling.
- Promise: expose the messy reality of token pricing mechanics and how to keep it legible.
- Goal: map the traps (units, volatility, mixed models) and practical ways to steer buyers through them.
- Tone: clear, operational, and candid about trade-offs.

## Problem: the unit is slippery
Tokens are the atomic units models read and write, but price tags drift because providers tokenize differently and split input/output rates. Credits blur it further: one vendor maps a credit to a token, another to “slow mode,” and buyers can’t make apples-to-apples comparisons. If the monetizable unit is opaque, buyers attach value to actions instead of burn—and trust erodes fast.

## Stakes: complexity multiplies
- Input and output tokens price differently, and the range of model specializations is vast.
- Predictability dies when you don’t define the unit plainly or show a live tally of burn.
- Seat or outcome pricing can diverge from actual value: raise seat costs and collaboration shrinks as buyers ration access.
- Flexible journeys matter: tokens with caps for trial, then seats for ongoing use, to align incentives stage by stage.

## How complexity shows up in the wild
Helicone’s calculator highlights the gap: GPT-5 lands around $0.00125 per 1k input tokens and $0.01 per 1k output; Claude Sonnet 4.5 clocks near $0.003 per 1k input and $0.015 per 1k output. Outputs usually carry the heavier toll, so orchestration choices (long contexts, verbose completions) swing cost more than inputs suggest.

Token billing shines when buyers can forecast their own spend—common in B2B where teams know likely demand—and when they can shift between quality/cost: swap to -mini for cheaper, faster runs, or move up-tier when quality matters. Providers can also tune margins by mixing these levers, but they must show the math.

## Actions: make the mess usable
- Define the unit and keep a running tally: per-1k or per-1M input/output with clear model names.
- Show preflight estimates that split input vs. output, and flag how context choices change burn.
- Offer hybrid paths: capped token trials, then seats or outcomes once usage stabilizes.
- Publish a change log for price-impacting swaps (models, tokenizers, orchestration) before buyers feel the burn.
- Give toggle-able quality/price tiers and label trade-offs so buyers can self-optimize.

## Reuse map
- Use snippets: 002, 012, 013, 014, 015, 016, 017, 018, 019.
- Cut next: a cost-estimate template that separates input/output; a buyer-facing explainer on when to switch tiers; examples of guardrails (caps, alerts, soft throttles) that reduce support load.
