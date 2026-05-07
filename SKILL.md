---
name: google-search-seo-match
description: Check whether a page, site, draft article, content plan, metadata set, or SEO implementation matches Google's SEO Starter Guide from Google Search Central. Use when the user asks to audit, compare, score, or improve content/site SEO against Google's official starter guide, including indexing, crawlability, titles, snippets, canonicalization, content quality, images, videos, links, and promotion.
---

# Google Search SEO Match

Use this skill to assess whether content or a website aligns with Google's official SEO Starter Guide, not generic third-party SEO advice.

## Core behavior

- Treat the Google Search Central SEO Starter Guide as the primary standard.
- Load [references/google-seo-starter-guide-vi.md](references/google-seo-starter-guide-vi.md) before giving a substantive audit.
- Distinguish clearly between:
  - eligibility/indexing basics,
  - crawl/render/accessibility basics,
  - search appearance improvements,
  - content quality and people-first guidance,
  - myths/non-factors.
- Prefer a gap-analysis format: `match`, `partial match`, `does not match`, `not enough evidence`.
- If the user gives only text instead of a live URL, evaluate only what can actually be inferred from that text and state the missing evidence.
- Do not invent ranking guarantees. State that changes can take time to be reflected in Google Search.

## Default workflow

1. Identify the audit target: URL, page copy, metadata, IA/URL pattern, media plan, or SEO checklist.
2. Compare it against the reference categories in the Google guide.
3. Flag concrete gaps with direct fixes.
4. Separate:
   - critical blockers,
   - high-impact improvements,
   - optional polish,
   - items Google explicitly says are not useful or are commonly misunderstood.
5. If the user wants a reusable output, produce:
   - a checklist,
   - an audit table,
   - rewritten metadata,
   - a remediation plan,
   - or acceptance criteria for writers/developers.

## Output pattern

Use a concise structure like:

- `Overall verdict`
- `Critical blockers`
- `Content and usefulness`
- `Crawl/index/render`
- `Search appearance`
- `Media and links`
- `Myths / non-actions`
- `Next fixes`

## Boundaries

- Do not say a page is "SEO compliant" unless the evidence is strong; prefer "mostly aligned" or "not yet aligned".
- Do not rely on keyword density, meta keywords, or keyword-heavy domains as meaningful ranking levers.
- If the user asks for advanced or current Google Search behavior beyond the starter guide, say so and suggest checking broader Google Search Central docs.
