# WelBewust × Aweris — planning workspace

A small set of self-contained, single-file web pages used to plan WelBewust's move onto the **Aweris** platform. No build step, no dependencies, no accounts — open any page in a browser or view it live via GitHub Pages.

All pages share one design system (`aweris.css`) built from the live Aweris brand tokens (warm paper, deep-blue ink, orange accent, Fraunces + Inter). A top nav links them together.

## Pages

| File | What it is | For |
|------|------------|-----|
| [`overview.html`](overview.html) | Hub — what this workspace is and what's inside | Everyone |
| [`index.html`](index.html) | **Cost calculator** — Chirp transcription + Gemini email/voice/doc costs, every figure editable and live | Massy |
| [`assistenten.html`](assistenten.html) | **Digital-assistants guide** — what runs, what's coming, what it saves (NL/EN) | Anna & Massy |
| [`compliance.html`](compliance.html) | **NEN 7510 plan** — the all-Google-Cloud move and what it does (and doesn't) do for compliance | The board |

## Design system

`aweris.css` defines the brand palette, Fraunces/Inter typography, and the shared nav/footer. It is loaded **last** in each page's `<head>`, so it also recolours the older pages' local tokens without touching their markup or logic.

Figures are sourced from Google Cloud's official pricing pages (verified July 2026).

*Working documents — not legal or financial advice.*
