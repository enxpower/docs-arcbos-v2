# CLAUDE.md

## Project

This repository is the public ARCBOS reference documentation repository served through `ref.arcbos.com`.

## Operating Context

This repository belongs to ARCBOS. It is part of the public reference and documentation context for ARCBOS technical or brand-facing material.

## Current Purpose

The current practical purpose appears to be a lightweight public reference repository for ARCBOS. The exact site structure and generated output need verification because the inspected repository root is minimal.

## Architecture

The repository appears to be a public documentation or reference repository with minimal inspected root structure.

Known structure from inspection:

- `README.md` exists but currently only contains the repository name and `ref`.
- `CNAME` points the repository to `ref.arcbos.com`.
- No root `index.html` was found during inspection.
- No root `package.json` was found during inspection.

Deployment is likely GitHub Pages because the repository contains a root `CNAME`, but Pages settings and the actual publishing source were not verified.

## Brand / UI Rules

This repository is public and domain-linked. If it contains or later adds public HTML, documentation, static pages, or UI assets, apply these rules:

- Desktop, tablet, and mobile layouts must be precisely responsive.
- Every release must be checked for responsive layout before publishing.
- Horizontal scrolling must be prevented on all screen sizes.
- Every public HTML page must include proper social preview metadata.
- Every public HTML page must include a strongly relevant title, description, favicon, and preview image.
- PNG preview images are preferred over SVG when social sharing compatibility matters.
- Use the correct company VI based on the brand involved.
- If no company brand applies, use Andy Gong / GONG-VI.
- Do not use dark color schemes unless the repository's VI explicitly requires it.
- Do not expose private source, credentials, or internal logic in public pages.
- All code, comments, filenames, and UI copy must be English.

For ARCBOS repositories:

- Use ARCBOS VI.
- Maintain an industrial robotics tone.
- Avoid toy-like startup visuals.
- Keep the design practical, technical, and execution-focused.

## Hard Rules

- Do not modify unrelated files.
- Do not add dependencies unless explicitly approved.
- Do not change deployment structure unless explicitly approved.
- Do not change public routes unless explicitly approved.
- Do not commit credentials, tokens, API keys, OAuth secrets, private keys, or environment variable values.
- Do not put secrets in frontend HTML or public JavaScript.
- Keep changes minimal, purposeful, and reversible.
- All generated repository content must be English-only.
- Update docs/todo-next.md at the end of every coding session.

## Session Handoff Rule

Every coding session must end by updating:

- docs/decision-log.md if a decision changed
- docs/change-log.md if files changed
- docs/todo-next.md with exact next steps

If docs/change-log.md does not exist and files were changed, create it.
