# AGENTS.md

Conventions for AI coding agents working in **UX Design Role**. This file is the
canonical entry point under the [AGENTS.md](https://agents.md) standard, and it
is the first thing a Fredrin Worker reads.

## Project

A static, no-build "About me" page (`index.html` + `styles.css`) for Manoj Salunke, a UX designer, supporting a Fredrin job application.

## Commands

- Run: `python3 -m http.server 8000`, or open `index.html` directly.
- No tests or build step. Deploys to GitHub Pages via `.github/workflows/pages.yml`.

## Conventions

- Every fact on the page must come from the candidate's portfolio (https://manojsalunke.in) or resume. Never invent employers, dates or outcomes.
- Keep it dependency-free: plain HTML and CSS, accessible, readable on mobile.
