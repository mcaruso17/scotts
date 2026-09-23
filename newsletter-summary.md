# Scott Cunningham Newsletter — Latest Issue Summary

**Publication:** Scott's Mixtape Substack (*causalinf.substack.com*)
**Post:** *Parallel Trends is a Debiasing Method*
**Date:** September 17, 2026
**Link:** https://causalinf.substack.com/p/parallel-trends-is-a-debiasing-method

---

## Main topics / themes

- **Reframing difference-in-differences (DiD)** as a *bias-adjustment / debiasing* procedure rather than only a fixed-effects estimator.
- The parallel connection between the **simple difference-in-means decomposition** (ATT + selection bias) and the **DiD decomposition** (ATT + parallel-trends term).
- **Parallel trends** understood as the assumption that a "selection bias" term is exactly zero.
- The distinction between DiD as a **calculation** vs. DiD as a **research design**.
- **Heckman, Ichimura and Todd (1997)** imputation as the mechanical engine of debiasing, and its link to modern machine-learning covariate adjustment.

## Key points / insights (one sentence each)

- A regression of outcome `Y` on a treatment dummy `D` just returns the simple difference in group means, which decomposes into the ATT plus a selection-bias term (the same coefficient written in the untreated potential outcome `Y(0)`).
- DiD is "four averages and three subtractions" (the 2×2), and, like the simple comparison, can be written as an OLS regression — only of the *trend* in `Y` on the treatment dummy rather than the *level*.
- Because DiD is also a regression, it decomposes the same way, except its selection-bias term is what we call **the parallel trends assumption**.
- Parallel trends does not mean selection bias is naturally zero — it is a *design assumption* that makes it zero, which is exactly why a credible research design is needed.
- Every research design is a *calculation plus a belief* such that, if the belief holds, the estimator's sampling distribution centers on the true effect (LLN) and is approximately Gaussian (CLT), enabling hypothesis tests.
- Heckman, Ichimura and Todd (1997) is mechanically a **debiasing routine**: fit the outcome-trend model on the control group, impute the counterfactual first difference for the treated, and subtract it to remove selection bias.
- Under *conditional* parallel trends and correct functional form, that imputed counterfactual trend is correct, so the DiD is the ATT.
- Viewing DiD as bias adjustment (not just fixed effects) clarifies that the target object is the **selection bias itself**, which you estimate and delete.
- Because the adjustment is an **imputation**, it is functional-form dependent, opening the door to flexible **machine-learning estimators** when there are many covariates to model.
- The caveat: this bias-adjustment framing requires you to **know the relevant covariates in advance**.

## Links, resources & calls to action

- **Web version of the post:** https://causalinf.substack.com/p/parallel-trends-is-a-debiasing-method
- **Key reference cited:** Heckman, Ichimura & Todd (1997) — imputation-based debiasing.
- **Related framing referenced:** Angrist & Pischke's constant-treatment-effects decomposition (ATT + selection bias); the author's own book decomposition of a simple comparison of means.
- **Call to action:** the standard Substack invitation — *"Scott's Mixtape Substack is a reader-supported publication. To receive new posts and support my work, consider becoming a free or paid subscriber."*

---

*Retrieved from the subscriber's inbox (newsletter delivered Sep 17, 2026). This was the most recent issue available at the time of retrieval; no newer issue had arrived.*
