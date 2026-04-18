# Iris Axon Lab

Personal website of **Iris Shen** — a researcher and systems builder focused on the infrastructure behind long-running AI agents: **memory, evaluation, orchestration, and runtime design**.

**Live site:** https://iris-axon-lab.github.io/

## Overview

This repository powers a personal site that brings together:

- writing on agentic systems, memory architectures, orchestration, and epistemic integrity
- project pages and builder's notes
- research notes and learner's notes in progress
- selected links to prior work in knowledge graphs and operations research

The site is organized around a through-line that connects three chapters of work:

1. **Agentic AI infrastructure** — memory, orchestration, planning, and long-running task lifecycle
2. **Knowledge graphs at Microsoft Research** — large-scale academic knowledge systems and science-of-science work
3. **Operations research at USC** — optimization, decision systems, and the gap between formally correct and actually useful solutions

Across all three, the central question stays the same:

> How does a system know what it needs to know — and act reliably on it?

## What's on the site

### Writing
Longer-form essays and technical pieces on topics such as:

- agent epistemic integrity
- memory as a first-class architectural primitive
- runtime-layer design for agentic systems
- tool and skill quality in orchestrated pipelines

### Projects
Selected builds, including:

- **Trace** — a local-first longitudinal agent project
- architecture and systems work around agent memory, evaluation, and orchestration

### Notes
A more informal working notebook for:

- builder's notes
- learner's notes
- frameworks in formation
- partial ideas that may later grow into full essays

## Representative themes

The homepage currently emphasizes five recurring themes:

- **Memory** — semantic, episodic, procedural, and prospective memory
- **Evaluation** — metrics, graders, and failure-mode-sensitive evaluation design
- **Orchestration** — tool quality, skill triggering, and compound failure across pipelines
- **Epistemic integrity** — reliable self-knowledge in long-running agentic tasks
- **Runtime systems** — the infrastructure that helps agents persist, coordinate, and complete work over time

## Selected entry points

- **Homepage:** https://iris-axon-lab.github.io/
- **Writing:** https://iris-axon-lab.github.io/posts/
- **Projects:** https://iris-axon-lab.github.io/projects/
- **Notes:** https://iris-axon-lab.github.io/notes/
- **Trace:** https://github.com/iris-axon-lab/trace

## Tech stack

This is a lightweight static site built with:

- **Jekyll 4.4**
- **Minima**
- **GitHub Pages**

The current repo includes:

- `index.html` for the homepage
- `_posts/` for writing
- `pages/` for additional site sections
- `_includes/` for shared templates and partials
- `_config.yml` and `Gemfile` for site configuration

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000
```

## Notes on tone and scope

This site is intentionally personal in voice, but the goal is not to be a scrapbook. It is meant to function as a clear public record of the questions, systems, and technical directions that matter most in the work.

## License

- **Code:** [MIT](LICENSE)
- **Written content:** © Iris Shen, all rights reserved
