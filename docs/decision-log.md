# Decision Log

## Active Decisions

- Decision: Initial Project Context Pack added.
  Reason: Future AI coding sessions need a reliable project baseline instead of relying on chat history.
  Impact: Future sessions should read `CLAUDE.md` and docs files before making changes.

- Decision: Treat this repository as a public ARCBOS reference surface.
  Reason: Inspection found a public repository with `CNAME` pointing to `ref.arcbos.com`.
  Impact: Future changes must preserve public-facing quality and avoid exposing internal or private information.

- Decision: The verified public domain is `ref.arcbos.com`.
  Reason: The root `CNAME` file contains `ref.arcbos.com`.
  Impact: Do not change domain routing, canonical URLs, or public routes without explicit approval.

- Decision: Actual publishing structure remains To verify.
  Reason: No root `index.html` or root `package.json` was found during inspection.
  Impact: Future agents must verify the site source and deployment path before changing structure or adding tooling.

- Decision: ARCBOS VI is required for any public-facing additions.
  Reason: The repository is ARCBOS-branded and public-facing.
  Impact: Future public pages must stay practical, technical, industrial, and execution-focused.
