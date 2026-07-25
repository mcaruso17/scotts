# Scott Cunningham Newsletter — Latest Summary

**Publication:** *Scott's Mixtape Substack* (causalinf.substack.com)
**Author:** Scott Cunningham, Professor of Economics, Baylor University; author of *Causal Inference: The Mixtape*
**Summary compiled:** 2026-07-25

> **Access note:** Substack (and several secondary sites) were not directly reachable from this environment's network policy — direct page fetches returned `403`. This summary is reconstructed from web-search result snippets, the community *AI in Economic Research* wiki, and Scott's public **MixtapeTools** GitHub repository. Treat post-level details as best-effort rather than verbatim.

---

## Main topics / themes

- **Agentic coding for empirical economics** — the ongoing "Claude Code" series (now ~51 posts) on using AI agents for real quantitative social-science research.
- **The "Odd Couple" live collaboration** — Scott Cunningham + Caitlin Myers (Middlebury) writing a paper *in public*, on how driving distance to the nearest abortion clinic changed marriage flows in Texas after House Bill 2 closed roughly half the state's clinics.
- **Causal inference craft** — deep dives on difference-in-differences, including continuous/"dosage" treatments (e.g., minimum-wage levels, not just up/down).
- **Verification & research integrity** — cross-language replication, code audits, and citation checking as first-class steps.

## Key points / insights (one sentence each)

- Scott frames Claude as a **"thinking partner, not a code monkey"** — "the dialogue is the work, not just the delivery mechanism for the work."
- His workflow favors **iterative steering over full automation**, keeping the researcher in the loop at every decision.
- He treats **markdown files (`CLAUDE.md`, `README.md`, session logs) as external memory** — persistent shared state that Claude reads at session start and updates at session end.
- **"Design before results":** get the specification and identification strategy right before trusting any point estimate.
- **Cross-replication is a bug-catcher:** implementing key analyses in R *and* a second language (Stata/Python) works because "the mistakes Claude makes in R and Stata are largely independent — orthogonal error vectors."
- The **"Referee 2"** protocol runs a fresh, independent Claude instance as a skeptical reviewer that audits code and replicates results but **never edits the author's code** (author/reviewer separation).
- **"Blindspot"** applies a peripheral-vision audit to surface overlooked problems and under-exploited strengths in a draft.
- **"Bibcheck"** spawns many narrow agents to verify each citation against canonical sources, catching systematic transcription errors.
- The Odd Couple episodes show agents doing **real research plumbing** — acquiring data, making maps, and drawing the diff-in-diff design collaboratively.
- Scott is packaging this body of work into a forthcoming book, **"AI Agents for Research Workers."**

## Links, resources & calls to action

- **Newsletter:** https://causalinf.substack.com/ (Claude Code section: https://causalinf.substack.com/s/claude-code)
- **Latest capstone-style post:** *Claude Code 51: Harnessing AI Agents for Economic Research* — https://causalinf.substack.com/p/claude-code-51-harnessing-ai-agents
- **Ongoing series:** *The Odd Couple, Season 5* (setting up, getting data, "what's up with this data?", making maps, drawing the diff-in-diff) — on Substack and *The Mixtape with Scott* podcast.
- **Tooling (open source):** MixtapeTools — https://github.com/scunning1975/MixtapeTools (Referee 2, Blindspot, Bibcheck, Split-PDF, Beamer deck tools, TikZ collision audit, GTD research harness).
- **Community wiki:** *AI in Business & Economic Research* — https://velikov-mihail.github.io/ai-econ-wiki/ (per-post summaries of the Claude Code series).
- **Call to action:** subscribe to the Mixtape Substack; fork/adapt MixtapeTools for your own lab; follow the Odd Couple paper as it's written live.

---

*Sources:* [Scott's Mixtape Substack](https://causalinf.substack.com/) · [Claude Code series](https://causalinf.substack.com/s/claude-code) · [Claude Code 51](https://causalinf.substack.com/p/claude-code-51-harnessing-ai-agents) · [MixtapeTools repo](https://github.com/scunning1975/MixtapeTools) · [AI-econ wiki](https://velikov-mihail.github.io/ai-econ-wiki/) · [AI Economist interview](https://www.aieconomist.io/articles/scott-cunningham-claude-code-ai-economists)
