# Vendia MCP Gateway — Messaging Framework

## One-liner
Vendia is the managed MCP Gateway for enterprises that need to expose their data
as AI-ready context — with the auth, governance, and reliability that production
AI systems require.

---

## The Problem We Solve

AI agents and LLMs need real-time access to enterprise data. The Model Context
Protocol (MCP) provides the standard — but building and operating MCP servers at
enterprise scale is hard:

- Auth and access control across multiple data sources
- Rate limiting and abuse prevention
- Audit logging for compliance
- Multi-party data sharing without copying data
- Operational reliability and observability

Most teams either build this themselves (expensive, slow) or use open-source
frameworks that stop at the protocol layer and hand the operational burden back
to them.

---

## Ideal Customer Profile

**Primary: Platform / Infrastructure Engineers at enterprise companies**
- Building internal AI tooling or agentic workflows
- Responsible for making company data accessible to LLMs safely
- Care deeply about security, governance, and not building undifferentiated infra

**Secondary: AI/ML teams and data engineers**
- Want to expose existing data sources (databases, APIs, S3) to AI agents
- Don't want to write and maintain MCP server code

**Tertiary: Technical buyers (VP Eng, Head of AI, CTO at mid-market)**
- Evaluating MCP infrastructure options
- Care about compliance, audit trails, and vendor reliability

---

## Messaging Pillars

### 1. Managed, not DIY
Vendia handles the infrastructure — auth, routing, rate limiting, logging,
uptime. You connect your data sources and get a production-ready MCP server.
FastMCP and similar frameworks give you building blocks; Vendia gives you the
finished product.

### 2. Enterprise-grade governance
Every tool call is logged. Access is controlled per data source. PII masking,
read-only enforcement, and audit trails are built in — not bolted on.

### 3. Multi-party data sharing
Vendia's underlying platform is purpose-built for controlled data sharing across
organizational boundaries. This makes it uniquely suited for use cases where
multiple companies or teams need to share data context with AI agents.

### 4. Connect existing data — no server code required
Bring your existing APIs, databases, and S3 buckets. Vendia exposes them as MCP
tools via configuration, not custom server code.

---

## Differentiation by Competitor

### vs. FastMCP
FastMCP is a developer framework — you write Python to build MCP servers.
Vendia is managed infrastructure — you configure it and Vendia runs it.
FastMCP is the right choice for a developer building a personal project.
Vendia is the right choice for a team that needs to run MCP servers in production
without owning the operational burden.

**Key wedge:** "Do you want to build and operate MCP infrastructure, or do you
want to use it?"

### vs. TrueFoundry
TrueFoundry is an MLOps platform that added MCP server hosting as a feature.
Vendia is purpose-built MCP Gateway infrastructure with data sharing at its core.
TrueFoundry is the right choice if you're already using it for ML deployment.
Vendia is the right choice if MCP Gateway is a first-class requirement.

**Key wedge:** "Is MCP infrastructure a feature you need, or a platform you need?"

---

## Proof Points (sanitize before publishing)
- [X] enterprise customers using Vendia MCP Gateway in production
- Supports [N] concurrent tool connections
- [X] ms median latency for tool calls
- SOC 2 compliant
