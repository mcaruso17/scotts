# Scott Cunningham Newsletter — Summary

**Source:** Scott's Mixtape Substack — <https://causalinf.substack.com>
**Compiled:** 2026-09-06

> **Retrieval note:** The Substack domain (and Substack generally) was blocked by
> this environment's network egress proxy, and posts are partly paywalled, so the
> full text of individual issues could not be fetched. This summary is built from
> publicly indexed post titles and search excerpts. The single *latest* issue
> could not be confirmed with certainty — treat the items below as Scott's recent
> output rather than a guaranteed "newest post."

## Main themes

- **An ongoing "Claude Code" series** documenting, in near-real-time, how an
  agentic coding assistant is used for *practical* quantitative / empirical
  social-science research (started mid-December 2025, still running).
- **The econometrics of LLMs** — when models are used to *measure* variables that
  then enter a statistical analysis, and what that does to inference.
- **Reproducibility and the software "canon"** — reviving old projects, handling
  deprecated code, and cross-checking results across languages and packages.
- **The bigger picture** — how AI agents change research productivity, publishing,
  peer review, and the future comparative advantage of human researchers.

## Key points / insights (one line each)

- Scott frames Claude Code use as documenting "what I'm learning," filling a gap
  left by material that treats the tool abstractly or only from a developer's view.
- A signature workflow is the **apples-to-apples audit**: replicating one estimand
  (e.g. difference-in-differences) independently across Python, R, and Stata and
  across competing packages to confirm a result is a property of the method.
- He runs **multiple agents to audit each other's code and diffs**, using
  independent passes as a lightweight substitute for a second human reviewer.
- A major applied thread is **reclassifying text at scale** (on the order of
  ~305,000 historical speeches), which crystallised for him the econometric
  cautions about validation samples and training-data leakage.
- His **explainer of Ludwig, Mullainathan & Rambachan's "Large Language Models: An
  Applied Econometric Framework"** stresses no-leakage for prediction and a
  validation sample for estimation — without which model/prompt choices can swing
  estimates dramatically.
- He notes agents **create new problems even while solving old ones**, e.g.
  silently abandoning promising work — motivating having Claude keep a *diary* of
  everything it did, including discarded attempts ("Claude Code 50").
- Recurring artefact use: generating **teaching decks and explainers** directly
  from the underlying analysis code.
- A speculative essay imagines a **near future where humans lose the comparative
  advantage in research**, and reconsiders what peer review was for.

## Links / resources / calls to action

- **Claude Code series hub:** <https://causalinf.substack.com/s/claude-code>
- **LLM econometrics explainer:** <https://causalinf.substack.com/p/explainer-of-ludwig-mullainathan>
- **Underlying paper (Ludwig, Mullainathan & Rambachan), NBER WP 33344:**
  <https://www.nber.org/papers/w33344>
- **MixtapeTools (his AI-assisted coding/teaching tools):**
  <https://github.com/scunning1975/MixtapeTools>
- **Call to action:** Mixtape Sessions causal-inference workshops (recurring;
  online and in-person) are regularly announced in the newsletter.
