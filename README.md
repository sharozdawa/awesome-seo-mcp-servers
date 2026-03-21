<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=220&section=header&text=Awesome%20SEO%20MCP%20Servers&fontSize=42&fontColor=e94560&fontAlignY=35&desc=MCP%20Servers%20%E2%80%A2%20Agent%20Skills%20%E2%80%A2%20Open%20Source%20SEO%20Tools&descSize=16&descColor=ffffff&descAlignY=55&animation=fadeIn" width="100%" />

<br />

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![GitHub stars](https://img.shields.io/github/stars/sharozdawa/awesome-seo-mcp-servers?style=flat-square&color=e94560)
![GitHub last commit](https://img.shields.io/github/last-commit/sharozdawa/awesome-seo-mcp-servers?style=flat-square&color=0f3460)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)
![License](https://img.shields.io/github/license/sharozdawa/awesome-seo-mcp-servers?style=flat-square)

<br />

**The most comprehensive directory of SEO tools for AI-powered development.**

MCP servers connect AI tools (Claude, Cursor, Copilot, Codex, Windsurf) to SEO data.<br/>
Agent Skills (SKILL.md) add SEO capabilities directly inside 30+ AI agents.

<br />

[MCP Servers](#-mcp-servers) · [Agent Skills](#-agent-skills-skillmd) · [Standalone Tools](#-standalone-open-source-seo-tools) · [Gaps](#-notable-gaps-in-the-ecosystem) · [Resources](#-resources)

</div>

<br />

> [!NOTE]
> The SEO MCP ecosystem is growing fast but fragmented across dozens of directories. This list is the **single source of truth** for every SEO-related MCP server, agent skill, and open source tool — updated regularly.

---

## :globe_with_meridians: MCP Servers

### :mag: Search Console

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [mcp-gsc](https://github.com/AminForou/mcp-gsc) | 560+ | :green_circle: Active | Google Search Console with 19+ tools, regex filters, quick wins detection |
| [mcp-server-gsc](https://github.com/ahonn/mcp-server-gsc) | - | :green_circle: Active | GSC with 25,000 rows of performance data |
| [google-search-console-mcp](https://github.com/surendranb/google-search-console-mcp) | 26 | :green_circle: Active | GSC for Claude, Cursor, Windsurf |
| [awesome-gsc-mcp](https://github.com/Magdoub/awesome-gsc-mcp) | 11 | :green_circle: Active | GSC with 27 tools, analysis engine, caching, rate limiting |
| [gsc-mcp-server](https://github.com/serpfire/gsc-mcp-server) | 8 | :green_circle: Active | 28 tools incl. keyword cannibalization detection, traffic drop diagnostics |

### :bar_chart: Analytics

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [google-analytics-mcp](https://github.com/googleanalytics/google-analytics-mcp) | 1,529+ | :green_circle: Active | **Official** GA4 MCP with schema discovery |
| [google-ads-mcp](https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server) | - | :green_circle: Active | **Official** Google Ads read-only campaign analysis |

### :key: Keyword Research

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [mcp-keywords-everywhere](https://github.com/hithereiamaliff/mcp-keywords-everywhere) | 5 | :green_circle: Active | Keywords Everywhere API integration |
| [kwrds-ai-mcp](https://github.com/mkotsollaris/kwrds-ai-mcp) | 5 | :green_circle: Active | kwrds.ai keyword research API |
| [keywordinsights-mcp](https://github.com/Amaculus/keywordinsights-mcp) | 3 | :green_circle: Active | Keyword Insights API for Claude Code |

### :link: Backlink Analysis

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [seo-mcp](https://github.com/cnych/seo-mcp) | 226 | :green_circle: Active | Free Ahrefs data (backlinks, keywords, traffic) |
| [seo-research-mcp](https://github.com/egebese/seo-research-mcp) | 151 | :green_circle: Active | Ahrefs data with multi-IDE support |
| [ahrefs-mcp-server](https://github.com/ahrefs/ahrefs-mcp-server) | 94 | :yellow_circle: Archived | **Official** Ahrefs MCP (deprecated Feb 2026, use remote server) |
| [seo-insights-mcp-server](https://github.com/mrgoonie/seo-insights-mcp-server) | 29 | :green_circle: Active | Backlinks, keyword ideas, keyword difficulty |
| [moz-mcp](https://github.com/metehan777/moz-mcp) | 9 | :green_circle: Active | Moz SEO API — Domain Authority, Page Authority, backlinks |
| [majestic-mcp](https://github.com/MattiooFR/majestic-mcp) | 0 | :green_circle: Active | Majestic — Trust Flow, Citation Flow, backlinks |

### :chart_with_upwards_trend: Rank Tracking

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [seomonitor-mcp-server](https://github.com/BuntStudio/seomonitor-mcp-server) | 0 | :green_circle: Active | SEOmonitor API integration |

### :wrench: Technical SEO & Auditing

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [seo-crawler-mcp](https://github.com/houtini-ai/seo-crawler-mcp) | 10 | :green_circle: Active | Crawl and analyze websites, 25+ SQL queries, SQLite storage |
| [screaming-frog-mcp](https://github.com/bzsasson/screaming-frog-mcp) | 8 | :green_circle: Active | 8 tools for headless crawls, CSV exports (requires SF license) |
| [seo-inspector-mcp](https://github.com/mgsrevolver/seo-inspector-mcp) | 6 | :green_circle: Active | Scan HTML for SEO issues in Cursor/Claude |
| [web-meta-scraper](https://github.com/cmg8431/web-meta-scraper) | 7 | :green_circle: Active | OG, JSON-LD, media extraction with SEO validation |
| [bing-webmaster-mcp](https://github.com/isiahw1/mcp-server-bing-webmaster) | 11 | :green_circle: Active | Bing Webmaster Tools API |

### :pencil: Content Optimization

> [!IMPORTANT]
> **Gap Alert:** No MCP server currently provides Surfer SEO / Clearscope-style content optimization. This is the biggest missing category in the ecosystem.

### :round_pushpin: Local SEO

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [local-falcon-mcp](https://github.com/local-falcon/mcp) | 15 | :green_circle: Active | **Official** — 37 tools for geo-grid rank tracking, GBP monitoring, competitor analysis |

### :earth_americas: SERP & Search

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [serpapi-mcp](https://github.com/serpapi/serpapi-mcp) | 122 | :green_circle: Active | **Official** SerpAPI — Google and other search engine SERP results |
| [mcp-server-serper](https://github.com/marcopesani/mcp-server-serper) | 147 | :green_circle: Active | Serper API — Google search + web scraping |

### :zap: PageSpeed & Core Web Vitals

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [lighthouse-mcp-server](https://github.com/danielsogl/lighthouse-mcp-server) | 49 | :green_circle: Active | 13+ tools — performance, accessibility, SEO audit, Core Web Vitals |
| [pagespeed-mcp-server](https://github.com/PhialsBasement/Pagespeed-MCP-Server) | 13 | :green_circle: Active | Google PageSpeed Insights data via MCP |

### :label: Schema & Structured Data

> [!IMPORTANT]
> **Gap Alert:** No dedicated schema markup generation or validation MCP server exists. Structured data capabilities are only embedded within broader skills.

### :moneybag: Advertising

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) | - | :green_circle: Active | Facebook/Meta Ads campaign management and optimization |
| [meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) | - | :green_circle: Active | Meta Ads API integration |

### :package: Multi-Platform SEO Suites

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [dataforseo-mcp-server](https://github.com/Skobyn/dataforseo-mcp-server) | 71 | :green_circle: Active | Comprehensive — 12 API categories: SERP, keywords, backlinks, on-page, content, AI optimization |
| [semrush-mcp](https://github.com/mrkooblu/semrush-mcp) | 29 | :green_circle: Active | **77 tools** — domain analytics, backlinks, keyword research, traffic, site audit |
| [semrush-mcp (metehan777)](https://github.com/metehan777/semrush-mcp) | 12 | :green_circle: Active | Alternative Semrush integration |
| [seo-data-api-mcp-server](https://github.com/seranking/seo-data-api-mcp-server) | 8 | :green_circle: Active | **Official** SE Ranking — 60+ data tools, 50+ project tools, AI search visibility |
| [SEO-API-MCP](https://github.com/SEO-Review-Tools/SEO-API-MCP) | 3 | :green_circle: Active | SEO Review Tools — traffic analysis, authority scoring, backlink discovery |
| [seo-mcp-tools](https://github.com/dalebertrand/seo-mcp-tools) | 4 | :green_circle: Active | Generic SEO tools via MCP |

### :robot: AI Search & Visibility

> [!IMPORTANT]
> **Gap Alert:** No MCP server tracks brand visibility across ChatGPT, Perplexity, Claude, and Gemini. This is a rapidly growing need.

### :toolbox: Other SEO Tools

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [etsy-seo-mcp](https://github.com/semihbugrasezer/etsy-seo-mcp) | 6 | :green_circle: Active | Etsy product listing SEO — titles, descriptions, tags |
| [seontology-mcp-server](https://github.com/Instilla-AI/seontology-mcp-server) | 0 | :green_circle: Active | Semantic SEO via SEOntology |
| [LLMTEXT-mcp](https://github.com/janwilmake/LLMTEXT-mcp) | 48 | :green_circle: Active | llms.txt to MCP converter |

### :cloud: Commercial/Hosted MCP Servers (Not Open Source)

<details>
<summary>Click to expand — listed on PulseMCP but not open-source</summary>

| Name | Description |
|------|-------------|
| SEO LinkMap | SERP correlation, PageRank calculations |
| TransformSEO | Keyword research, competitor analysis, backlink monitoring |
| Citedy SEO Agent | Content marketing automation |
| Stobo SEO Audit | AI-powered SEO + AEO auditing |
| OctoBoost SEO | SEO + accessibility + performance + AI visibility |
| SERP AI Overview | Google AI Overview + PAA extraction |
| Keys.so SEO | 150+ API endpoints for keyword research |
| SiteRooster MCP | SEO monitoring, AI visibility tracking |
| EzBiz SEO & Marketing | Keyword research, SERP, backlinks, content optimization |
| SEO Checker (Hostinger) | Multi-dimension SEO analysis |
| Coupler.io MCP | 70+ data source connections including GA, Google Ads, HubSpot |
| Nightwatch SEO Agent | SEO monitoring and analysis |

</details>

---

## :brain: Agent Skills (SKILL.md)

Agent Skills use the [Open Agent Skills specification](https://agentskills.io/specification) and work across **30+ AI tools** including Claude Code, OpenAI Codex CLI, Cursor, GitHub Copilot, Google Antigravity, Windsurf, JetBrains Junie, and more.

### :trophy: Comprehensive SEO Suites

| Name | Stars | Installs | Description |
|------|-------|----------|-------------|
| [marketingskills](https://github.com/coreyhaines31/marketingskills) | 14,967 | 48K+ | 35 marketing skills incl. 6 SEO: seo-audit, ai-seo, programmatic-seo, site-architecture, schema-markup |
| [geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude) | 3,363 | - | GEO-first — 5 subagents, citability scoring, AI crawler analysis (14+ bots), llms.txt generation |
| [seomachine](https://github.com/TheCraigHewitt/seomachine) | 2,818 | - | Long-form content workspace — 10 agents, 26 commands, GA4/GSC/DataForSEO integration |
| [claude-seo](https://github.com/AgriciDaniel/claude-seo) | 2,662 | - | Universal SEO skill v1.5 — 12 sub-skills, 7 subagents, E-E-A-T, Core Web Vitals, GEO/AEO |
| [seo-geo-claude-skills](https://github.com/aaron-he-zhu/seo-geo-claude-skills) | 454 | 11K+ | 20 skills across Research/Build/Optimize/Monitor phases, cross-platform |
| [openclaudia-skills](https://github.com/OpenClaudia/openclaudia-skills) | 260 | - | 56 marketing skills incl. 6 SEO, SemRush/Ahrefs/DataForSEO integration |
| [marketing-skills](https://github.com/kostja94/marketing-skills) | 219 | - | 160+ markdown skills with deep SEO coverage |
| [Agentic-SEO-Skill](https://github.com/Bhanunamikaze/Agentic-SEO-Skill) | 191 | - | 16 sub-skills, 10 agents, supports Antigravity + Claude Code + Codex |
| [ai-workflow](https://github.com/nicepkg/ai-workflow) | 139 | - | 170+ skills total, Content Creator workflow has 32 SEO skills |

### :satellite: GEO & AEO Skills

| Name | Stars | Description |
|------|-------|-------------|
| [claude-skill-seo-geo-optimizer](https://github.com/199-biotechnologies/claude-skill-seo-geo-optimizer) | 20 | SEO/GEO/AEO optimizer with entity extraction and multi-format reports |
| [claude-code-seo-skill](https://github.com/factive1/claude-code-seo-skill) | 7 | SEO + GEO content strategy guide |

### :dart: Specialized SEO Skills

| Name | Stars | Description |
|------|-------|-------------|
| [fireauto](https://github.com/imgompanda/fireauto) | 106 | Korean — 15+ commands across 7 SEO domains |
| [claude-code-seo](https://github.com/huifer/claude-code-seo) | 100 | Next.js-specific — 27+ commands, 100-point scoring, bilingual |
| [tech-seo-audit-skill](https://github.com/Suganthan-Mohanadasan/tech-seo-audit-skill) | 40 | 10-category audit, imports Screaming Frog/Sitebulb/Ahrefs CSV |
| [claude-seo-skill](https://github.com/mangollc/claude-seo-skill) | 19 | Agency-focused — AEO discovery, brand SERP monitoring, multi-client |
| [30x-seo](https://github.com/norahe0304-art/30x-seo) | 14 | 24 skills + Squirrelscan CLI with 230+ rules |
| [seo-claude-code-skills](https://github.com/ccforseo/seo-claude-code-skills) | 2 | Technical audits, keyword clustering, AI visibility |

### :gear: OpenClaw SEO Skills

| Name | Stars | Description |
|------|-------|-------------|
| [google-yandex-seo-skill](https://github.com/Horosheff/google-yandex-seo-skill) | 12 | Dual-engine SEO audit (Google + Yandex) with GEO layer |
| [openclaw-seo-aeo-skills](https://github.com/jrr996shujin-png/openclaw-seo-aeo-skills) | 3 | Website diagnostics, keyword tracking, monthly reports |

---

## :hammer_and_wrench: Standalone Open Source SEO Tools

| Name | Stars | Status | Description |
|------|-------|--------|-------------|
| [robotstxt-ai](https://github.com/sharozdawa/robotstxt-ai) | New | :green_circle: Active | Visual robots.txt manager for AI crawlers — toggle GPTBot, ClaudeBot, PerplexityBot, 20+ bots |
| [indexnow-mcp](https://github.com/sharozdawa/indexnow-mcp) | New | :green_circle: Active | Instant URL indexing via IndexNow (Bing, Yandex, Naver, Seznam) and Google Indexing API |
| [schema-gen](https://github.com/sharozdawa/schema-gen) | New | :green_circle: Active | Schema.org JSON-LD markup generator — 12 types with live preview, web app + MCP server |
| [serpbear](https://github.com/towfiqi/serpbear) | 1,900+ | :green_circle: Active | Self-hosted rank tracker — unlimited keywords, GSC integration |
| [SiteOne Crawler](https://github.com/janreges/siteone-crawler) | 699 | :green_circle: Active | Cross-platform crawler in Rust, CI/CD integration |
| [seonaut](https://github.com/StJudeWasHere/seonaut) | 661 | :green_circle: Active | Go-based SEO auditing tool with interactive dashboard |
| [LibreCrawl](https://github.com/PhialsBasement/LibreCrawl) | 496 | :green_circle: Active | JS rendering crawler with plugin architecture |
| [ContentSwift](https://github.com/hilmanski/contentswift) | 153 | :red_circle: Dead | Surfer SEO alternative — abandoned Oct 2023 |
| [getCito](https://github.com/ai-search-guru/getcito-worlds-first-open-source-aio-aeo-or-geo-tool) | 65 | :yellow_circle: Semi-alive | AIO/AEO/GEO tracker for ChatGPT, Perplexity, Gemini |
| [AiCMO](https://github.com/AICMO/ai-cmo) | 18 | :green_circle: Active | AI brand visibility monitoring |

---

## :warning: Notable Gaps in the Ecosystem

These are categories with **no viable open source solution** — massive opportunities for builders:

| Category | What's Missing | Incumbent Price |
|----------|---------------|-----------------|
| **Content Optimization** | No open source Surfer SEO / Clearscope | $89-170/mo |
| **AI Visibility Tracking** | No comprehensive GEO/AEO tracking platform | $100-500/mo |
| **SEO A/B Testing** | No open source SearchPilot alternative | $2,000+/mo |
| **IndexNow / Indexing API** | [indexnow-mcp](https://github.com/sharozdawa/indexnow-mcp) now fills this gap! | Free & Open Source |
| **Keyword Cannibalization** | No standalone detection tool | Part of $99+/mo suites |
| **Log File Analysis** | No usable SEO-focused log analyzer | $99/yr |
| **Internal Linking** | No platform-agnostic link analysis tool | $69+/mo |
| **Schema Generation MCP** | [schema-gen](https://github.com/sharozdawa/schema-gen) now fills this gap! | Free & Open Source |
| **robots.txt AI Manager** | [robotstxt-ai](https://github.com/sharozdawa/robotstxt-ai) now fills this gap! | Free & Open Source |

---

## :books: Resources

### Directories & Registries

| Directory | Size | Description |
|-----------|------|-------------|
| [Official MCP Registry](https://registry.modelcontextprotocol.io/) | 518+ servers | The official MCP server registry |
| [PulseMCP](https://www.pulsemcp.com/) | 11,880+ servers | Largest MCP directory |
| [FastMCP](https://fastmcp.me/) | 1,864+ servers | Curated, quality-focused |
| [skills.sh](https://skills.sh/) | 89,000+ skills | Agent skills directory by Vercel |
| [SkillsMP](https://skillsmp.com/) | 351,000+ skills | Largest skills aggregator |
| [SkillHub](https://www.skillhub.club/) | 7,000+ skills | AI-evaluated skills |

### Learn More

- [MCP Specification](https://modelcontextprotocol.io/) — Protocol documentation
- [Agent Skills Specification](https://agentskills.io/specification) — SKILL.md format
- [How to Build an MCP Server](https://modelcontextprotocol.io/quickstart) — Getting started guide
- [How to Build a Claude Code Skill](https://code.claude.com/docs/en/skills) — Skills documentation
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) — General MCP server list
- [SEO MCP Guide (SEOptimer)](https://www.seoptimer.com/blog/seo-mcp/) — Overview of SEO MCP servers
- [SEO MCP Guide (Coupler.io)](https://blog.coupler.io/seo-mcp/) — MCP servers for SEO workflows

---

## :handshake: Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

If you know of an SEO MCP server, agent skill, or open source tool not listed here, please open a PR or issue.

---

<div align="center">

### Maintained by

**[Sharoz Dawa](https://sharozdawa.com)** — SEO Professional & Digital Marketing Expert

[![GitHub](https://img.shields.io/badge/GitHub-@sharozdawa-181717?style=flat-square&logo=github)](https://github.com/sharozdawa)
[![Website](https://img.shields.io/badge/Website-sharozdawa.com-0f3460?style=flat-square&logo=google-chrome&logoColor=white)](https://sharozdawa.com)

<br />

If you find this list useful, please give it a :star: — it helps others discover it!

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=100&section=footer" width="100%" />

</div>
