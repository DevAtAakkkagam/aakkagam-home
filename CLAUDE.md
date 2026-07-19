# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

Landing page for **aakkagam.com** (ஆக்கம், Tamil for "creation") — a hub linking to subdomains:

1. **skeinos.aakkagam.com** — Skeinos, a local-first browser extension for organizing AI chats
2. **games.aakkagam.com** — Aakkagam Games (align3 / Terni Lapilli & Tamil kattam, and ostomachion)

The page will later also exhibit portfolio content: websites and apps built for clients.

## Structure

Pure static site — no build step, no framework, no package.json, no tests.

- `index.html` — the entire site: all CSS and SVG inline (kolam mark with draw animation, JSON-LD, OG tags, data-URI favicon)
- `robots.txt`, `sitemap.xml` — SEO; update `sitemap.xml` `<lastmod>` when content changes

## Commands

- Local preview: `npx wrangler pages dev .` (a `.wrangler/` cache dir exists; hosting is Cloudflare Pages)
- Deploy: `npx wrangler pages deploy .`

## Conventions

- Keep everything inline in `index.html` — single-file page, no external CSS/JS files
- Design context lives in `PRODUCT.md` (strategy, register, anti-references) and `DESIGN.md` (visual system); read both before design work
- Design language: "Ink and Rice Flour" — committed deep-indigo ground (`--ink`, OKLCH) with rice-cream line work (`--cream`); fonts Alegreya / Alegreya Sans / Noto Serif Tamil via Google Fonts; left-anchored editorial layout; the kolam draw is the only choreography
- Respect `prefers-reduced-motion` for any animation
- Tone: "quiet software" — free, no ads, no accounts, nothing sold; no em dashes in visible copy
