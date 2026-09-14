# Hi, I'm Harry.

Product-minded builder turning awkward real-world problems into useful, accessible products across software, data, AI and hardware.

I work at the intersection of healthcare and product delivery, and outside of that I build things that fix annoyingly specific problems I actually have — a scraper for NHS board papers, an accessible colour-palette tool, a companion device that sits on my desk. I'd rather ship something small and honestly-documented than something impressive-sounding and untested.

## What I build

- **Practical products** — tools built to solve one real problem well, like a group game-night planner or a duck-race decision randomizer.
- **Accessible & data tools** — WCAG-compliant colour generation, NHS board-paper scraping, and cost-modelling calculators for healthcare decision-makers.
- **Creative software** — small, emotionally-considered experiences, like a "write it and burn it" expressive-writing ritual.
- **Hardware** — porting open firmware to new physical boards, with the engineering and constraints documented, not just the result.

## Featured projects

**[WhatShouldWePlay](https://github.com/HazzJC/WhatShouldWePlay)** — friend groups waste more time deciding what to play than actually playing; this matches everyone's availability and game preferences into an actual plan. [Live demo](https://what-should-we-play-chi.vercel.app) · 163 automated tests, green CI.

**[Ritual](https://github.com/HazzJC/writeitdownripitup)** — counsellors often suggest writing a letter you'll never send; this gives that ritual a screen, then burns what you wrote. [Live demo](https://ritual.harryjameschapman.com) · privacy claim ("nothing is saved or sent") verified by code review and live network capture, not just asserted.

**[Accessible Palettes](https://github.com/HazzJC/AccessiblePalettesWCAGColourPaletteGenerator)** — most palette generators don't check contrast at all; this generates 3–16 colour swatches and validates them against real WCAG AA/AAA thresholds. [Live tool](https://hazzjc.github.io/AccessiblePalettesWCAGColourPaletteGenerator/).

**[NHS Evidence Scraper](https://github.com/HazzJC/NHSTrustPaperScraper)** — NHS trust board papers are scattered across dozens of separate sites with no unified index; this crawls and indexes them, with rate-limiting and retry handling. AI-assisted features exist in the codebase and are clearly labelled experimental/untested, not presented as production-ready.

**[Claude Desktop Buddy — Waveshare port](https://github.com/HazzJC/claude-desktop-buddy-waveshare-1-85c)** — porting Anthropic's open Claude Desktop Buddy firmware to a round 360×360 ESP32-S3 display meant a new board driver, remapped touch controller, and a square UI re-centred into a round frame. Upstream vs. original work is documented commit-by-commit.

**[Devices Over Time](https://github.com/HazzJC/DevicesOverTime)** — a visual, interactive timeline of my own device history, built to be genuinely browsable rather than a static list. [Live site](https://devices-over-time.pages.dev).

## How I work

- **Constraint-led decisions** — I document *why* something was built a certain way (e.g. why Ritual has no server and no save feature), not just what it does.
- **Rapid validation over polish-first** — ship something real, then check the claims hold up. Several of the projects above were re-verified from scratch (privacy claims tested against actual network traffic, contrast maths checked against the real WCAG formula) rather than taken on faith from their own README.
- **Accessibility by default** — from WCAG-validated colour tooling to plain, honest UI copy.
- **Privacy-conscious** — the tools that handle sensitive personal content (expressive writing, NHS-adjacent data) are built to keep as little as possible, and I try to prove that rather than just claim it.
- **Honest about limitations** — untested features get labelled untested. Dead links get fixed, not left. If something doesn't have a test suite yet, the README says so instead of implying otherwise.

## Interested in

Technical product roles, implementation and delivery, innovation teams, digital transformation, and health-tech specifically — where "does this actually work for the person using it" matters as much as the roadmap.

## Elsewhere

[harryjameschapman.com](https://harryjameschapman.com)
