---
layout: post
title: "Tool and Skill Management in Agentic Systems: A Quality Framework"
date: 2026-03-31
---

*Everyone optimizes for whether a tool executes — almost nobody measures whether the agent called it for the right reason.*

*Still cooking. The core argument is here — prose to follow.*

Tool calling gets a lot of attention. Tool *quality* gets almost none. This post proposes a three-layer framework for thinking about what makes an agentic tool actually work in production.

**The three layers:**
- **Contract quality** — is the tool's interface well-specified enough for an agent to use reliably?
- **Execution success rate** — does it do what it says, consistently?
- **Orchestration triggering accuracy** — does the agent call it at the right moment, for the right reason?

Most teams optimize layer two and ignore layers one and three. That's why their agents behave unpredictably.

**Topics covered:**
- Why tool contracts are an underrated failure surface
- Measuring orchestration triggering — not just success/failure
- The skill vs. tool distinction and why it matters
- Evaluation design for tool quality at scale

---


