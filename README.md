# scotts

Scott Cunningham newsletter — summaries and related research notes.

## Contents

- [`docs/scott-cunningham-newsletter-summary.md`](docs/scott-cunningham-newsletter-summary.md)
  — scannable summary of the latest *Scott's Mixtape Substack* newsletter
  (topics, key insights, links, and calls to action).
- [`docs/ai-in-research-claude-code.tex`](docs/ai-in-research-claude-code.tex)
  — LaTeX document summarizing the main concepts of AI applications in
  research, focused on agentic coding tools and the use of **Claude Code**
  in quantitative social science.

## Building the LaTeX document

No TeX distribution is bundled; the source uses only standard packages.
Compile it with any LaTeX install (run twice so the table of contents and
cross-references resolve):

```sh
cd docs
pdflatex ai-in-research-claude-code.tex
pdflatex ai-in-research-claude-code.tex
```

> **Note:** the newsletter summary was assembled from public search results
> because the Substack domains were unreachable from the build environment.
> Verify exact post titles and dates against
> <https://causalinf.substack.com/archive?sort=new>.
