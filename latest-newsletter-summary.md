# Scott Cunningham — Latest Newsletter Summary

**Publication:** *Scott's Mixtape* Substack (causalinf.substack.com)
**Post:** *Vertical regression and selection bias in diff-in-diff (plus some pictures of Pisa and Stresa Italy)*
**Date:** June 12, 2026
**Access:** Free (not paywalled)
**Link:** https://causalinf.substack.com/p/vertical-regression-and-selection

---

## Main topics / themes
- **Travel diary** — teaching a 3-day workshop at Sant'Anna University (Pisa); a gap-filling stop in Stresa on Lake Maggiore; intermittent fasting on the road.
- **Difference-in-differences theory** — parallel trends reframed as a form of selection bias.
- **Equivalence of "horizontal" and "vertical" regression** in diff-in-diff and synthetic control.

## Key points / insights
- Diff-in-diff is a *research design* (calculation + identification assumption), not merely a regression.
- Under no-anticipation with a never-treated comparison group, the only remaining bias in the 2×2 is the non-parallel-trends term — which is why parallel trends *is* the identifying assumption.
- "Parallel trends" is really just **selection bias**: a gap in mean untreated potential outcome `Y(0)` between groups, expressed in first differences.
- The diff-in-diff bias term is *itself* a diff-in-diff — a 2×2 ("four averages and three subtractions") on `Y(0)` rather than realized `Y`.
- Following Imbens and coauthors, synthetic control is a **"vertical regression"** (comparing groups across time); the horizontal (first-difference) and vertical (within-time group-difference) specifications are algebraically equivalent, and TWFE does both at once.
- Selection bias is measured using the *post-treatment* `Y(0)`, not "pre-trended" `Y(0)` — they aren't the same outcomes that must be parallel.

## Links, resources & calls to action
- **Article:** Baker, Callaway, Cunningham, Goodman-Bacon & Sant'Anna — *"Difference-in-Differences: A Practitioner's Guide,"* *Journal of Economic Literature*.
- **Books:** Angrist & Pischke, *Mostly Harmless Econometrics*; Cunningham, *Causal Inference: The Mixtape*.
- **Imbens et al.** synthetic control papers (Doudchenko & Imbens; matrix completion; synthetic DiD; Imbens & Viviano).
- **Currently reading:** C.S. Lewis, *The Four Loves*; Marie Howe, *What the Living Do*.
- **CTA:** Become a free or paid subscriber to support the publication.
- **Coming next week:** a return to the topic of covariates in diff-in-diff.

> Note: This edition is a causal-inference/econometrics post rather than part of the "Claude Code" / AI series. The accompanying LaTeX document (`ai-in-research-claude-code.tex`) synthesises the AI-in-research concepts from the surrounding Claude Code series.
