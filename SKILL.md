---
name: project-ops-research
description: Research an industry, niche, product, website category, or business idea for project operations and go-to-market planning. Use for 项目运营调研, 行业调研, 产品调研, 竞品分析, SEO分析, Google投放分析, 出海项目调研, or when the user gives an industry or product and wants competitor discovery, Google search-based market overview, high-traffic competitor website selection, domain/company age checks, website technology stack analysis, traffic channel diagnosis, SEO structure and keyword analysis, Google Ads or paid acquisition analysis, promotion model breakdown, and an actionable summary of how to enter the market and what to copy or avoid.
---

# Project Ops Research

Use this skill to turn a user's industry, product, niche, or business idea into a practical competitor and operations research report.

## Core workflow

1. Clarify the research object only if it is ambiguous. If the user gives a broad industry, define the likely target country/language from context and state the assumption.
2. Search Google or the web for buyer-intent, category, review, alternative, and problem keywords. Prefer current, location-relevant results.
3. Build an initial market overview:
   - What the product or industry does.
   - Typical customer segments and purchase intent.
   - Common monetization models.
   - Main acquisition channels visible from public data.
   - Important regulation, trust, seasonality, or platform dependency risks.
4. Identify 3-5 strong competitors:
   - Prefer competitors with strong organic visibility, high estimated traffic, repeated ranking across keywords, active paid promotion, strong brand search, or obvious market traction.
   - Exclude directories, marketplaces, news articles, social profiles, and thin affiliate pages unless they are the real competitor model.
   - Include each competitor's website URL and explain why it was selected.
5. Investigate each competitor:
   - Domain, company or brand name, country/region, business model, pricing model, and likely target customer.
   - Domain age or first-known public history when available through WHOIS, ICANN lookup, Wayback Machine, company filings, Crunchbase, LinkedIn, or official about pages.
   - Technology stack using public signals such as BuiltWith, Wappalyzer, page source, response headers, robots.txt, sitemap.xml, CMS paths, JavaScript bundles, ecommerce platform fingerprints, and analytics/ad pixels.
   - Traffic channel mix using public sources such as Similarweb, Semrush, Ahrefs, SpyFu, Google results, Google Ads Transparency Center, Meta Ad Library, app stores, social profiles, affiliate programs, review sites, and backlink data.
6. Branch the deep analysis by the dominant channel:
   - If organic search is dominant, analyze site architecture, page templates, keyword clusters, title/meta patterns, internal linking, content freshness, programmatic SEO, schema markup, backlink strategy, and conversion paths.
   - If Google Ads or paid search is dominant, analyze visible ad copy, landing pages, likely high-intent keywords, funnel structure, pricing economics, estimated CPC pressure, and a rough ROI hypothesis.
   - If social, influencer, affiliate, marketplace, community, or email appears dominant, analyze the content format, offer, distribution rhythm, trust assets, referral incentives, and retention loop.
7. Produce a final report that tells the user what to do:
   - Market opportunity and difficulty.
   - Best competitor lessons to borrow.
   - Differentiation angle.
   - Recommended acquisition strategy for the first 30, 60, and 90 days.
   - SEO structure or paid campaign plan when relevant.
   - Risks, validation steps, and key metrics to watch.

## Research quality rules

- Browse the web for current data. Do not rely only on memory for competitor lists, traffic, pricing, company age, ads, or technology stack.
- Use multiple source types when possible. Treat traffic, CPC, keyword volume, and revenue as estimates unless sourced from official disclosures.
- Prefer primary or observable evidence: the competitor's own site, sitemaps, robots.txt, ad libraries, search results, official filings, and public profiles.
- Clearly label estimates, assumptions, and confidence level.
- Include source links for factual claims and avoid overclaiming paid tool data if only snippets are available.
- If Google search itself is unavailable, use the available web search tool and explain the limitation.
- Never present private or scraped personal data. Stay within publicly accessible information.

## Search pattern

Use multiple query families instead of one generic search:

- Category intent: `[product/category]`, `best [product]`, `[product] software`, `[product] service`, `[product] supplier`.
- Commercial intent: `buy [product]`, `[product] pricing`, `[product] quote`, `[product] near me`, `[product] for [customer segment]`.
- Comparison intent: `[competitor] alternatives`, `best [product] for [use case]`, `[product] reviews`.
- SEO footprint: `site:competitor.com`, `site:competitor.com/blog`, `site:competitor.com/resources`, `site:competitor.com/locations`, `site:competitor.com/collections`.
- Ads and acquisition: `[competitor] ads`, `[competitor] affiliate program`, `[competitor] coupon`, `[competitor] partner program`.
- Company history: `[brand] founded`, `[brand] company`, `[brand] Crunchbase`, `[domain] WHOIS`, `[domain] Wayback Machine`.

For Chinese users, search both Chinese and English keywords when the market may be global. For local Chinese markets, include Baidu, 小红书, 抖音, 微信公众号, 1688, 淘宝, 天猫, 京东, and industry forums when useful.

## Competitor selection rubric

Score candidates qualitatively before choosing the final 3-5:

- Search visibility: ranks repeatedly for commercial or informational keywords.
- Traffic strength: public estimates, ranking footprint, brand search, active content library, or visible audience.
- Business similarity: sells the same product, solves the same problem, or targets the same customer.
- Operational learnability: website, funnel, ads, content, pricing, or community are visible enough to analyze.
- Market relevance: serves the user's target country, language, price band, and customer type.

If the top Google results are marketplaces or listicles, use them to discover brands, then analyze the brands.

## Output format

Use the report structure in `references/report-template.md` when the user asks for a complete research document. For quick answers, compress the same structure.

## Practical cautions

- Similarweb, Semrush, Ahrefs, SpyFu, BuiltWith, Wappalyzer, and ad libraries can disagree. Explain which signal you are relying on.
- Do not infer ROI as fact. State the funnel assumptions: estimated CPC, conversion rate, average order value or subscription value, gross margin, and payback period.
- For SEO, separate what is visible now from what likely caused growth. Current structure may be the result, not the original growth lever.
- For young domains with high traffic, look for paid ads, expired domain reuse, influencer campaigns, press, redirects, or viral social channels.
