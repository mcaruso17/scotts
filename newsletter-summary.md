# Scott Cunningham Newsletter — Latest Issue Summary

**Publication:** *Scott's Mixtape Substack* (causalinf.substack.com)
**Title:** "When should you control for covariates in your diff-in-diff design?"
**Date:** June 17, 2026
**Access:** Partially paywalled (free preview summarized below)
**Link:** https://causalinf.substack.com/p/when-should-you-control-for-covariates

---

## Main Topics / Themes
- **Econometrics:** When covariate control is *mandatory* in difference-in-differences (DiD) designs.
- **Conditional parallel trends:** The formal conditions under which covariate imbalance breaks the parallel-trends assumption.
- **Travel / personal notes:** Berlin (DIW Berlin / Berlin School of Economics), upcoming stops in Pisa, Lucca (IMT), San Sebastián, and KU Leuven (Belgium).

## Key Points / Insights
- Covariates become mandatory when they are needed to satisfy *conditional* parallel trends, which involves three distinct bias terms.
- The three bias sources are: (1) covariates imbalanced between treatment and control, (2) heterogeneous treatment effects across those covariate dimensions, and (3) reliance on time-*invariant* covariates for conditional parallel trends.
- A common misconception is that time-invariant confounders are automatically absorbed by the unit fixed effect (first difference) and so need no control.
- This is wrong because DiD bias comes from *trend* differences in the untreated potential outcome Y(0), not from *level* differences.
- "Selection on levels" is fine for DiD, but "selection on trends" is not — so confounders driving differential trends must be kept in the model.
- The newsletter derives the problem formally from a two-way fixed-effects regression with additive covariates, showing how *changing returns to a covariate over time* (β₁ ≠ β₂) generates bias under imbalance.

## Links / Resources / Calls to Action
- **Read on web:** https://causalinf.substack.com/p/when-should-you-control-for-covariates
- **Referenced work:** Section 4 of the author's *Journal of Economic Literature* (JEL) survey on conditional parallel trends.
- **Talk:** Presenting a paper on "discretion and the behavior of AI agents" at IMT Lucca.
- **CTA:** Become a free or paid subscriber to support the reader-supported publication (this post is paywalled past the preview).
