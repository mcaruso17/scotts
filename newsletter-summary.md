# Scott Cunningham — *Scott's Mixtape* Newsletter Summary

**Publication:** Scott's Mixtape Substack — <https://causalinf.substack.com>
**Author:** Scott Cunningham, Professor of Economics, Baylor University; author of *Causal Inference: The Mixtape*
**Compiled:** 2 September 2026

> ⚠️ **Retrieval caveat.** The Substack could not be fetched directly from this
> environment (`causalinf.substack.com` and `substack.com` are blocked by the
> network egress policy, and part of the series is paywalled). This summary is
> reconstructed from publicly indexed search results, so it reflects the **most
> recent identifiable content**, not a guaranteed single "latest issue." Verify
> against the source before relying on specifics.

---

## 1. Main Topics / Themes

- **Claude Code for quantitative social scientists** — an ongoing series (started mid-Dec 2025, still running) documenting agentic AI for applied empirical work.
- **Causal inference & econometrics** — explainers, difference-in-differences, and the mechanics of credible research design.
- **Reproducibility as an audit** — cross-language replication and "referee report" style verification of findings.
- **AI's effect on scholarly publishing** — speculative "Claude Code fan fiction" on how agents reshape the publishing pipeline.
- **Workshops & teaching** — Mixtape Sessions (e.g., Causal Inference I, a Sept 27 Saturday session) and an "educate 1 million people" agenda.

## 2. Key Points / Insights (one sentence each)

- **Thinking partner, not autopilot:** Claude is best used with *iterative steering* — the researcher supplies judgement and lets the agent execute only when the next step is clear.
- **Design before results:** get the specification right (fixed effects, sample restrictions, standard errors); a result is the *output* of a design, never the goal.
- **Invariants first:** before prompting, write a `done = …` definition plus 3–10 constraints the agent's code must preserve, then let it refactor freely underneath them.
- **`CLAUDE.md` as project memory:** a root file stating where truth lives, which conventions matter, and what must not change without permission.
- **The workflow loop:** Dialogue → Code → Replicate → Verify → Document.
- **Cross-language audit:** re-run the same pipeline in multiple languages/packages (e.g., difference-in-differences across Python, R, and Stata, five packages) and require identical results for every non-random step.
- **Guard against sycophancy:** agents readily produce "results you want to hear," so the workflow must resist p-hacking rather than enable it.
- **Intellectual honesty in public:** Cunningham flagged possible p-hacking in AI-drafted papers, then walked it back when the pattern turned out to be a rounding artifact in t-statistics.
- **Cost collapse:** he estimates a manuscript can now cost roughly a Claude subscription plus ~$100 in editing.

## 3. Links, Resources & Calls to Action

- 📚 Claude Code series — <https://causalinf.substack.com/s/claude-code>
- 🧑‍🏫 Mixtape Sessions workshops (Causal Inference I, Sept 27) — <https://causalinf.substack.com/p/changing-market-conditions-demand>
- 🎙️ *The Mixtape with Scott* podcast — <https://causalinf.substack.com/podcast>
- 🛠️ MixtapeTools (AI-assisted coding/teaching tools) — <https://github.com/scunning1975/MixtapeTools>
- ➡️ **CTA:** subscribe to the newsletter and register for the upcoming causal-inference workshops.
