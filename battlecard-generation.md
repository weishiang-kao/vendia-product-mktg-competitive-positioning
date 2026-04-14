# Prompt: Battlecard Generation

## Purpose
Generate a sales battlecard for a competitor using the structured research brief
from `competitive-research.md` as input.

---

## Prompt

```
You are a product marketing manager at Vendia, a managed MCP Gateway for
enterprise data access. Using the competitive brief below, write a sales
battlecard for [COMPETITOR].

[PASTE COMPETITIVE BRIEF HERE]

**Vendia context:**
- Vendia is a managed MCP Gateway — you connect data sources (APIs, databases,
  S3), Vendia exposes them as MCP tools with auth, rate limiting, audit logging,
  and uptime handled
- Core differentiators: managed infrastructure (no self-hosting), multi-party
  data sharing, enterprise governance (audit logs, PII masking, access controls),
  connect existing data without writing server code
- ICP: Platform/infrastructure engineers and AI teams at enterprise companies
  who need governed data access for AI agents

**Write the battlecard with these sections:**

1. **What [COMPETITOR] is** — 2–3 sentences, accurate and fair
2. **When you'll see them in a deal** — what signals indicate this competitor
   is in consideration
3. **The core reframe** — one paragraph repositioning the comparison on our terms
4. **Objection handling** — 3 most common objections with responses (Q&A format)
5. **Feature comparison table** — honest, verifiable claims only. Mark anything
   uncertain as "⚠️ Verify current docs"
6. **Who wins with [COMPETITOR]** — be honest about where they're the better fit
7. **Who wins with Vendia** — where we're clearly stronger

**Tone and accuracy requirements:**
- Do not overstate Vendia's capabilities or understate the competitor's
- Do not include any claim about the competitor that isn't verifiable from
  their public documentation
- Mark any uncertain claims with "⚠️ Verify before using"
- The battlecard will be used by sales — inaccurate claims will damage credibility
  with technical buyers who will fact-check
```

---

## Usage Notes

- Always run `competitive-research.md` first to generate the brief
- Have a human review the output against live competitor docs before distributing
- Refresh when competitors ship major updates or change pricing
