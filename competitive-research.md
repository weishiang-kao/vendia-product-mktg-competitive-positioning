# Prompt: Competitive Research

## Purpose
Research a competitor's current positioning, product capabilities, pricing,
and messaging before drafting battlecards, landing pages, or blog content.
Designed to be rerun as competitors update their positioning.

## Tools Used
- Claude web search (for current docs, pricing pages, blog posts)
- Manual verification against live competitor documentation

---

## Prompt

```
You are a product marketing analyst at Vendia, a managed MCP Gateway company.
Research [COMPETITOR] thoroughly using web search and return a structured
competitive brief.

**Search targets (in order):**
1. [COMPETITOR] official website and product pages
2. [COMPETITOR] documentation (especially MCP-related features)
3. [COMPETITOR] pricing page
4. [COMPETITOR] GitHub (if open source — check README, recent commits, star count)
5. Recent blog posts or changelog entries from [COMPETITOR] (last 6 months)
6. Any third-party comparisons or reviews mentioning [COMPETITOR] and MCP

**Return the following structured brief:**

---

## [COMPETITOR] Competitive Brief

### What they are
1–2 sentence description of what [COMPETITOR] is and who it's built for.
Be precise — don't conflate their primary product with secondary features.

### Primary product / core use case
What does [COMPETITOR] primarily sell? What problem does it solve?
This may be different from their MCP capability.

### MCP capability
- Does [COMPETITOR] offer MCP server hosting or gateway functionality?
- What exactly does their MCP offering include?
- Is it a core product or a feature within a larger platform?
- Source: [URL where you found this]

### Pricing
- What is their pricing model? (open source / freemium / usage-based / seat-based)
- Any public pricing tiers?
- Source: [URL]

### Target audience
Who is [COMPETITOR] built for? (job titles, company size, use case)

### Key messaging / positioning
What are their top 3 positioning claims? Quote directly from their website
where possible, with URLs.

### Differentiators they claim
What do they say makes them different? List their stated differentiators.

### Weaknesses / gaps (vs. Vendia)
Based on your research, where does [COMPETITOR] appear weaker than Vendia?
Only include gaps that are verifiable from their public documentation —
do not speculate or overstate.

### Things to verify manually
List any claims that should be manually verified against live docs before
using in published content.

### Sources
List all URLs consulted with date accessed.
```

---

## Usage Notes

- Replace `[COMPETITOR]` with the competitor name before running
- Always manually verify capability claims against live documentation before
  using in published content — especially feature comparison tables
- If a capability is unclear from public docs, mark it as "⚠️ Verify" rather
  than assuming it's absent
- Rerun this prompt quarterly or whenever you see significant competitor updates

## Competitors Researched

| Competitor | Last Run | Notes |
|---|---|---|
| FastMCP | April 2026 | Open source Python framework; no managed hosting |
| TrueFoundry | April 2026 | MLOps platform; MCP via AI Gateway feature |
