# AGENTS playbook

Working rules for producing projects like `Tokens and Transparency`, with mirrored `drafts/` and `snippets/` folders per project.

## Folder layout (per project)
- Root folder name: short, readable title (e.g., `Tokens and Transparency`).
- `drafts/`: long-form pieces and format-specific variants (article, landing, email, deck notes). Multiple drafts allowed; keep each in its own file.
- `snippets/`: modular, stand-alone paragraph-level pieces sized to be reused or combined.
- `material/`: reference hub for links to source docs, research, and datasets; favor markdown link lists over stored binaries.
- File naming: `NNN-kebab-title.md` where `NNN` is zero-padded order of creation, not quality rank.

## New project setup
- Create the project folder plus `drafts/`, `snippets/`, and `material/` subfolders immediately.
- Add a `material/README.md` that lists live links to reference docs, data sources, and any verification notes; update it as sources change.
- Capture a 3–5 bullet brief at the top of the first draft to anchor goal, audience, and promise.
- Log any facts needing verification inside drafts with callouts (e.g., `[!warning] REVIEW:`) and resolve before publish.

## Project kickoff
- Confirm `drafts/`, `snippets/`, and `material/` exist and are linked from the project root.
- Record initial sources and links in `material/README.md`; keep drafts referenced to those sources for traceability.

## Draft workflow
- Start from an outline: problem → stakes → alternative(s) → proof/examples → action.
- Produce multiple draft types as needed: flagship article, concise landing copy, email, social thread scaffold, sales one-pager. Each lives in its own file in `drafts/`.
- Keep paragraphs short and scannable; front-load claims, add supporting detail after.
- Explicitly separate reusable checklists, definitions, and proof points that can be promoted to snippets.
- When citing numbers or roles, flag for verification unless sourced and linked.
- End each draft with a quick reuse map: which snippets already exist or should be cut next.

## Snippet workflow
- One idea per snippet; it must stand alone without surrounding context.
- Keep to 1–4 sentences; ensure it contains a hook plus a result/implication so it is composable.
- Derive snippets from drafts after each revision pass; avoid duplication by adding angles (risk, how-to, example, takeaway).
- Note provenance lightly in the snippet body if format-sensitive (e.g., “For landing pages:”).
- Treat snippets as building blocks for longer pieces; prefer specificity over slogans.
- When capturing snippets from the end user, ask for the structure `snippet: <SNIPPET_CONTENT>`; store each into `snippets/NNN-kebab-title.md` with one snippet per file and maintain numbering.

## Quality and consistency
- Voice: clear, direct, buyer-ready; avoid hype and filler.
- Transparency: declare assumptions, keep terminology consistent, and expose trade-offs.
- Structure: prefer markdown headings and lists for clarity; avoid burying key claims.
- Hygiene: no trailing TODOs; resolve or flag. Keep ASCII; avoid emoji.
- Versioning: increment the numeric prefix when adding new drafts/snippets; keep older files for comparison rather than overwriting.

## Writing guidance (drawn from plain-language best practices)
- Audience first: state the reader’s goal and pain early; avoid insider jargon unless defined.
- Lead with the conclusion, then the “why” and evidence; keep sentences under ~20 words where possible.
- Prefer active voice and concrete verbs; replace abstractions with examples or numbers.
- Chunk information with headings, bullets, and short paragraphs to lower cognitive load.
- Maintain consistency in terms (e.g., “tokens” vs. “credits”); don’t swap labels mid-piece.
- Show trade-offs explicitly (speed vs. quality; transparency vs. simplicity) rather than implying them.

## Editing workflow
- Pass 1 (structure): check the outline against the problem→stakes→alternatives→proof→action flow; remove tangents.
- Pass 2 (clarity): shorten sentences, swap passive for active, cut filler, and tighten verbs/nouns.
- Pass 3 (evidence): verify names, roles, numbers, dates; add source notes or `[!warning] REVIEW:` tags for anything pending.
- Pass 4 (voice and coherence): ensure tone is direct and confident; align terminology across drafts and snippets.
- Pass 5 (reuse prep): lift strong standalone paragraphs into `snippets/`; label any format-specific notes (“For email: …”).
- Final check: run a skim for scannability—headings/bullets in place, lead claim early, CTA/action clear.

## Reuse and assembly
- Before drafting from scratch, scan existing snippets across projects for reusable blocks.
- When assembling a new piece, map required beats to snippet IDs, then fill gaps with fresh writing.
- After assembly, backfill any strong new paragraphs into `snippets/` for future use.
