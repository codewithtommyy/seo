# google-search-seo-match

Reusable Codex skill for auditing pages and content against Google's official SEO Starter Guide from Google Search Central.

## Contents

- `SKILL.md`: skill trigger and workflow
- `agents/openai.yaml`: UI metadata
- `references/google-seo-starter-guide-vi.md`: structured Vietnamese reference distilled from the official guide

## Install into Codex

Copy this folder into your Codex skills directory, for example:

- Windows: `C:\Users\<you>\.codex\skills\google-search-seo-match`

## Usage

Call the skill in Codex with prompts like:

- `$google-search-seo-match audit URL này: https://example.com`
- `$google-search-seo-match so sánh bài vi?t này v?i Google SEO Starter Guide`
- `$google-search-seo-match check title, meta description, canonical và content page này`

## Source

Official source used for the reference summary:

- https://developers.google.com/search/docs/fundamentals/seo-starter-guide?hl=vi
