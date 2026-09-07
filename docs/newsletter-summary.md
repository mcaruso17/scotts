# Scott Cunningham Newsletter — Latest Summary

**Source:** *Scott's Mixtape Substack* (`causalinf.substack.com`)
**Compiled:** 2026-09-07
**Retrieval note:** Direct fetching of `causalinf.substack.com`/`substack.com` is blocked by
this environment's network egress policy, so this summary was reconstructed from public web-search
snippets rather than the full post text. The most recent, well-documented editions available at
retrieval time are the ongoing **"Claude Code"** series (mid-Dec 2025 → ongoing) and a July 2026 note
on Substack's Claude integration. Treat exact wording and figures as approximate.

---

## Main topics / themes
- **AI agents as research collaborators** — using Claude Code end-to-end for applied quantitative
  social science (data pull → estimation → robustness → manuscript).
- **Causal inference under automation** — difference-in-differences, Callaway & Sant'Anna,
  Sun–Abraham, TWFE, Gardner estimators, run and cross-audited by agents.
- **Reproducibility & code auditing** — replicating the *same* specification across Python, R, and
  Stata (and multiple packages) to see whether estimates agree.
- **Research vs. publishing** — when the marginal cost of a manuscript falls toward zero, discovery
  and dissemination split into two separate problems.
- **Epistemics of AI-found "facts"** — if data is real, methods standard, and code audited, does it
  matter that no human designed the study?

## Key points / insights (one line each)
- Cunningham has run a rolling **"Claude Code for quantitative social scientists"** series since
  mid-December 2025, now 35+ installments deep.
- In **"Can Claude Code Find Facts?" (#29)** a vague overnight prompt produced a full
  marijuana-legalization manuscript with modern diff-in-diff plus a battery of robustness estimators.
- The agent surfaced *real* problems in its own draft — a Sun–Abraham aggregation bug and 295 false
  zeros in incarceration data — which it then fixed.
- **Multi-language / multi-package audits (#28, #31)** show six Callaway & Sant'Anna implementations
  "almost never agree" on the same data, spec, and covariates — a caution about silent method drift.
- **"Research and Publishing Are Now Two Different Things" (#27)** argues causal inference will spread
  into low-stakes venues (policy memos, city-council questions, PTA meetings) once manuscripts are cheap.
- **"Dispatch" (#34)** covers running Claude Code from a phone to revisit the cannabis paper on the go.
- The **p-hacking arc (#36–#37)** documents Cunningham revising his own priors after agent-run analyses
  of rounding, publication bias, and evidence for p-hacking.
- A **July 2026 note** describes Substack's new Claude integration, which he used to mine his own essays
  back to 2021 — encouraging readers to do the same.
- He is writing a book, **"AI Agents for Research Workers,"** growing out of the series.

## Links / resources / calls to action
- Newsletter: `https://causalinf.substack.com/`
- Claude Code series hub: `https://causalinf.substack.com/s/claude-code`
- Explainer of Ludwig, Mullainathan & Rambachan, *Large Language Models: An Applied Econometric
  Framework* (2026): `https://causalinf.substack.com/p/explainer-of-ludwig-mullainathan`
- **CTA:** subscribe to the Substack; try Claude Code on one of your own stalled projects; audit any
  agent-produced estimate across languages/packages before trusting it; explore Substack's Claude
  integration on your own archive.

---
*Prepared by an automated Claude Code routine. Verify specifics against the original posts before citing.*
