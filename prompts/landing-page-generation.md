# Prompt: Competitive Landing Page Generation

## Purpose
Generate a competitor comparison landing page using the research brief and
battlecard as inputs. Optimized for both SEO and conversion.

---

## Prompt

```
You are a product marketing manager at Vendia, a managed MCP Gateway for
enterprise data access. Using the competitive brief and battlecard below,
write a comparison landing page for Vendia vs. [COMPETITOR].

[PASTE COMPETITIVE BRIEF]
[PASTE BATTLECARD]

**Page context:**
- URL: /mcp-gateway/vs-[competitor-slug]
- Primary audience: developers and platform engineers evaluating MCP options
- Goal: convert visitors searching for [COMPETITOR] alternatives or comparisons
- Tone: direct, technically credible, fair — not disparaging

**Page structure:**

1. **Hero**
   - H1: Single clear headline that frames the comparison on our terms
   - Subhead: 1–2 sentences expanding on the H1
   - Two CTAs: "Start free trial" and "Talk to an engineer"

2. **What [COMPETITOR] does well** (100–150 words)
   Lead with genuine acknowledgment of their strengths. This builds credibility
   with technical readers who know the tool. Do not be dismissive.

3. **Where the gap is** (150–200 words)
   Describe the specific capability or use case where Vendia is stronger.
   Be concrete — reference actual features, not vague claims.

4. **What Vendia gives you** (150–200 words)
   Describe Vendia's solution. Focus on outcomes, not feature lists.

5. **Comparison table**
   Keep to 8–10 rows. Mark uncertain claims as "⚠️ Verify current docs."
   Do not fabricate capabilities for either side.

6. **When [COMPETITOR] is the right choice** (2–3 sentences)
   Honest. If they're genuinely better for a use case, say so. Technical
   audiences respect intellectual honesty and it improves conversion quality.

7. **CTA section**
   Short closing paragraph + two CTAs.

**Writing requirements:**
- No marketing superlatives ("best," "leading," "revolutionary")
- No unverifiable claims about the competitor
- Sentence case for all headings
- Aim for 700–900 words total
```

---

## Usage Notes

- Run after `competitive-research.md` and `battlecard-generation.md`
- Have engineering or a technical PMM review the comparison table before publishing
- Add target keywords to the SEO meta title and description after generation
- Update when competitor ships major changes — stale comparison pages hurt credibility
