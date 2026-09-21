# Scott Cunningham Newsletter — Latest Issue Summary

**Source:** *Scott's Mixtape Substack* (causalinf.substack.com) — Scott Cunningham,
economist at Baylor University and author of *Causal Inference: The Mixtape*.
**Retrieved:** 2026-09-21

> **Retrieval note:** This environment's network egress proxy blocks `substack.com`,
> so the full post could not be fetched directly. The summary below is reconstructed
> from web-search results for the most recent identifiable post and the underlying
> academic paper it explains. Treat details as high-confidence but not verbatim.

**Latest identified post:** *"Explainer of Ludwig, Mullainathan and Rambachan's 2026
Econometrics of LLM Paper"*
(https://causalinf.substack.com/p/explainer-of-ludwig-mullainathan)

---

## 1. Main Topics / Themes

- **The econometrics of large language models (LLMs)** as tools for empirical research.
- **Using LLMs to replace expensive human annotation/labeling** of text and other data.
- **Measurement error** introduced when LLM outputs feed downstream regressions.
- **Validity conditions** for using LLMs in prediction vs. estimation tasks.
- Ongoing series theme: **how AI agents (incl. Claude Code) are changing how researchers work.**

## 2. Key Points / Insights (one sentence each)

- The post is Scott's plain-language explainer of Ludwig, Mullainathan & Rambachan's *"Large Language Models: An Applied Econometric Framework"* (Annual Review of Economics, 2026).
- The paper splits LLM use into two regimes — **prediction problems** and **estimation (measurement) problems** — each with its own validity requirement.
- For **prediction**, validity hinges on **"no training leakage"** between the LLM's training corpus and the researcher's sample, controllable via model choice and research design.
- For **estimation**, LLM labels must be paired with a **small human-coded validation sample** to yield consistent, precise downstream estimates.
- **Without a validation sample**, researchers cannot gauge LLM labeling error, so trivial choices (which model, which prompt) can swing parameter estimates dramatically.
- LLM measurement error is typically **non-classical** — it can correlate with true values and bias coefficients in *any* direction, including sign reversals, unlike random classical noise.
- High raw labeling accuracy **does not** by itself protect a regression; the validation-sample correction is what debiases the estimates.
- Practical takeaway: budget a modest amount of human labeling to **calibrate/debias** cheap, at-scale LLM labels rather than trusting them blind.

## 3. Links, Resources & Calls to Action

- **Explainer post:** https://causalinf.substack.com/p/explainer-of-ludwig-mullainathan
- **Underlying paper (NBER w33344):** https://www.nber.org/papers/w33344
- **arXiv version (2412.07031):** https://arxiv.org/abs/2412.07031
- **Annual Review of Economics 18:283–316 (2026):** https://www.annualreviews.org/content/journals/10.1146/annurev-economics-120925-105620
- **Authors' PDF:** https://sendhil.org/wp-content/uploads/2025/07/LargeLanguageModels_AnAppliedEconometricFramework.pdf
- **Newsletter home / subscribe:** https://causalinf.substack.com/
- **Implied CTA:** read the source paper, and when using LLMs for measurement, collect a validation sample to debias downstream estimates.
