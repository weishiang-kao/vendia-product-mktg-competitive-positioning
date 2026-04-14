# Battlecard: Vendia MCP Gateway vs. FastMCP

> Last verified: April 2026 — check fastmcp.com and docs before using in sales calls.

---

## What FastMCP Is

FastMCP is an open-source Python framework that simplifies building MCP servers.
It provides decorators and abstractions that reduce the boilerplate of implementing
the MCP protocol in Python. It's a developer tool — you write code, you run it,
you operate it.

FastMCP does not provide: hosting, auth, rate limiting, audit logging, governance,
or any managed infrastructure. It is a framework, not a platform.

---

## When You'll See FastMCP in a Deal

- Prospect has a developer who has already prototyped something with FastMCP
- Prospect is evaluating "just building it ourselves" vs. buying
- Prospect found FastMCP via GitHub/docs and is using it as the baseline comparison

---

## The Core Reframe

FastMCP answers the question: **"How do I build an MCP server?"**
Vendia answers the question: **"How do I run MCP servers in production without owning the infrastructure?"**

These aren't competing answers — they're different questions. When a prospect is
comparing them directly, they're usually underestimating the operational cost of
running FastMCP in production.

---

## Objection Handling

**"We can just use FastMCP — it's free and our engineers can build it."**

FastMCP is free to use, but not free to operate. Your engineers will need to build
and maintain: auth/SSO integration, rate limiting, abuse prevention, audit logging,
uptime monitoring, and incident response. That's months of engineering time and
ongoing maintenance — for infrastructure that isn't your core product.

Vendia's managed gateway means you're up in hours, not months, and your engineers
stay focused on what makes your product differentiated.

---

**"FastMCP is open source — we have full control."**

Control over the code is different from control over the outcome. With FastMCP
you control the implementation; you also own every bug, outage, and security
vulnerability. Vendia gives you control over configuration, access policies, and
data — while owning the operational reliability.

---

**"We already have a FastMCP prototype — why would we switch?"**

Prototypes and production have different requirements. A FastMCP prototype is a
great proof of concept. When you're ready to go to production — with real users,
real data, and real compliance requirements — that's when managed infrastructure
pays off. Vendia can sit in front of your existing data sources; you don't
necessarily need to throw away the prototype.

---

## Feature Comparison

| Capability | Vendia MCP Gateway | FastMCP |
|---|---|---|
| MCP protocol support | ✅ | ✅ |
| Managed hosting / uptime | ✅ | ❌ Self-hosted |
| Auth / SSO | ✅ Built-in | ❌ Build yourself |
| Rate limiting | ✅ Built-in | ❌ Build yourself |
| Audit logging | ✅ Built-in | ❌ Build yourself |
| PII masking | ✅ Built-in | ❌ Build yourself |
| Multi-party data sharing | ✅ | ❌ |
| Connect existing APIs/DBs | ✅ Config-based | ⚠️ Requires code |
| Open source | ❌ | ✅ |
| Cost | Paid | Free (infra costs extra) |

---

## Who Wins With FastMCP
Individual developers, hobbyists, and teams building internal prototypes where
operational requirements are minimal. If you have strong Python engineers and
want full control over the implementation, FastMCP is a reasonable choice.

## Who Wins With Vendia
Teams that need MCP servers in production, with real governance and reliability
requirements, who don't want to own the infrastructure.
