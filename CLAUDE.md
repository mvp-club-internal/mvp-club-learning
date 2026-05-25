# MVP Club Lessons — Claude Code Instructions

## What This Is
A public collection of free, hands-on HTML lessons published via GitHub Pages at
https://mvp-club-internal.github.io/mvp-club-learning/. Each lesson is a self-contained
static HTML page in its own folder. There is no build step, framework, or backend.

## IMPORTANT: This is a PUBLIC repo
Never add secrets, API keys, tokens, internal URLs, credentials, or business/proprietary
content. Lessons only. Everything committed here is world-readable on the internet.

## Publishing
GitHub Pages serves this repo from the `main` branch root. Pushing to `main` republishes
the site. `.nojekyll` disables Jekyll so HTML is served verbatim — keep it in the repo.

## Structure
- `index.html` — the hub landing page; links to each lesson
- `<lesson-slug>/index.html` — one folder per lesson (lowercase, hyphenated slug)

## Brand
- Colors: Navy (#081f3f), Amber (#d97706), Golden (#fbbf24), Warm Stone (#faf5f0)
- Fonts: Zilla Slab (headers, 400 weight only), Inter (body)
- Never use cold white page backgrounds — always warm stone (cards may be white)
