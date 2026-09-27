# Scott's Mixtape Substack — Latest Newsletter Summary

**Post:** *Parallel Trends is a Debiasing Method*
**Author:** Scott Cunningham (Scott's Mixtape Substack)
**Published:** September 17, 2026
**Link:** https://causalinf.substack.com/p/parallel-trends-is-a-debiasing-method

> Retrieved from the email edition (site was unreachable directly). This is the most recent post as of this digest.

---

## Main topics / themes

- **Reframing difference-in-differences (DiD)** as a *bias-adjustment* (de-biasing) procedure rather than only a fixed-effects calculation.
- **The parallel trends assumption (PTA)** reinterpreted as the condition under which a "selection bias" term equals zero.
- **The dual nature of DiD**: it is simultaneously a *calculation* and a *research design*.
- **Heckman, Ichimura & Todd (1997)** as an imputation-based de-biasing estimator that identifies the ATT under *conditional* parallel trends.
- A bridge from classic econometrics to **machine-learning estimators** for flexible covariate adjustment.

## Key points / insights (one sentence each)

- A simple regression of an outcome on a treatment dummy recovers the raw difference in group means, which decomposes into the ATT plus a selection-bias term (written in terms of the untreated potential outcome Y(0)).
- Diff-in-diff is "four averages and three subtractions" (the 2×2), equivalently an OLS regression of the *first difference* (trend) on a treatment dummy.
- Just as the level comparison decomposes into ATT + selection bias, the DiD estimand decomposes into the ATT plus two extra terms that people loosely call "the parallel trends assumption."
- Parallel trends holds exactly when those extra (selection-bias) terms sum to zero — and the whole point of a research design is to make that bias vanish, since in general it need not.
- A research design = a calculation *plus* a belief such that, if the belief is true, the sampling distribution of the calculation is centered on the truth (enabling law-of-large-numbers consistency and CLT-based hypothesis tests).
- Mechanically, Heckman-Ichimura-Todd (1997) fits a regression on the control group, imputes the counterfactual first difference for the treated group, and subtracts it — literally *estimating and removing* the selection bias.
- Under conditional parallel trends and a correct functional form, that imputed treated-group trend is the counterfactual trend, so DiD becomes "four averages and three subtractions" where two averages are imputed.
- Because the correction is an imputation, it is functional-form dependent — which opens the door to flexible ML methods when there are many covariates to model.
- Caveat: this bias-adjustment framing requires knowing the relevant covariates in advance.
- Bottom line: **"diff-in-diff is a bias adjustment method which we can do because conditional parallel trends allows it."**

## Links, resources & calls to action

- **Read on the web:** https://causalinf.substack.com/p/parallel-trends-is-a-debiasing-method
- **Reference cited:** Heckman, Ichimura & Todd (1997) — imputation/de-biasing estimator.
- **Reference cited:** Angrist & Pischke — the ATT-plus-selection-bias decomposition under constant treatment effects.
- **Reference cited:** Scott Cunningham's own book (the decomposition of a simple mean comparison into treatment effects and selection bias).
- **Call to action:** "Scott's Mixtape Substack is a reader-supported publication" — consider becoming a free or paid subscriber to support the work.

*Note: The original post includes several typeset equations/images that do not render in the email edition; the equations are described above in words.*
