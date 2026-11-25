# Contributing

Thank you for contributing to **Awesome Weight-Space Programming**.

## Scope

Papers covering any aspect of **weight-space programming** or **weight-space learning** are welcome, including:
- LLM weight-space programming, auditing, and circuit synthesis
- Weight-space symmetries, invariance, equivariance, and optimization
- Metanetworks, probing, function prediction, and weight-space representations
- Hypernetworks, weight-space diffusion/flow matching, and parameter generation
- Model editing, merging, and steering
- Datasets, benchmarks, surveys, and theses on neural network weights

## Strict Pull Request Rules (Automated Enforcement)

An automated maintainer checks pull requests daily. Non-compliant PRs (including any file deletion, edit, or unallowlisted link) are **closed immediately** with an explanatory comment:

1. **Allowed Changes (`README.md` additions only)**
   - External PRs may **only add new paper lines (`+`)** to `README.md`.
   - Deleting or modifying existing lines in `README.md`, or adding/editing/deleting any other file (such as `CONTRIBUTING.md`, `CITATION.cff`, `LICENSE`, or `.github/`), is not permitted and will be closed immediately.
2. **Entry Format**
   - Add one single-line bullet under the most appropriate section:
     ```markdown
     - **[Paper Title](https://arxiv.org/abs/XXXX.XXXXX)** — *Venue Year*
     ```
   - An optional official GitHub code repository link may be appended:
     ```markdown
     - **[Paper Title](https://arxiv.org/abs/XXXX.XXXXX)** — *Venue Year* · [Code](https://github.com/owner/repo)
     ```
3. **Allowed Domains (No Redirects)**
   - Every paper entry must include a direct `https://` URL (with **no HTTP redirects**) from one of the following allowlisted academic hosts:
     - `arxiv.org`
     - `openaccess.thecvf.com`
     - `proceedings.mlr.press`
     - `proceedings.neurips.cc`
     - `papers.nips.cc`
     - `aclanthology.org`
   - *(Note: `openreview.net` is currently excluded from automated verification because its challenge/redirect responses block unattended non-redirect checks.)*
   - Code links are optional and permitted **only** as a repository root URL on `https://github.com/<owner>/<repo>` (no redirects, no `raw.githubusercontent.com`, no release binaries).
   - Any PR containing URLs outside the allowlist (in the diff or PR description) will be closed immediately without visiting those URLs.
4. **No Duplicates**
   - Check `README.md` before submitting to avoid duplicate papers or arXiv IDs.
