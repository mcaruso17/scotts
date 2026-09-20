# Scott Cunningham Newsletter — Latest Issue Summary

**Publication:** *Scott's Mixtape Substack* (causalinf.substack.com)
**Post:** "Parallel Trends is a Debiasing Method"
**Date received:** 17 September 2026
**Link:** https://causalinf.substack.com/p/parallel-trends-is-a-debiasing-method

> Retrieved from the subscriber's inbox on 20 September 2026. This is the most
> recent newsletter as of that date.

---

## Main themes

- **A unifying way to read difference-in-differences (DiD):** the same
  selection-bias decomposition that applies to a simple comparison of means
  also applies to DiD.
- **Parallel trends re-framed:** the parallel-trends assumption is exactly the
  condition that a *selection-bias term* equals zero.
- **DiD as a bias-adjustment (debiasing) estimator:** framing DiD through
  Heckman, Ichimura and Todd (1997) imputation rather than only through fixed
  effects.

## Key points / insights (one line each)

- A regression of an outcome on a treatment dummy returns the simple difference
  in group means, which decomposes into the ATT plus a selection-bias term
  (the same coefficient written in the untreated potential outcome, Y(0)).
- DiD is likewise an OLS regression — but of the *first difference* (the trend)
  on a treatment dummy — so it admits the very same ATT-plus-bias decomposition.
- What we usually call the "parallel trends assumption" is precisely the
  requirement that DiD's analog of the selection-bias term sums to zero.
- DiD is always two things at once: a *calculation* ("four averages and three
  subtractions") that can always be computed, and a *research design* whose
  credibility rests on the parallel-trends belief being true.
- Heckman, Ichimura and Todd (1997) is, mechanically, a procedure that
  *de-biases* the treatment group's first difference so that, under conditional
  parallel trends, the debiased quantity identifies the ATT.
- The recipe: regress the first difference on covariates in the control group,
  impute the counterfactual trend for the treatment group, then subtract that
  imputed trend from the treatment group's realized trend.
- Viewing DiD as bias adjustment makes clear it is *functional-form dependent*,
  which opens the door to flexible machine-learning imputation when there are
  many covariates.
- Caveat: this bias-adjustment view still requires knowing the relevant
  covariates in advance.

## Links, resources & calls to action

- **Read online:** https://causalinf.substack.com/p/parallel-trends-is-a-debiasing-method
- **Referenced work:** Heckman, Ichimura & Todd (1997); framing credited to
  Angrist & Pischke's treatment of selection bias.
- **Call to action:** standard Substack footer — "consider becoming a free or
  paid subscriber" to support the reader-supported publication.

---

### Recent issues (context)

The current post is the latest installment in an active run that alternates
between (a) a technical difference-in-differences series and (b) a free
"Claude Code" / AI-agents-for-research series. Recent titles include:

| Date | Title | Track |
|------|-------|-------|
| 2026-09-17 | Parallel Trends is a Debiasing Method | DiD |
| 2026-09-09 | Connectors and My Harness Idea | Claude Code |
| 2026-09-07 | Four Rungs of Covariate Inclusion in Callaway and Sant'Anna | DiD |
| 2026-09-04 | Where and how will the human be in the loop? | Claude Code |
| 2026-09-03 | Which covariates? When to include them? | Claude Code |
| 2026-09-02 | Some thoughts about AI in practice | Claude Code |
| 2026-08-24 | How and why I am using hooks (part 1) | Claude Code |
| 2026-08-14 | Which stages of research production should we let AI Agents loose | Claude Code |
| 2026-08-07 | How to improve understanding with Claude Code | Claude Code |
