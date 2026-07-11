# Scott's Mixtape — Newsletter Summary

**Source:** Scott Cunningham, *Scott's Mixtape Substack* — https://causalinf.substack.com
**Compiled:** 2026-07-11

> **Access note:** Substack and LinkedIn returned HTTP 403 to direct fetches (both the
> platform anti-scraping layer and this session's egress policy block `causalinf.substack.com`).
> This summary is therefore compiled from search-indexed post text, public Substack "notes,"
> and Cunningham's public GitHub repo (`scunning1975/MixtapeTools`), not from a full read of a
> single gated post. The most recent *flagship explainer* identified is the LLM-econometrics
> piece below; the ongoing *Claude Code* series had reached roughly part ~31.

---

## Main topics / themes

- **The "Claude Code for quantitative social scientists" series** — an ongoing, near-weekly
  log (started mid-Dec 2025) of Cunningham using Claude Code on real empirical projects.
- **Agentic AI as a research collaborator** — Claude as a *thinking partner*, not an
  autonomous agent: the human steers, Claude executes when the next move is clear.
- **Verification and replication** — cross-language / cross-package replication as the new
  bottleneck now that *producing* results is cheap.
- **The econometrics of LLMs** — when it is (and isn't) valid to use LLM outputs as data.
- **The future of research and peer review** — speculative essays on a near future where
  human researchers may lose their comparative advantage.

---

## Key points / insights

- Producing empirical results is now fast, but **verification has become the slow, binding
  step** — the returns to methodological expertise rise, not fall.
- Using an AI agent to orchestrate OpenAI's batch API, Cunningham classified **305,000
  historical speeches with zero-shot prompts in ~2.6 hours**.
- **LLM classification error is not classical measurement error**: when errors correlate with
  the outcome being studied, downstream estimates can be severely biased.
- His **cross-language coding audit** replicates a pipeline from scratch across Python, R, and
  Stata (and 5+ packages), checking that non-random results match to 6+ decimal places.
- He treats **documentation as a primary output** and enforces **adversarial review** by
  running audits in a *separate, fresh Claude instance* that never edits the author's code.
- A recurring caution: take it all "with a grain of salt" — the workflow is being figured out
  in public, not prescribed.

---

## Links, resources & calls to action

- **Newsletter:** https://causalinf.substack.com — Claude Code section: https://causalinf.substack.com/s/claude-code
- **MixtapeTools (public templates & protocols):** https://github.com/scunning1975/MixtapeTools
  - `Referee 2` — five-audit post-project review protocol (code, cross-language replication,
    directory structure, output automation, econometrics), run by an independent Claude instance.
  - `Blindspot` — "peripheral vision" audit for overlooked problems/opportunities.
  - `Bibcheck` — multi-agent bibliography verification against DOI / journal / author sources.
  - `Split-PDF` — paper ingestion into 4-page chunks with structured notes.
  - `Beautiful Deck` / `TikZ Collision Audit` — Beamer/LaTeX presentation generation & cleanup.
- **Referenced paper:** Ludwig, Mullainathan & Rambachan, *Large Language Models: An Applied
  Econometric Framework* (NBER w33344; forthcoming *Annual Review of Economics*).
- **Book:** *Causal Inference: The Mixtape* (Yale UP); sequel *Causal Inference: The Remix* due mid-2026.
- **Call to action:** follow the series, clone the MixtapeTools templates, and adopt a
  design-first + independent-verification workflow when using Claude Code for research.
