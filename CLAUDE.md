# CLAUDE.md

This file provides context for AI assistants working in this repository.

## Repository Purpose

This is a **GitHub profile repository** (`leonardolimanas/leonardolimanas`). Its sole purpose is to render a customized profile page on https://github.com/leonardolimanas. GitHub automatically displays the contents of `README.md` as the profile landing page.

## Repository Structure

```
leonardolimanas/
├── assets/
│   └── profile-header.svg   # Custom SVG banner displayed at the top of the profile
└── README.md                # GitHub profile page (rendered automatically by GitHub)
```

No source code, tests, build tooling, or dependencies exist in this repository.

## Owner Profile

- **Name:** Leonardo Lima Nascimento (@leonardolimanas)
- **Role:** Software engineer and DevOps/SRE Manager
- **Focus areas:** Practical products, AI integrations, SDKs, DevOps workflows, platform reliability, and engineering hiring

## Tech Stack (as documented in README)

| Category | Technologies |
|---|---|
| Frontend | Vue.js, TypeScript, JavaScript, HTML5, CSS3 |
| Backend | Python, Go, PHP |
| DevOps/Infra | Docker, Docker Compose, GitHub Actions, Shell/Bash |
| Observability | Prometheus, Alertmanager, Grafana, Loki, Tempo, k6 |
| Setup | macOS, VS Code, Git |

## Featured Projects Referenced

- **`doctor-nfse-website`** — Vue, TypeScript, CSS, HTML, Shell, Dockerfile
- **`sudoku-go-game`** — JavaScript, Go, CSS, HTML
- **`samuraibot`** — Python, PHP
- **`deriv-bot`** — Python, TypeScript, CSS, Shell, JavaScript, HTML
- **`feegow/devops-trial-task`** — DevOps hiring evaluation (Prometheus, Alertmanager, Grafana, Loki, Tempo, k6)

## Development Conventions

### Editing README.md
- The file uses standard GitHub-Flavored Markdown (GFM)
- Badges use the `shields.io` service with `for-the-badge` style for visual consistency
- The header image (`./assets/profile-header.svg`) is always the first element
- Keep sections in order: Social → Dev Stack → Setup → Featured Repos → DevOps → GitHub Stats

### Editing the SVG Header
- File: `assets/profile-header.svg`
- Edit directly; no build step required
- Optimise for rendering on both light and dark GitHub themes

### No Build or Test Steps
There are no build scripts, linters, or tests to run. Changes to `README.md` or the SVG are effective immediately after pushing to the default branch (`master` / `main`).

## Git Workflow

- Default branch rendered by GitHub: `main` (or `master` — whichever is set as default in GitHub settings)
- Commit messages should be clear and descriptive (e.g., `Update profile README visual layout`)
- Feature or AI-assisted branches follow the pattern: `claude/<description>-<id>`
- Push with: `git push -u origin <branch-name>`

## What AI Assistants Should Know

1. **Scope is intentionally minimal.** Do not add source code, package files, or tooling unless explicitly requested.
2. **README.md is the product.** Changes here directly affect how the public GitHub profile looks.
3. **Preserve badge style.** All shields.io badges should use `style=for-the-badge` for visual consistency.
4. **No secrets or credentials** belong in this repository.
5. **SVG assets** should remain self-contained (no external font or image dependencies) so they render correctly in GitHub's CSP-restricted environment.
