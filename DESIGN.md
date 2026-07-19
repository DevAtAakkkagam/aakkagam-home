<!-- SEED: re-run /impeccable document once there's code to capture the actual tokens and components. -->

---
name: Aakkagam
description: Landing page for a small workshop for quiet software, indigo ground and rice-flour line.
---

# Design System: Aakkagam

## 1. Overview

**Creative North Star: "Ink and Rice Flour"**

A kolam drawn in rice flour on indigo-dark ground before dawn: one committed color holding the whole surface, one pale line doing all the work. The system is precise, minimal, and warm; it borrows the typographic quiet of iA.net and the material honesty of Muji, then roots itself with a single meaningful mark rather than decoration. The page is the portfolio: craft is demonstrated, never claimed.

This system explicitly rejects the Awwwards showreel (motion over meaning), the SaaS landing template, corporate agency polish, and ethnic kitsch. Nothing scroll-jacks, nothing glows, nothing sells.

**Key Characteristics:**
- Committed color: deep indigo carries 30–60% of the surface; rice-cream line work on top
- Serif display + sans body; hierarchy through scale and weight, not ornament
- One signature motion moment (the kolam drawing itself); everything else restrained
- Generous whitespace; short, concrete copy

## 2. Colors

One deep indigo ground, one rice-flour cream, and little else.

### Primary
- **Deep Indigo** [to be resolved during implementation]: the ground itself; a committed surface color, not an accent. Dark, slightly warm, ink-like; never neon, never Linear-glow.

### Neutral
- **Rice-Flour Cream** [to be resolved during implementation]: line work, display type, the kolam stroke. The pale voice on the indigo ground.
- **Dimmed Cream** [to be resolved during implementation]: secondary text and dots; the cream stepped down, same hue.

### Named Rules
**The Committed Ground Rule.** Indigo is the surface, not a decoration on white. If the page reads as a white site with indigo accents, the strategy has collapsed; rework it.
**The Two Voices Rule.** Indigo and cream carry the page. Any third color must earn its place per project card, or not exist.

## 3. Typography

**Display Font:** [serif, to be chosen at implementation]
**Body Font:** [humanist sans, to be chosen at implementation]
**Tamil Font:** [serif Tamil face, to be chosen at implementation]

**Character:** Editorial and classical without stiffness; the serif speaks in headings, the sans stays legible and warm underneath. iA-grade precision in measure and rhythm.

### Hierarchy
- **Display**: wordmark and page title only; scale ratio ≥1.25 between steps.
- **Body**: max measure 65–75ch; unhurried line-height.
- **Label**: small, for link destinations and footer.

### Named Rules
**The One Serif Moment Rule.** The serif appears at display sizes and card titles; body text is always the sans. No serif body paragraphs.

## 4. Elevation

Flat by default. Depth, where needed, comes from tonal layering of the indigo ground (a raised surface is the same hue, one step lighter), never from drop shadows. Motion is the one signature moment: the kolam line drawing itself once on load, honored by `prefers-reduced-motion`.

## 5. Components

[No components exist yet; this section is populated on the first scan-mode run.]

## 6. Do's and Don'ts

### Do:
- **Do** let indigo carry the surface (30–60% minimum); cream does the line work.
- **Do** keep the kolam as the single culturally rooted mark, drawn once, meaningfully.
- **Do** respect `prefers-reduced-motion` on every animation, the kolam draw included.
- **Do** keep copy short and concrete: "no ads, no accounts, nothing sold" is the register.

### Don't:
- **Don't** build an Awwwards showreel: no scroll-jacking, no WebGL set pieces, no motion over meaning.
- **Don't** produce a SaaS landing template: hero + feature grid + CTA buttons + gradient blobs.
- **Don't** produce corporate agency polish: stock-photo sheen, "we deliver solutions" tone, case-study carousels.
- **Don't** use ethnic kitsch: temple borders, gold-on-maroon, Tamil motifs as decorative wallpaper.
- **Don't** use side-stripe borders, gradient text, glassmorphism, or identical card grids.
