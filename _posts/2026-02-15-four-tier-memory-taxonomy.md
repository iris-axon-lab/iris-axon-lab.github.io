---
layout: post
title: "A Four-Tier Memory Taxonomy for Agentic Systems"
date: 2026-02-15
---

*Most AI memory architectures collapse four distinct problems into one bucket, then wonder why agents forget the wrong things.*

*Still cooking. The core argument is here — prose to follow.*

Most discussions of AI memory collapse everything into a single bucket. This post proposes a structured taxonomy: four tiers, each with distinct retrieval characteristics, update cadences, and failure modes.

**The four tiers:**
- **Semantic memory** — factual world knowledge, slow to change
- **Episodic memory** — session and interaction history, user-specific
- **Procedural memory** — how to do things, skill and tool patterns
- **Prospective memory** — what to do next, forward-looking task state *(original contribution)*

The prospective tier is the least discussed and the most critical for long-running agentic tasks. An agent that forgets what it was *about* to do is more dangerous than one that forgets what it already did.

**Topics covered:**
- Why the four-tier distinction matters operationally
- Retrieval and update patterns per tier
- Architectural implications for memory generation
- Where existing systems get this wrong

---


