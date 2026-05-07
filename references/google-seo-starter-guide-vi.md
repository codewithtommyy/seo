# Google SEO Starter Guide Reference

Source:
- Google Search Central, SEO Starter Guide, Vietnamese edition
- URL: https://developers.google.com/search/docs/fundamentals/seo-starter-guide?hl=vi
- Accessed: 2026-05-07

Use this file as the working reference for audits. It is a concise paraphrase of the guide, not a verbatim copy.

## 1. What the guide is for

- SEO means helping search engines understand content and helping users decide whether to visit from search results.
- Following the guide improves discoverability and clarity; it does not guarantee first-place rankings.
- Changes may take hours, weeks, or even months to show effects. Evaluate over time rather than immediately.

## 2. Discovery, crawling, rendering, indexing

- Check first whether Google already indexed the site with `site:example.com`.
- Google primarily discovers pages through links from pages it already knows.
- Important pages should be reachable through normal links, not only through internal search or hidden flows.
- Google should be able to view the page similarly to a normal user.
- Do not block essential CSS, JavaScript, images, or other resources needed to understand the page.
- If content varies by user location, verify that Googlebot's likely US-based view still sees an acceptable version.
- Use Search Console URL Inspection to understand how Google sees a URL.

## 3. Site structure and URL handling

- Keep the site structure logical and useful for people first.
- Avoid multiple URLs serving the same content when possible.
- Prefer one canonical URL per content item.
- If duplicates exist, use redirects to the preferred URL when appropriate.
- If redirects are not feasible, use `rel="canonical"`.
- Do not obsess over subdomain vs subfolder as a ranking trick; choose the structure that makes business and maintenance sense.
- Keywords in domain names or URLs provide little ranking value by themselves.

## 4. Titles and snippets

- Titles should be descriptive, specific to the page, and useful to users scanning results.
- Avoid generic, repetitive, or misleading title text.
- Snippet-relevant text should accurately reflect the page's useful content.
- Meta descriptions are useful as suggested snippet text, but they are not a direct ranking guarantee.
- Write concise, page-specific descriptions that summarize the value of the page.

## 5. Content quality and people-first content

- The strongest lever in the guide is creating content that is interesting, useful, reliable, and clearly written.
- Content should be easy to read, organized with headings and sections, and free of avoidable spelling/grammar issues.
- New content should be original rather than copied or lightly rephrased from others.
- Existing content should be reviewed and updated or removed when stale.
- Content should be helpful, trustworthy, and written for people before search engines.
- Evidence of experience or expertise can help readers trust the content.
- Think about how different users might search for the topic, but do not force every keyword variation unnaturally.
- Google's systems can often understand relevance without exact keyword matching.
- Avoid distracting ads or interstitials that obstruct the main content experience.

## 6. Links

- Links are a core way Google discovers pages and understands relationships.
- Link to relevant internal pages and trustworthy external resources when that helps users.
- Anchor text should describe the destination clearly.
- Do not add links just to stuff keywords or manipulate rankings.
- If you link to content you do not trust but still need to reference, use `nofollow` or a similar annotation.
- For user-generated content such as comments or forum posts, automatically apply `nofollow` or similar handling to user links.

## 7. Images

- Images can be an important discovery surface, especially in visual search.
- Use high-quality, clear images placed near relevant surrounding text.
- Make sure the page context helps users and Google understand the image.
- Image optimization is not only about file presence; relevance and context matter.

## 8. Video

- If a page centers on video, create high-quality video and place it on a dedicated page near relevant text.
- Provide useful title and description text for the video.
- If video is important to the site, apply video-specific SEO guidance beyond the starter basics.

## 9. Promotion

- Promote new content so people and search engines can discover it sooner.
- Useful channels include social media, communities, advertising, offline promotion, newsletters, and word of mouth.
- Natural word of mouth is one of the most sustainable long-term growth channels.
- Avoid spammy or manipulative promotion methods that could be interpreted as search manipulation.

## 10. Myths and low-value actions explicitly called out

- `meta keywords` are not used by Google Search.
- Keyword stuffing is spam and harms user experience.
- Repeating the same keyword excessively is not a good tactic.
- Keywords in the domain or URL are not a meaningful ranking shortcut.
- Subdomain vs subfolder is not a simple SEO hack; choose based on practical business needs.
- There are no secret tricks in the guide that automatically rank a page first.

## 11. Practical audit checklist

Use these questions when auditing:

- Can Google discover the page through normal links?
- Is the page already indexed?
- Can Google render the page with its essential resources?
- Is the preferred canonical URL clear?
- Is the title specific and useful?
- Does the page offer a strong, honest summary that could support a good snippet?
- Is the content original, helpful, current, and well structured?
- Are headings, paragraphs, and readability handled well?
- Are ads or interstitials getting in the way?
- Are internal/external links relevant, clear, and trustworthy?
- Are images high-quality and placed near relevant text?
- If the page is video-led, is the video page and metadata good enough?
- Is the promotion plan legitimate rather than manipulative?
- Is the team avoiding `meta keywords`, keyword stuffing, and URL/domain superstition?

## 12. Suggested verdict labels

- `Match`: clear alignment with the guide based on available evidence.
- `Partial match`: direction is correct but important gaps remain.
- `Does not match`: evidence conflicts with the guide or misses core requirements.
- `Not enough evidence`: cannot verify from the material provided.
