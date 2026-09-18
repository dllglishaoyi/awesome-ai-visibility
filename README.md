# Awesome AI Visibility [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Tools, free checkers, research and data for **AI visibility** / **Generative Engine Optimization (GEO)**: whether ChatGPT, Claude, Gemini, Perplexity and Google AI Overviews mention or recommend a brand.

[中文版 README_CN.md](README_CN.md)

Maintained by the team behind [GeoBuddy](https://geobuddy.co). Competitors are listed on equal footing; entries are factual one-liners, no rankings. PRs welcome.

## Contents

- [Free checkers (no signup)](#free-checkers-no-signup)
- [Monitoring platforms](#monitoring-platforms)
- [Open source](#open-source)
- [Data](#data)
- [Research and reports](#research-and-reports)
- [llms.txt and crawler resources](#llmstxt-and-crawler-resources)
- [Other curated lists](#other-curated-lists)

## Free checkers (no signup)

- [GeoBuddy Free Check](https://geobuddy.co/check) - Asks ChatGPT, Claude, Gemini and Perplexity your category questions with web search on; shows mention, position and who was recommended instead. 3 checks/day.
- [Ahrefs AI Visibility Checker](https://ahrefs.com/ai-visibility-checker) - Brand Radar based checker for ChatGPT, Gemini, Copilot, Perplexity and AI Overviews.
- [Semrush AI Search Visibility Checker](https://www.semrush.com/ai-visibility/) - Free look at ChatGPT, Gemini and AI Overviews visibility.
- [HubSpot AEO Grader](https://www.hubspot.com/aeo-grader) - Composite score across ChatGPT, Perplexity and Gemini.
- [LLM Pulse free tools](https://llmpulse.ai/) - Standalone AI visibility report, robots.txt/crawlability checker, llms.txt generator.

## Monitoring platforms

- [GeoBuddy](https://geobuddy.co) - 4 engines (ChatGPT, Claude, Gemini, Perplexity), mentions, rank, recommendation-vs-alternative framing, competitors. Pro $49/mo, Business $149/mo. Publishes its own weekly [self-test](https://geobuddy.co/methodology/self-test).
- [Profound](https://www.tryprofound.com/) - Enterprise platform, 11 engines, share of voice, sentiment, prompt-level rankings.
- [Peec AI](https://peec.ai/) - AI search visibility with competitive analysis, priced by prompt count.
- [Otterly.AI](https://otterly.ai/) - Link citation analysis for AI Overviews and Perplexity, timeline tracking.
- [AthenaHQ](https://www.athenahq.ai/) - YC-backed, unified GEO scoring plus content agents.
- [Scrunch](https://scrunch.com/) - Agent experience platform: monitoring plus making sites legible to AI engines.
- [Knowatoa](https://knowatoa.com/) - AI search analytics across ChatGPT, Claude and Perplexity.
- [Rankshift](https://rankshift.com/) - Position tracking for AI-powered search.
- [ZipTie](https://ziptie.ai/) - Brand visibility monitoring across generative AI platforms.
- [Goodie](https://higoodie.com/) - AI-native GEO optimization and monitoring suite.

## Open source

- [GEO/AEO Tracker](https://github.com/danishashko/geo-aeo-tracker) - Local-first, bring-your-own-key AI visibility dashboard.
- [geo-lint](https://github.com/search?q=geo-lint) - Open-source GEO linter for content.

## Data

- [`data/brand-ai-visibility-2026-09-17.csv`](data/brand-ai-visibility-2026-09-17.csv) - AI visibility score for 164 public brands, each measured on 12 category questions across ChatGPT, Claude, Gemini and Perplexity with web search on. Snapshot of GeoBuddy's public brand pages taken 2026-09-17. Selection note: only brands with at least one mention get a public page, so this file has no 0% rows; the 59% zero-score figure comes from the full 2,000+ brand population in the report below. Every row links to its source page with the raw engine answers.

Top 10 in the snapshot:

| Brand | Score | Mentioned |
|---|---|---|
| FreshBooks | 100% | 12/12 |
| Zoom | 100% | 12/12 |
| Shopify | 100% | 12/12 |
| Poshmark | 100% | 12/12 |
| Instacart | 100% | 12/12 |
| Microsoft Teams | 100% | 12/12 |
| Acorns | 100% | 12/12 |
| Notion | 92% | 11/12 |
| Nike | 92% | 11/12 |
| Airbnb | 92% | 11/12 |

- [State of AI Search Visibility 2026](https://geobuddy.co/reports/state-of-ai-search-visibility-2026) - Aggregate over 2,000+ checked brands, refreshed from production data.

## Research and reports

- [GEO: Generative Engine Optimization (Aggarwal et al., KDD 2024)](https://arxiv.org/abs/2311.09735) - The paper that named the field; 40% visibility gains from citations, statistics and quotations.
- [AI Platform Citation Patterns (Profound)](https://www.tryprofound.com/blog/ai-platform-citation-patterns) - Which domains ChatGPT, AI Overviews and Perplexity cite most.
- [GeoBuddy methodology](https://geobuddy.co/methodology) - How scores are computed, why empty engine responses are treated as measurement failures rather than 0%.

## llms.txt and crawler resources

- [llmstxt.org](https://llmstxt.org/) - The /llms.txt proposal.
- [Awesome-llms-txt](https://github.com/SecretiveShell/Awesome-llms-txt) - Index of llms.txt files, usable as an MCP source.
- [llmstxt.site](https://llmstxt.site/) - Directory of llms.txt files with a submit form.

## Other curated lists

- [awesome-generative-engine-optimization](https://github.com/amplifying-ai/awesome-generative-engine-optimization)
- [awesome-geo](https://github.com/luka2chat/awesome-geo)
- [awesome-seo-tools](https://github.com/serpapi/awesome-seo-tools) (GEO / AI Visibility section)

## Contributing

Open a PR with a one-line factual description and a link. No rankings, no superlatives. Disclose if you work on the tool you add.

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
