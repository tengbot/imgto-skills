# AIADS Skills

Ad creation skills for AI agents.

Built for [AIADS.IM](https://aiads.im), an AI Ads Generator for UGC video ads, product videos, hooks, scripts, translations, and creative variations.

AIADS Skills is a public kit of Skill files, prompts, ad templates, page templates, and launch checklists for building AI ad creative workflows.

## Core idea

```text
Input product -> Generate ad creatives
```

Expanded workflow:

```text
Product image / URL / description / script / reference ad
-> ad angle
-> hook
-> script
-> storyboard
-> video
-> captions
-> voiceover
-> creative variations
-> download
```

## What this repo is for

Use this repo when you want an AI agent or coding agent to help create:

- ad hooks for the first 3 seconds
- UGC video ad scripts
- product video ad scripts
- product image to ad video briefs
- URL to video ad briefs
- localized captions and CTAs
- creative variation batches
- AI ad landing pages
- sitemap, footer, canonical, and route plans for ad tool sites

## What this repo is not

This repository is not the private AIADS product codebase.

It does not include:

- model provider integrations
- API keys
- payment logic
- credit logic
- database schema
- auth logic
- private prompt database
- user data
- deployment secrets

The production app should stay private.

## Skills included

```text
.agents/skills/aiads-site-skill/SKILL.md
.agents/skills/hook-skill/SKILL.md
.agents/skills/ad-script-skill/SKILL.md
.agents/skills/ugc-ad-skill/SKILL.md
.agents/skills/product-video-ad-skill/SKILL.md
.agents/skills/ad-translation-skill/SKILL.md
.agents/skills/creative-variation-skill/SKILL.md
```

## Quick start

```text
Use the aiads-site-skill.

Brand brief:
brandName: AI Ads
domain: https://aiads.im
mainKeyword: AI Ads Generator
homepageTitle: AI Ads Generator for UGC & Product Videos | AI Ads
homepageH1: AI Ads Generator
homepageDescription: Create UGC video ads, product videos, hooks, thumbnails, translations, and ad variations for TikTok, YouTube, Instagram, Facebook, and X.

P0 pages:
/
/ad-video-generator
/product-image-to-video
/url-to-video
/ugc-video-ads
/product-video-generator
/ai-hook-generator
/ai-ad-script-generator
/ad-translation
/pricing

Do not touch payment, database, API keys, or private product logic.
```

## Repository map

```text
.agents/skills/       Skill files for AI agents
prompts/              Copy-paste prompts for ad creative workflows
templates/            Reusable page and creative templates
examples/             Example product briefs
docs/                 Practical docs and launch checklists
```

## Page strategy

AI ad tools should not rely on one homepage. Useful traffic and useful product flows usually come from a small set of focused pages:

- AI Ad Video Generator
- Product Image to Video
- URL to Video
- UGC Video Ads
- Product Video Generator
- AI Hook Generator
- AI Ad Script Generator
- Ad Translation
- Pricing

Every indexable page should have a clear H1, useful examples, related links, FAQ, and a real product CTA.

## Responsible marketing note

Use these Skills to create draft ad creatives and testing variations.

Do not promise:

- guaranteed viral results
- guaranteed ROI
- guaranteed conversions
- guaranteed sales

Use safer language:

- designed for faster creative testing
- helps generate draft ad creatives
- helps create multiple creative angles
- helps localize ad assets
- helps produce ad variations

## Useful links

- Main site: [https://aiads.im](https://aiads.im)
- Core keyword: AI Ads Generator
- Core workflow: Input product -> Generate ad creatives
