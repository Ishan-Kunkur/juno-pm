# Juno - AI PM Copilot

> Juno is an AI Associate PM that operates inside Slack, Notion, and Jira, where the team spends its day. Juno takes on three ongoing jobs: synthesizing scattered signals into insight, drafting the specs that unblock delivery, and prioritizing the risks that most deserve attention.

_Ishan Kunkur | AI PM Cohort | October 2026_

Repo: https://github.com/Ishan-Kunkur/juno-pm

This repo is my final project for the AI Product Management Certification — **Juno - AI PM Copilot**. Each module’s artefact lives in its own folder; this README is the dashboard and the pitch.

---

## Module artefacts

### M1 · Prompting
- **System prompt** — [`01-prompting/system-prompt.md`](01-prompting/system-prompt.md)
- **Prototype** — https://lovable.dev/projects/d7e7a2bb-0ce8-48c9-92cb-848e0411dfc7?magic_link=mc_05b74ce7-d57d-4e68-8e4c-d40db17fa3d9

### M2 · Strategy
- **Decision matrix** — [`02-strategy/decision-matrix.md`](02-strategy/decision-matrix.md)
- **AI Strategy one-pager** — [`02-strategy/strategy-one-pager.md`](02-strategy/strategy-one-pager.md)

### M3 · RAG / AI PRD
- **AI PRD** — [`03-rag-prd/prd.md`](03-rag-prd/prd.md)

### M4 · AI-Native UX
- **AI user flow** — [`04-ai-ux/user-flow.md`](04-ai-ux/user-flow.md)
- **Trust-gap mitigations** — [`04-ai-ux/trust-gaps.md`](04-ai-ux/trust-gaps.md)

### M5 · Agentic Workflows
- **Agent Workflow Spec (AWSpec)** — [`05-agentic-workflows/awspec.md`](05-agentic-workflows/awspec.md)
- **Agent Control Panel** — [`05-agentic-workflows/agent-control-panel.md`](05-agentic-workflows/agent-control-panel.md)

### M6 · Evals &amp; Guardrails
- **Eval stack** — [`06-evals/eval-stack.md`](06-evals/eval-stack.md)
- **Human evaluation rubric** — [`06-evals/human-rubric.md`](06-evals/human-rubric.md)

---

## PM Execution Plan

### Where Juno is today
- M1 - M6 is specced and committed
- M1 prototype is working

### What ships next (next 2 sprints)
- Sprint 1 - Wire Tool connectors (Slack, Notion and Jira)
- Sprint 2 - Evals (harness, beta testing with PMs, review rubric Scores)

### What I watch (dashboards)
- Daily - Thumbs up/down rate, hand off rate, 
- Weekly - Rubric Score Trends, Cost

### Red lines (what blocks shipping)
- Human Eval results show critical issues
- Hallucinations 
- Juno getting stuck in a loop 
- <90% Golden set accuracy

### Governance
Compliance - PII and Financial details should not be leaked
Safety - No self harm intent should be conversed
Reliability - Eval rubric 
Reputation - Product should improve NPS with Customers

---

## Build Insights

- **Friction point.** Determining what to feed the model is important. Quality of input will drive qualtiy of output. Hence sampling the imputs are so important.
- **Key learning.** There is more to AI Product Management than Vibe Coding. When the capability to build ("How") is democratized, the "What" and "Why" to build becomes even more important
- **Aha moment.** Building a product using a foundational model is one thing. Building a AI product from scratch is a whole different game all together.

---

_Certification submission — AI Product Management Certification._
