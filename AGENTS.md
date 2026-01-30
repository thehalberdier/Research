# Agent Instructions (Repo)

This repository is a Quarto website project.

## Defaults

- Prefer writing new documents as `.qmd` (not `.md`).
- Put site-level settings in `_quarto.yml`.
- Keep pages linked from `index.qmd` and/or the navbar in `_quarto.yml`.
- Do not commit rendered output (`_site/`) or Quarto cache (`.quarto/`).

## Common tasks

- Render site: `quarto render`
- Preview with live reload: `quarto preview`
- Render a single file: `quarto render path/to/file.qmd`

## Conventions

- Use YAML front matter in each `.qmd` with at least `title:`.
- Prefer Markdown links in angle brackets for raw URLs (`<https://...>`).
- Keep tables as Markdown tables unless a page needs computation; only add code chunks when required.

