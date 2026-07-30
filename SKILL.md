---
name: project-ops-research
description: Research an industry, niche, product, website category, competitor, or business idea for overseas project operations and go-to-market planning, then deliver the result as a PPTX presentation. Use for project operations research, overseas market research, product research, competitor analysis, SEO analysis, Google Ads analysis, paid traffic analysis, export/going-global research, 项目运营调研, 行业调研, 产品调研, 竞品分析, SEO分析, Google投放分析, 投流分析, 出海项目调研, or when the user gives an industry, product, competitor company, or competitor URL and wants market overview, competitor discovery, traffic channel diagnosis, SEO structure and keyword analysis, ad analysis, promotion SOPs, expected outcomes, and actionable entry recommendations.
---

# Project Ops Research

Use this skill to create a practical overseas operations research deck from a user's industry, product, competitor company, or competitor URL.

The default deliverable is a `.pptx` file, not only a text answer. Include a short chat summary with the file path after creating the deck.

## Inputs

Identify which input mode the user gave:

- **Industry/product only**: Discover competitors from search results and public market signals.
- **Competitor company or URL provided**: Deep-dive the provided targets first, then add extra market competitors only if useful.
- **Mixed input**: Treat provided competitors as required targets and use the industry/product to find additional benchmark competitors.

Ask a clarifying question only when the product/category, target country, or language is too ambiguous to research responsibly. Otherwise state assumptions in the deck.

## Required research workflow

1. Define the research scope:
   - Product/category.
   - Target overseas market and language.
   - Buyer type: consumer, B2B, distributor, brand owner, local service buyer, or mixed.
   - Research limitations and confidence level.
2. Analyze the macro environment:
   - Current overseas market status for the industry or product.
   - Demand drivers, customer use cases, price bands, buying channels, and seasonality.
   - Market size or trend signals from authoritative or observable sources when available.
   - Platform/channel landscape: Google, Amazon, Etsy, TikTok, Instagram, YouTube, Pinterest, marketplaces, distributors, and niche communities as relevant.
   - Compliance, trust, logistics, certification, or cultural barriers.
3. Discover or confirm competitors:
   - If the user provides competitor URLs or companies, analyze those exact targets.
   - If no competitors are provided, inspect the first 8 Google result pages when possible, or the closest available web search equivalent. Capture how many real competitors appear, which result types dominate, and which brands repeatedly surface.
   - Exclude pure directories, news articles, generic marketplaces, and listicles unless they reveal brands or are themselves the business model.
   - Select the strongest competitors or benchmark sites for deep analysis. Prefer sites with strong search visibility, estimated traffic, paid ad activity, brand traction, marketplace traction, or a learnable operating model.
4. Build a competitor data table:
   - Domain and URL.
   - Company or brand name.
   - Country/region.
   - Founding time, domain age, or earliest public evidence.
   - Business model and target customer.
   - Main products/offers and price range.
   - Website technology stack.
   - Estimated traffic and traffic source mix.
   - Dominant acquisition channel hypothesis.
   - Evidence links and confidence level.
5. Diagnose each competitor's operating model:
   - Product positioning, offer structure, pricing, packaging, trust assets, and conversion path.
   - Website structure, navigation, landing pages, product/category templates, blog/resources, FAQ, reviews, and email capture.
   - Traffic channels: SEO, Google Ads, shopping ads, Meta/TikTok ads, affiliates, influencers, marketplaces, distributors, PR, social, email, or community.
   - What appears to be driving growth and what is weak or missing.
6. Branch by channel:
   - **SEO-led**: Analyze site architecture, page templates, keyword clusters, ranking pages, title/meta patterns, internal links, content depth, freshness, schema, backlinks/PR, programmatic SEO, and conversion paths.
   - **Paid traffic-led**: Analyze visible ad channels, ad copy, offer, landing pages, likely keywords/audiences, CPC pressure, funnel economics, rough ROI hypothesis, and payback risk.
   - **Marketplace-led**: Analyze Amazon/Etsy/app-store listings, ratings, review count, pricing, bundles, images, keywords, bestseller/category rank signals, and review pain points.
   - **Social/influencer-led**: Analyze content formats, hooks, posting rhythm, creator partnerships, UGC angle, viral visual moments, and landing flow.
   - **B2B/distributor-led**: Analyze wholesale pages, catalog structure, MOQ, distributor recruitment, trade shows, certifications, and reseller support materials.
7. Summarize the actual current situation:
   - Whether the category is already crowded or still early.
   - Whether competitors mainly win by SEO, paid traffic, social content, marketplace presence, distribution, or brand.
   - Which operating model is most realistic for a new entrant.
   - What capabilities are required before entering.
8. Provide entry recommendations:
   - Positioning and differentiation.
   - Product/offer/pricing suggestions.
   - Website and funnel requirements.
   - Channel strategy.
   - Starting SOP for each recommended promotion method.
   - Expected results, timeline, required budget/resources, and key metrics.

## Research sources

Browse the web for current evidence. Use a mix of:

- Google search results and SERP patterns.
- Competitor websites, sitemaps, robots.txt, page source, product pages, blogs, FAQs, and landing pages.
- Similarweb, Semrush, Ahrefs, SpyFu, BuiltWith, Wappalyzer, Store Leads, EcomScout, or comparable public snippets when available.
- Google Ads Transparency Center, Meta Ad Library, TikTok Creative Center, YouTube, Pinterest, Amazon, Etsy, app stores, review sites, affiliate pages, and social profiles.
- Official company pages, WHOIS/ICANN lookup, Wayback Machine, Crunchbase, LinkedIn, filings, press releases, and trusted industry reports.

Treat traffic, CPC, keyword volume, revenue, and ROI as estimates unless sourced from official disclosures. Label assumptions and confidence level.

## Search pattern

Use multiple query families instead of one generic search:

- Category intent: `[product/category]`, `best [product]`, `[product] software`, `[product] service`, `[product] supplier`.
- Commercial intent: `buy [product]`, `[product] pricing`, `[product] quote`, `[product] near me`, `[product] for [customer segment]`.
- Comparison intent: `[competitor] alternatives`, `best [product] for [use case]`, `[product] reviews`.
- SEO footprint: `site:competitor.com`, `site:competitor.com/blog`, `site:competitor.com/resources`, `site:competitor.com/collections`, `site:competitor.com/products`.
- Ads and acquisition: `[competitor] ads`, `[competitor] affiliate program`, `[competitor] coupon`, `[competitor] partner program`.
- Company history: `[brand] founded`, `[brand] company`, `[brand] Crunchbase`, `[domain] WHOIS`, `[domain] Wayback Machine`.

For Chinese users, search both Chinese and English terms when the market may be global. For China-local research, include Baidu, Xiaohongshu, Douyin, WeChat official accounts, 1688, Taobao, Tmall, JD, and industry forums when useful.

## PPTX deliverable

Always create a PPTX deck for a complete research request. Use `references/report-template.md` as the slide outline.

Deck requirements:

- Use concise slide titles with clear conclusions.
- Put data tables in slides when they help comparison.
- Use charts or simple matrices when data is available.
- Put source links in slide footers, speaker notes, or a final source appendix.
- Separate facts from estimates and recommendations.
- Make the deck readable for business decision-making, not academic reporting.
- Use Chinese output when the user writes in Chinese unless they request another language.

If PPTX creation tools are unavailable, produce the complete slide-by-slide Markdown outline and clearly state that the PPTX file could not be generated.

## Practical cautions

- Similarweb, Semrush, Ahrefs, SpyFu, BuiltWith, Wappalyzer, and ad libraries can disagree. Explain which signal is being used.
- Do not infer ROI as fact. State funnel assumptions: CPC, conversion rate, average order value or subscription value, gross margin, repeat purchase, and payback period.
- For SEO, separate what is visible now from what likely caused growth. Current structure may be the result, not the original growth lever.
- For young domains with high traffic, check paid ads, expired domain reuse, influencer campaigns, PR, redirects, viral social channels, and marketplace traction.
- Do not present private or scraped personal data. Stay within publicly accessible information.
