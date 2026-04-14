# Competitive Positioning — Vendia MCP Gateway

## Context

Vendia offers a **managed MCP Gateway** — enterprise infrastructure for exposing
data sources as MCP servers, with built-in auth, governance, rate limiting, and
audit logging. As the MCP ecosystem grew rapidly in 2025–2026, a new category of
competitors emerged targeting the same developer and enterprise buyer audience.

This repo documents the competitive positioning work I led for Vendia's MCP
Gateway: messaging framework, battlecards, landing page copy, and SEO content
targeting competitor keyword clusters.

---

## Competitive Landscape

| Competitor | Positioning | Primary Audience |
|---|---|---|
| FastMCP | Open-source Python framework for building MCP servers quickly | Individual developers |
| TrueFoundry | MLOps/deployment platform adding MCP server hosting | ML/Platform engineers |

Vendia's differentiation centers on **enterprise readiness**: managed infrastructure,
multi-party data sharing, governance controls, and the ability to expose existing
data sources (APIs, databases, S3) as MCP servers without writing server code.

---

## What This Repo Contains

| Folder | Contents |
|---|---|
| `positioning/` | Core messaging framework and battlecards |
| `landing-pages/` | Competitor comparison landing page copy |
| `seo/` | SEO blog content targeting competitor keyword clusters |
| `prompts/` | Claude prompts used to research competitors and draft content |

---

## Workflow

All competitive research and initial drafts were produced using Claude with web
search, then fact-checked against each competitor's live documentation before
publishing. The prompts in `prompts/` are the actual working prompts used —
parameterized so they can be rerun as competitors update their positioning.

```
Competitor docs / website
        ↓
Claude + web search (competitive-research.md prompt)
        ↓
Structured research brief
        ↓
Claude (battlecard / landing-page / blog prompt)
        ↓
Draft → manual fact-check against live docs → publish
```

---

## Key Principle

Every claim about a competitor was verified against their official documentation
or website before publishing. Competitive copy that overstates gaps or makes
unverifiable claims creates legal and credibility risk — especially with a
technical developer audience that will fact-check you.

---

## Files

### Positioning
- [`positioning/messaging-framework.md`](positioning/messaging-framework.md) — ICP, core differentiators, messaging pillars
- [`positioning/battlecard-fastmcp.md`](positioning/battlecard-fastmcp.md) — FastMCP battlecard
- [`positioning/battlecard-truefoundry.md`](positioning/battlecard-truefoundry.md) — TrueFoundry battlecard

### Landing Pages
- [`landing-pages/vs-fastmcp.md`](landing-pages/vs-fastmcp.md) — vs. FastMCP comparison page copy
- [`landing-pages/vs-truefoundry.md`](landing-pages/vs-truefoundry.md) — vs. TrueFoundry comparison page copy

### SEO
- [`seo/blog-vs-fastmcp.md`](seo/blog-vs-fastmcp.md) — SEO blog targeting FastMCP keyword cluster
- [`seo/blog-vs-truefoundry.md`](seo/blog-vs-truefoundry.md) — SEO blog targeting TrueFoundry keyword cluster

### Prompts
- [`prompts/competitive-research.md`](prompts/competitive-research.md) — research prompt
- [`prompts/battlecard-generation.md`](prompts/battlecard-generation.md) — battlecard prompt
- [`prompts/landing-page-generation.md`](prompts/landing-page-generation.md) — landing page prompt
