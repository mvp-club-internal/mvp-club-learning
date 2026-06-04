# MVP Club — Lessons

Free, hands-on lessons from [MVP Club](https://mvpclub.ai) on building with AI.

**Live site:** https://mvp-club-internal.github.io/mvp-club-learning/

## Lessons

- **AI Summer Camp** (`summer-camp/`) — a four-Friday beginner cohort delivered as a multi-page
  site (camp overview + one folder per session). **Published pages are password-protected**
  (client-side AES-256-GCM gate; cohort password required) — the editable plaintext source lives
  on the private `summer-camp` branch and is encrypted to `main` via `scripts/encrypt-camp.cjs`
  in the bizops-tool repo. `camp.css` and `the-one-big-idea.html` (a standalone shareable card)
  are served public. Session 1 is built; Sessions 2–4 are stubs.
- **The Four Moves of Knowledge Work with AI** (`knowledge-work-with-ai/`) — a self-contained
  HTML page teaching a tool-agnostic model (Data, Intent, Instructions, Evaluation) for getting
  good work out of any AI chat, applied to three use cases: drafting comms, project management,
  and research. A distillation of Nate B Jones' approach. Open
  `knowledge-work-with-ai/index.html` in any browser; there is no build step.
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
