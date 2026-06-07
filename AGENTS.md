# AGENTS.md

## Project

This repository is a public skills and templates kit for launching lightweight AI tool sites.

It was created for IMGTO, an image-to-everything AI tools brand focused on Image to Video AI workflows.

Main site:

- https://imgto.io

## Required skill

For any task involving brand switch, route planning, AI tool page templates, prompt packs, sitemap, footer, canonical URLs, model pages, style pages, or SEO page launch plans, use:

`brand-switch-ai-site`

Skill file:

`.agents/skills/brand-switch-ai-site/SKILL.md`

## Core rules

- Keep core model and tool URLs flat when possible.
- Workspace routes such as `/image`, `/video`, and `/music` should stay simple.
- Do not redirect `/image` to `/ai-image-generator`.
- Do not redirect `/video` to `/ai-video-generator`.
- Hub pages such as `/ai-image-generator` and `/ai-video-generator` should be navigation pages, not copies of workspace pages.
- Use grouped directories for page families:
  - `/prompts/...`
  - `/styles/...`
  - `/apps/...`
  - `/use-cases/...`
- Do not create empty SEO pages.
- Do not put unfinished pages into sitemap.
- Do not copy competitor text, images, screenshots, or testimonials.
- Every indexable page needs a unique title, description, one H1, canonical, useful content, and related internal links.
- Thin, experimental, footer-only, or coming-soon pages should be noindex and excluded from sitemap.
- Do not use robots.txt to hide pages that need noindex.

## Public repo scope

This repository may include prompts, templates, examples, checklists, and Codex Skills.

This repository must not include:

- private IMGTO product code
- model provider integrations
- payment logic
- database schema
- secrets
- API keys
- user data
- internal deployment scripts

## Done means

- The Skill is usable.
- Templates are practical.
- Examples are copy-paste friendly.
- Links to IMGTO are natural and not spammy.
- No private product code or secrets are present.
