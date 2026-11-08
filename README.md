<div align="center">

# Muhammad Hamid

**Digital Marketing Head · MarTech Engineer**

I build open-source tooling for technical SEO, paid media forensics, and server-side analytics —
and I send the same class of fixes back upstream to the projects my stack actually runs on.

[![Portfolio](https://img.shields.io/badge/Portfolio-abouthamid.web.app-0b7285?style=for-the-badge&logo=googlechrome&logoColor=white)](https://abouthamid.web.app/)
[![Resume](https://img.shields.io/badge/Resume-Interactive-2ea44f?style=for-the-badge&logo=readdotcv&logoColor=white)](https://hamid-resume.web.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077b5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-hamid-digital-marketing/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Direct-25d366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/923167417135)

![Merged PRs](https://img.shields.io/badge/merged%20PRs-30-2ea44f?style=flat-square)
![Open PRs](https://img.shields.io/badge/open%20PRs-79-0969da?style=flat-square)
![Projects](https://img.shields.io/badge/upstream%20projects-19-6f42c1?style=flat-square)
![Public repos](https://img.shields.io/badge/public%20repos-76-6e7781?style=flat-square)

</div>

---

## Upstream contributions

**30 merged pull requests across 15 projects**, with 79 more open. Every fix ships with a regression test that reproduces the defect before it is patched — no drive-by formatting PRs.

| Project | Merged | What the fixes covered |
|---|:---:|---|
| [vibgrate/cli](https://github.com/vibgrate/cli) | 7 | Vulnerability-scan reporting, lockfile edge cases (pnpm catalogs/engines), CLI snapshot tests |
| [simple-invoicing](https://github.com/nikhilb2/simple-invoicing-free-gst-billing-software) | 5 | Invoice / credit-note date-window correctness, GST totals, timezone-safe filters |
| [selimfirat/pysad](https://github.com/selimfirat/pysad) | 3 | Anomaly-detection edge cases, input validation, API robustness |
| [lukeautry/tsoa](https://github.com/lukeautry/tsoa) | 2 | Type-safe routing, bundled route-template resolution, metadata deduplication |
| [doobidoo/mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) | 2 | MCP tool annotations, hermetic test isolation |
| [rdlugs/sentryward](https://github.com/rdlugs/sentryward) | 2 | SSRF range blocking (NAT64 / 6to4), login-timing account enumeration |
| [anveshachuri/recarena](https://github.com/anveshachuri/recarena) | 1 | Batch simulator state handling |
| [cfgaudit/cfgaudit](https://github.com/cfgaudit/cfgaudit) | 1 | Config audit correctness |
| [exmergo/dex](https://github.com/exmergo/dex) | 1 | Security hardening |
| [kondratevdev/imgproxykit](https://github.com/kondratevdev/imgproxykit) | 1 | Image proxy edge cases |
| [mikesilvers/rag-docker](https://github.com/mikesilvers/rag-docker) | 1 | Offline model loading / pre-cached embeddings |
| [OpenWave-India/modeldiff](https://github.com/OpenWave-India/modeldiff) | 1 | Model diff correctness |
| [Opencomplai/opencomplai](https://github.com/Opencomplai/opencomplai) | 1 | CI reliability, container health |
| [supabase/supabase-py](https://github.com/supabase/supabase-py) | 1 | PostgREST filter serialization (`null` / booleans in `in_()`) |
| [aws-samples/genai-db-modernizer](https://github.com/aws-samples/sample-aws-genai-db-modernizer) | 1 | Dependency alignment |

**Most recent merges**

| Merged | Project | Change |
|---|---|---|
| 2026-11-06 | [rdlugs/sentryward#226](https://github.com/rdlugs/sentryward/pull/226) | `fix(security)` — prevent account enumeration via login timing |
| 2026-11-04 | [mikesilvers/rag-docker#620](https://github.com/mikesilvers/rag-docker/pull/620) | `fix(api)` — load pre-cached sentence-transformers model offline |
| 2026-11-04 | [doobidoo/mcp-memory-service#1853](https://github.com/doobidoo/mcp-memory-service/pull/1853) | `fix(registry)` — mark `memory_graph` read-write in tool annotations |
| 2026-11-03 | [lukeautry/tsoa#1927](https://github.com/lukeautry/tsoa/pull/1927) | `refactor(metadata)` — deduplicate binary body parameter checks |
| 2026-11-03 | [vibgrate/cli#539](https://github.com/vibgrate/cli/pull/539) | `test(lockfile)` — pnpm catalog / engines edge-case fixture |
| 2026-11-02 | [supabase/supabase-py#1863](https://github.com/supabase/supabase-py/pull/1863) | `fix(postgrest)` — serialize null and booleans in `in_()` |

**In review now (79 open)** — the largest single block is a locale-correctness sweep in [iamkun/dayjs](https://github.com/iamkun/dayjs) (**53 locales** where `yearStart` disagreed with CLDR `firstDay`/week rules), followed by work in `iamvisheshsrivastava/*` (Smart_CSV_Toolkit, AirKube, geniebot, ab-lab), `Opencomplai/opencomplai`, `Dpro-at/Tel-Agent`, `finos/open-resource-broker`, `OpnForm/OpnForm`, `adbar/trafilatura`, `wandb/rai-toolkit`, `date-fns/date-fns`, `google/sbsim` and `datamodel-code-generator`.

→ [See all pull requests](https://github.com/hamid-digitalmarketer?tab=pull-requests)

---

## Featured projects

**Commerce & storefront operations**

| Project | What it does | Stack |
|---|---|---|
| [**shopify-growth-mcp**](https://github.com/hamid-digitalmarketer/shopify-growth-mcp) | Production MCP server exposing 61 tools for Shopify ops: SEO audits, GEO readiness, feed quality, inventory intelligence | TypeScript · MCP |
| [**restock-radar**](https://github.com/hamid-digitalmarketer/restock-radar) | Shopify app for back-in-stock alerts and preorder recovery | JavaScript · Shopify |
| [**ecommerce-seo-optimizer**](https://github.com/hamid-digitalmarketer/ecommerce-seo-optimizer) | Audits and fixes product listings at catalogue scale — titles, descriptions, structured data | Python |

**Attribution, tracking & paid media**

| Project | What it does | Stack |
|---|---|---|
| [**conversionbridge**](https://github.com/hamid-digitalmarketer/conversionbridge) | Privacy-first server-side conversion gateway for Meta CAPI and GA4, with fail-closed consent and atomic deduplication | Python · FastAPI · Firebase |
| [**whatsapp-attribution-router**](https://github.com/hamid-digitalmarketer/whatsapp-attribution-router) | UTM-preserving WhatsApp click-to-chat attribution, 48h deduplication, Sheets and GoHighLevel sync | JavaScript · Python |
| [**conversion-tracking-doctor**](https://github.com/hamid-digitalmarketer/conversion-tracking-doctor) | Diagnostic suite for GA4, Google Ads, Meta Pixel and server-side tracking breakage | Python |
| [**ppc-waste-detector**](https://github.com/hamid-digitalmarketer/ppc-waste-detector) | Finds search-query bleed, cannibalisation, PMax junk traffic and zero-conversion spend | Python · SQLite |
| [**meta-lead-quality-analyzer**](https://github.com/hamid-digitalmarketer/meta-lead-quality-analyzer) | Lead-quality scoring and CRM revenue feedback loop for Meta Ads — bot and disposable-email detection | Python |
| [**ai-marketing-mix-copilot**](https://github.com/hamid-digitalmarketer/ai-marketing-mix-copilot) | Bayesian Marketing Mix Modeling and incrementality testing for budget decisions | Python |

**SEO, GEO & search visibility**

| Project | What it does | Stack |
|---|---|---|
| [**searchpulse-ai**](https://github.com/hamid-digitalmarketer/searchpulse-ai) | Search Console intelligence: CTR models, striking-distance opportunities, traffic-drop diagnostics | FastAPI · Python |
| [**seo-doctor**](https://github.com/hamid-digitalmarketer/seo-doctor) | Technical SEO crawler: broken links, canonical loops, redirect chains, crawl-over-crawl comparison | Python CLI |
| [**ai-search-visibility-auditor**](https://github.com/hamid-digitalmarketer/ai-search-visibility-auditor) | GEO auditing: AI-crawler access, `llms.txt` validation, AI-citation readiness scoring | Python · Streamlit |
| [**geo-visibility-lab**](https://github.com/hamid-digitalmarketer/geo-visibility-lab) | Local SEO and Google Business Profile proximity-grid rank tracking | Python · GeoJSON |
| [**dynamic-schema-generator**](https://github.com/hamid-digitalmarketer/dynamic-schema-generator) | WordPress JSON-LD `@graph` engine with Elementor extraction, NAP management and validation | PHP |
| [**seo-audit-tool**](https://github.com/hamid-digitalmarketer/seo-audit-tool) | Ethical on-page audit crawler — titles, meta, headings, canonicals, image SEO | Python |

**Platform & engineering**

| Project | What it does | Stack |
|---|---|---|
| [**ai-marketing-growth-os**](https://github.com/hamid-digitalmarketer/ai-marketing-growth-os) | Agentic marketing intelligence platform with human-in-the-loop governance | Python |
| [**ai-marketing-shared**](https://github.com/hamid-digitalmarketer/ai-marketing-shared) | Shared package: Pydantic schemas, eval harness, tracing, cost controls | Python |
| [**envscope**](https://github.com/hamid-digitalmarketer/envscope) | Audits `.env` against `.env.example` and a JSON schema without ever printing secrets | Python CLI · DevSecOps |
| [**pinvault-pinterest-downloader**](https://github.com/hamid-digitalmarketer/pinvault-pinterest-downloader) | Privacy-first Manifest V3 Chrome extension for Pinterest media | JavaScript |

**Security & AppSec work lives on a separate account:** [@mhamidlad](https://github.com/mhamidlad) — vulnerability remediation, DevSecOps and AI code security projects.

---

## Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![GA4](https://img.shields.io/badge/GA4-E37400?style=flat-square&logo=googleanalytics&logoColor=white)
![GTM](https://img.shields.io/badge/Server--Side%20GTM-246FDB?style=flat-square&logo=googletagmanager&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-000000?style=flat-square&logo=anthropic&logoColor=white)

**Analytics & tracking** — GA4, server-side GTM, Meta Conversions API, enhanced conversions, event deduplication, BigQuery
**Performance media** — Google Ads (Search, Shopping, PMax), Meta Ads, TikTok Ads, negative-keyword and waste audits
**SEO engineering** — technical SEO, Schema.org JSON-LD, GEO / `llms.txt`, local SEO, Core Web Vitals, crawl architecture
**Engineering** — Python, TypeScript, FastAPI, Node.js, PHP, SQL, MCP servers, pytest / Vitest / Jest

---

## Selected results

| Engagement | Outcome |
|---|---|
| MHW Clothing | Organic traffic +40%, conversion rate +75%, CAC −70% |
| Healthrix BPO | Scaled acquisition to 200+ employees; won US healthcare and tech contracts |
| Riceland Healthcare System | Multi-location patient-acquisition funnels and search visibility |
| Latest Bedding (UK) | Built and led the cross-functional e-commerce marketing team |

---

## Work with me

- **Ad-spend forensics** — reclaim 15–35% of wasted spend without losing conversions
- **Tracking architecture** — GA4 + sGTM + Meta CAPI deployments with validated enhanced conversions
- **Lead quality** — disposable-email / bot filtering and CRM offline conversion sync to lower CPQL
- **Local SEO** — 5×5 proximity-grid tracking, GBP and citation cleanup
- **Fractional Head of Digital Marketing** — full-funnel strategy, team leadership, budget ownership

📬 [WhatsApp +92 316 7417135](https://wa.me/923167417135) · [abouthamid.web.app](https://abouthamid.web.app/) · [LinkedIn](https://www.linkedin.com/in/muhammad-hamid-digital-marketing/)

<sub>Lahore, Pakistan · Open to consulting and full-time leadership roles · Contributions verified from the GitHub API on 2026-11-07</sub>
