# Scott Cunningham Newsletter — Summary

**Post:** "Stale code, deprecation, and the canon"
**Publication:** Scott's Mixtape Substack (the "Claude Code" essay series)
**Date:** 2026-07-21
**Link:** https://causalinf.substack.com/p/stale-code-deprecation-and-the-canon

---

## Main themes

- **"AI Agent drift"** — the tendency of AI coding agents (Claude Code) to silently accumulate errors, duplicate programs, and mutate the analytical sample over the course of a long empirical project.
- **A rigid, staged checklist** as the antidote — a personal, harness-like workflow that forces design discipline onto AI-assisted causal-inference research.
- **The "canon" metaphor** — borrowing from how the early church curated scripture, researchers now need an explicit process to decide which agent-generated code/exhibits are *canonical* vs. *deprecated*.

## Key points & insights

- Scott first noticed drift when a project's analytical sample silently grew from N to N+k observations with no explanation, caught only because he religiously produces "beautiful tables/figures/decks."
- A second symptom: what he assumed were edits to one program had quietly become ~5K near-duplicate programs with messy naming — the old copy-paste problem, now committed by the agent.
- His fix is a personalized dashboard built around a rigid 12–14 step checklist for panel-data causal inference, grounded in Rubin's "Design Trumps Analysis," Sant'Anna's diff-in-diff checklist, and Imbens's survey guidance.
- The checklist stages run: **PKG → TARGET → BITE → COVARIATES → ROLLOUT → OUTCOME → POWER → ESTIMATOR → EVENT → FALSIFY → MECHANISM → PIPELINE → DELIVER → SIGN.**
- Each stage has repeatable "rituals" and 2–3 exhibits, tracked on the dashboard with color-coded circles: green (closed/verified), red (open — no project can ship with a red), amber (pulsing "you are here").
- He predicts a general "harness-workflow-for-empirical-research-using-AI-agents" framework will soon be articulated, after which everyone still customizes their own dashboard by comparative advantage.
- The core argument: AI agents inevitably generate an abundance of similar-but-not-identical files, figures, tables, and code — like the competing gospels — so researchers need an explicit **selection-and-curation rule** to canonize a replicable pipeline and mark the rest heresy/apocryphal.
- The goal of the harness: ensure the final exhibits are the ones you *chose*, that they mean what you think they mean, and that "future Claudes" (and your future self) can always resume knowing what is canon vs. deprecated.

## Links, resources & calls to action

- Don Rubin, *"Design Trumps Analysis"* (methodological backbone of the checklist)
- Pedro Sant'Anna's diff-in-diff checklist (also adapted in Scott's forthcoming book)
- Guido Imbens's survey articles (checklist-style guidance near the end)
- Yiqing Xu's `panelview` command (for visualizing treatment rollout)
- Gentzkow & Shapiro's classic manual on code organization / version control
- Custom Claude Code skills referenced: `/covariates`, `/referee2`, `/blindspot`
- **CTA:** subscribe (free or paid) to Scott's Mixtape Substack; new book on causal inference is out next month; a future post will walk through a full diff-in-diff project using this workflow.
