# MVP Club — Lessons

Free, hands-on lessons from [MVP Club](https://mvpclub.ai) on building with AI.

**Live site:** https://mvp-club-internal.github.io/mvp-club-learning/

## Lessons

- **Claude Code Agents** (`claude-code-agents/`) — a self-contained HTML page used during a
  live 45–60 minute teaching session about building agents *with* Claude Code (CLAUDE.md,
  commands, skills, subagents). Open `claude-code-agents/index.html` in any browser; there
  is no build step.

## How this is published

Plain static HTML served by GitHub Pages directly from the `main` branch root. No build
step. Every push to `main` republishes the site. The `.nojekyll` file tells Pages to serve
the HTML as-is (no Jekyll processing).

## Adding a lesson

1. Create a folder named with a lowercase, hyphenated slug, e.g. `my-lesson/`, with an
   `index.html` inside.
2. Add a card linking to it in the root `index.html`.
3. Commit and push to `main`. The site updates automatically within a minute or two.
