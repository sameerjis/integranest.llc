# New SKU One-Pagers — IntegraNest LLC

> **DRAFT** — pricing below is placeholder, set in line with existing SKUs. Final numbers TBD.
> Text version of `new-sku-one-pagers.pdf`. Contact for all SKUs: hello@integranest.llc

Positioning line (all three): *Built so that when a new model drops next month, this gets better — not obsolete.* One engineer. FinTech & HealthTech. Fixed scope, fixed price.

---

## 1. Agent-Ready Data Sprint

**The problem.** Every company wants to pipe its internal data into one place and expose it to agents through MCP. Then they look at the data: five versions of the same customer, dead Slack channels, PDFs nobody can search. Agents built on messy data hallucinate, leak, and get switched off.

**Who it's for.** Companies about to deploy agents — or stuck mid-deployment because the data isn't cooperating. Not for companies with no agent plans.

**What you get (3-week fixed sprint):**
- Week 1 — Data estate audit: inventory of sources (CRM, warehouse, docs, tickets, chat), duplicate/conflict mapping, PII and access-risk flags.
- Week 2 — Cleanup: dedupe and normalize core entities (customers, products), canonical schema definition, junk archived or quarantined.
- Week 3 — MCP layer: working MCP servers exposing the clean data with role-based access controls and documented tool contracts agents can call.

**Deliverables:** data quality report, canonical schema doc, working MCP servers in your infra, access-control matrix, agent-readiness scorecard.

**Price:** from $4,800 — 3-week sprint *(draft)*

**Why IntegraNest:** data governance *is* access control — the same muscle as SOC 2 and HIPAA work.

---

## 2. Agent Access Audit

**The problem.** Every agent with access to your systems is a new door into your company — API keys in prompts, write access nobody reviewed, third-party agent tools with unclear data handling. A lot of those doors were left open.

**Who it's for.** Any company running agents with production data access. Ladders directly into SOC 2 — auditors will ask about this.

**What you get (2-week fixed audit):**
- Inventory of every agent/automation and what systems each can touch.
- Effective-permissions vs. needed-permissions mapping (least-privilege gap analysis).
- Review of credential storage, prompt-injection exposure, and third-party tool data flows.
- Prioritized remediation plan.

**Deliverables:** access inventory, gap report with severity ratings, remediation roadmap, re-audit checklist. Report formatted SOC 2-ready.

**Price:** from $3,500 — 2-week audit *(draft)*

**Why IntegraNest:** compliance-trained eyes on a security problem.

---

## 3. Agent Deployment Audit

**The problem.** Once an agent makes an expensive mistake, insurers will want audits before they cover anyone. Companies that get audited early ship cleaner deployments — and will get cheaper coverage later.

**Who it's for.** Companies deploying customer-facing or money-moving agents. Early-mover positioning — almost nobody is selling this yet.

**What you get (2–3 week fixed audit):**
- Deployment review: what the agent does, what it can touch, failure modes.
- Adversarial evals: scripted failure-scenario tests drawn from real deployment failures.
- Human-in-the-loop design review: where humans check output, escalation paths when the agent gets stuck.
- Risk register and controls documentation, formatted for future insurance and board use.

**Deliverables:** risk register, eval results, controls documentation, go/no-go recommendation. Insurer- and board-ready summary.

**Price:** from $3,900 — 2–3 week audit *(draft)*

**Why IntegraNest:** the evals are the moat — written by someone who knows the work, not generated.

---

## How they sequence

Agent-Ready Data Sprint → Agent Access Audit → Agent Deployment Audit → SOC 2 Readiness (auditors ask about AI controls) → AI Integration Pilot (build the harness on clean data). Each SKU is a wedge into the next.
