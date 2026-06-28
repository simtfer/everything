# everything

## Cursor Cloud specific instructions

This repository is **content-only**: a collection of Markdown articles under `articles/`, indexed by `README.md`. There is no application source code, no dependency manifest, no build step, and no backing services. "Developing" here means writing/editing Markdown.

- There is nothing to install or build. The update script is intentionally a no-op.
- Lint/test/build: none exist. Validation = rendering the Markdown and reading it.
- To preview articles rendered as HTML (with live reload), run a Markdown server, e.g.:
  `npx -y markserv -p 8080 -a 0.0.0.0 .`
  then open `http://localhost:8080/` (the README index) and follow links to articles. `markserv` is a dev convenience tool, not a repo dependency, so it is fetched on demand via `npx` rather than installed by the update script.
- Article filenames and content are in Chinese; keep links in `README.md` in sync when adding articles.
