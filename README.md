# FireJW

**Local-first AI workflow systems, research automation, and public-safe product engineering.**

I turn real operating workflows into small, auditable tools with reproducible demos, validation gates, and explicit privacy boundaries.

`Python` · `JavaScript / TypeScript` · `Node.js` · `SQLite` · `Deno` · `Chrome DevTools Protocol`

## Featured Work

| Project | Engineering signal | Review |
| --- | --- | --- |
| [stock-analysis-plus](https://github.com/FireJW/stock-analysis-plus) | Evidence-grounded market research with shortlists, macro overlays, data adapters, and validation bundles. | [Live demo](https://firejw.github.io/stock-analysis-plus/) · [Runbook](https://github.com/FireJW/stock-analysis-plus/blob/main/docs/demo-run.md) |
| [deckgen-local](https://github.com/FireJW/deckgen-local) | Contract-first artifact generation from Markdown and source packages to HTML previews and optional PPTX. | [Live demo](https://firejw.github.io/deckgen-local/) · [Runbook](https://github.com/FireJW/deckgen-local/blob/master/docs/demo-run.md) |
| [consulting-crm-lite](https://github.com/FireJW/consulting-crm-lite) | Local-first consulting operations with anonymized records, delivery tracking, and approval-gated case studies. | [Live demo](https://firejw.github.io/consulting-crm-lite/) · [Transcript](https://github.com/FireJW/consulting-crm-lite/blob/main/docs/demo-transcript.md) |
| [xhs-readonly-monitor-lite](https://github.com/FireJW/xhs-readonly-monitor-lite) | Read-only CDP monitoring with task-scoped tabs and a hard boundary against account-changing automation. | [Live demo](https://firejw.github.io/xhs-readonly-monitor-lite/) · [Transcript](https://github.com/FireJW/xhs-readonly-monitor-lite/blob/main/docs/demo-transcript.md) |

## Engineering Priorities

- **Local-first by default:** credentials, source data, browser state, and generated working files stay outside public repositories.
- **Evidence before output:** workflows expose source health, validation results, review packets, or reproducible checks.
- **Inspectable artifacts:** Markdown, JSON, HTML, SQLite, and PPTX outputs remain easy to audit and hand off.
- **Human review gates:** publishing, account changes, case-study export, and other consequential actions remain explicit.

## Portfolio Index

### Research And Market Systems

| Project | Focus | Demo |
| --- | --- | --- |
| [stock-analysis-plus](https://github.com/FireJW/stock-analysis-plus) | Public-safe stock analysis workflows for shortlists, macro overlays, evidence bundles, and market-data adapters. | [Pages](https://firejw.github.io/stock-analysis-plus/) |
| [stock-kit](https://github.com/FireJW/stock-kit) | Local-first stock research toolkit with adapters, indicators, validation gates, and reinforcement review. | [Pages](https://firejw.github.io/stock-kit/) |
| [market-alert-cloud](https://github.com/FireJW/market-alert-cloud) | Deno market-event alert service with RSS monitoring, keyword matching, KV deduplication, and Telegram delivery. | [Pages](https://firejw.github.io/market-alert-cloud/) |

### Knowledge And Artifact Workflows

| Project | Focus | Demo |
| --- | --- | --- |
| [deckgen-local](https://github.com/FireJW/deckgen-local) | Contract-first local deck generation with traceable run bundles and quality gates. | [Pages](https://firejw.github.io/deckgen-local/) |
| [research-to-deck](https://github.com/FireJW/research-to-deck) | Public-safe research-to-deck workflow with source grounding, HTML preview, and QC reports. | [Pages](https://firejw.github.io/research-to-deck/) |
| [obsidian-kb-workflow-lite](https://github.com/FireJW/obsidian-kb-workflow-lite) | Preview-first primitives for Markdown knowledge bases, frontmatter, wikilinks, search, and manifests. | [Pages](https://firejw.github.io/obsidian-kb-workflow-lite/) |

### Product And Automation Tools

| Project | Focus | Demo |
| --- | --- | --- |
| [consulting-crm-lite](https://github.com/FireJW/consulting-crm-lite) | Local-first consulting CRM with anonymized leads, delivery packets, and case-study approval gates. | [Pages](https://firejw.github.io/consulting-crm-lite/) |
| [ai-job-radar](https://github.com/FireJW/ai-job-radar) | AI job discovery with source-health checks, structured matching, and human-review application gates. | [Pages](https://firejw.github.io/ai-job-radar/) |
| [xhs-readonly-monitor-lite](https://github.com/FireJW/xhs-readonly-monitor-lite) | Read-only Xiaohongshu feed and note-metric inspection through Chrome DevTools. | [Pages](https://firejw.github.io/xhs-readonly-monitor-lite/) |

### Adapted Public Workflows

These repositories are clearly labeled forks and are included for integration and packaging work rather than as original upstream projects.

| Project | Adaptation | Demo |
| --- | --- | --- |
| [daily_stock_analysis](https://github.com/FireJW/daily_stock_analysis) | Portfolio fork of an AI-assisted A-share workflow with scheduled reports and notification delivery. | [Pages](https://firejw.github.io/daily_stock_analysis/) |
| [ai-daily-digest](https://github.com/FireJW/ai-daily-digest) | Portfolio fork of an AI-scored RSS digest with grouping, trend highlights, and Markdown reports. | [Pages](https://firejw.github.io/ai-daily-digest/) |

## Public Packaging Pattern

1. Extract the smallest reusable workflow boundary.
2. Remove credentials, private source data, browser sessions, local databases, and generated runtime artifacts.
3. Add a focused README, live review surface, safety notes, synthetic fixtures, and reproducible checks.
4. Keep the full operating system private when a clean public extraction is the safer artifact.
