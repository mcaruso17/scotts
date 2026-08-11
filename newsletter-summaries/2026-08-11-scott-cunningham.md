# Scott Cunningham Newsletter — Summary (as of 11 Aug 2026)

**Publication:** *Scott's Mixtape Substack* — <https://causalinf.substack.com>
**Latest identifiable posts:** "Stale code, deprecation, and the canon" (21 Jul 2026)
and "Claude Code 56: Falling marginal costs of production, output, and aggregate errors" (6 Jul 2026).

> Note: Substack was unreachable directly (network egress blocked), so this summary
> was reconstructed from public search excerpts. No post dated *after* 21 Jul 2026 was
> found; treat that as the latest available rather than a guaranteed "newest today."

---

## Main topics / themes
- **AI coding agents (Claude Code) in applied empirical social science** — the running subject of a 55+ essay series begun Nov 2025.
- **The economics of cognitive production** — what happens when the marginal cost of an analysis, a draft, or a deck falls toward zero.
- **Verification over production** — as agents generate the work, the human job shifts to checking it.
- **Reproducibility & workflow discipline** — cross-language replication, independent audits, and maintained project "canon."

## Key points / insights (one sentence each)
- The marginal cost of producing a unit of cognitive output (a table, a figure, a manuscript) is collapsing toward epsilon.
- Lower per-unit cost raises total output — but aggregate errors can rise even as each project gets cheaper.
- Agents have *unbundled* the production of research from its verification, making verification the researcher's distinctive new task.
- An agent cannot credibly audit its own work, so independence must be engineered into the review step.
- Cross-language replication (R = Stata = Python to 6+ decimals) exploits the fact that independent implementations fail *differently*, exposing bugs a single-language check misses.
- The "Referee 2" protocol runs an independent, non-destructive audit in a fresh terminal by an agent that never saw the project, across five parallel checks.
- Agents should *assist* peer review (reproduce, stress-test) but not *author* the referee report — humans keep accountability.
- Committed `CLAUDE.md` "canon" plus reusable skills turn ad-hoc prompting into repeatable quality control.
- Agents create new failure modes too — silent sample-size drift (N → N+k), stale/deprecated code — and don't guarantee time savings.
- The series frames all of this in standard economics (e.g., labor and minimum-wage reasoning), not as an exceptional case.

## Links, resources, and calls to action
- Series hub: <https://causalinf.substack.com/s/claude-code>
- Claude Code 56 (marginal costs): <https://causalinf.substack.com/p/claude-code-56-falling-marginal-costs>
- Stale code / deprecation / canon: <https://causalinf.substack.com/p/stale-code-deprecation-and-the-canon>
- Claude Code 44 (four criteria; referee reports): <https://causalinf.substack.com/p/claude-code-44-my-four-criteria-for>
- Claude Code 45 (AI agents and the minimum wage): <https://causalinf.substack.com/p/claude-code-45-ai-agents-and-the>
- Open tooling — MixtapeTools (workflow, skills, Referee 2 audit): <https://github.com/scunning1975/MixtapeTools>
- **CTA:** posts are free for a few days, then paywalled — subscribe to *Scott's Mixtape* to follow the ongoing series.
