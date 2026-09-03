# Scott Cunningham — Scott's Mixtape Substack: Latest Summary

_Prepared: 2026-09-03 (scheduled routine)_

> **Retrieval note.** The live newsletter at `causalinf.substack.com` (and
> `substack.com`) could not be fetched directly — this session's network
> egress proxy blocks the Substack domains (HTTP 403 on CONNECT). The summary
> below reconstructs the newsletter's **current themes and most recent posts**
> from public search results and from Cunningham's own, reachable GitHub
> repository (`scunning1975/mixtapetools`). Post-level details are therefore
> best-effort rather than a verbatim read of a single latest issue.

## About the newsletter
- **Author:** Scott Cunningham, economist and professor at Baylor University; author of _Causal Inference: The Mixtape_.
- **Publication:** _Scott's Mixtape Substack_ (`causalinf.substack.com`), ~28K+ subscribers.
- **Current editorial thrust:** teaching causal inference / econometrics while documenting, in the open, how **agentic AI (Claude Code)** is changing how empirical researchers actually work.

## Main topics / themes
- **Claude Code for empirical social science** — an ongoing series on practical, real-world quantitative research workflows.
- **Cross-language, cross-package replication** as a verification discipline.
- **Difference-in-differences (DiD)** — covariates in DiD, continuous treatment, and reading pre-trends correctly.
- **"The Odd Couple" (Season 5)** — a live, public collaboration with Caitlin Myers (Middlebury), writing a paper end-to-end on video using Claude Code.
- **Tooling and workflow** — reusable Claude Code skills/protocols for auditing, presentations, and bibliographies (his `mixtapetools` repo).

## Key points / insights (one line each)
- Cunningham ran a **coding audit of ~96 specifications** for a popular DiD estimator across **three languages (R, Python, Stata)** and multiple packages, and got materially different estimates — sometimes off by ~5×.
- The discrepancies traced to how each package **handles logit estimation under perfect separation** — some refuse, some silently return garbage, and some quietly drop to a constant-only logit despite being told to use covariates.
- The lesson: **replicating the same spec across software is a bug-detector**, not busywork — single-implementation analysis can hide serious errors.
- He frames Claude Code as a **"thinking partner," not an autonomous agent** — "the dialogue is the work," with less automation than many people prefer.
- **Design before results:** get the identification/specification right first; point estimates only matter after intentional experimental design.
- **Adversarial review needs structural separation:** a fresh Claude instance should audit work it didn't create ("don't ask the student to grade their own exam").
- **Documentation is a first-class output:** "if it's not documented, it didn't happen," with dated correspondence forming an audit trail.
- Because Claude has **no memory between sessions**, he uses a `CLAUDE.md` markdown file as persistent "institutional memory" for each project.
- In "The Odd Couple," he and Caitlin Myers use Claude Code to **build maps, figures, and the identification strategy** for a Texas HB2 study (travel distance to the nearest abortion clinic after half the state's clinics closed) using **continuous-treatment DiD**.

## Recent / notable posts (best-effort, newest-leaning)
- **"The Odd Couple" Season 5** — e.g. _Episode 6: How will we draw our diff-in-diff?_, _Episode 5: Making Maps with Claude Code!_, _Season 5, Episode 2: Setting it up and getting the data._
- **Covariates in difference-in-differences** — a short series laying out why covariates are needed in DiD.
- **The multi-language DiD coding-audit post** — replicating a popular estimator across R/Python/Stata and surfacing divergent estimates.
- **Mixtape University series** — e.g. _Diff-in-diff with a checklist: understanding the No-Anticipation violation._

## Links, resources & calls to action
- Newsletter: `https://causalinf.substack.com/` (dedicated section: `.../s/claude-code`)
- Tools repo: `https://github.com/scunning1975/mixtapetools` — Claude Code workflows/skills for research (Referee 2, Blindspot, Bibcheck, split-pdf, beautiful_deck, compiledeck, tikz, GTD harness).
- Podcast: _The Mixtape with Scott_.
- Book: _Causal Inference: The Mixtape_ — free online at `https://mixtape.scunning.com`.
- Implicit CTA: subscribe to the Substack, follow "The Odd Couple" series, and try the open-source Claude Code research tooling.

---
_Sources: Scott's Mixtape Substack (title/snippet metadata via web search, page bodies egress-blocked), and the reachable `scunning1975/mixtapetools` GitHub repository._
