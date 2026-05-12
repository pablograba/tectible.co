# CLAUDE.md – Build Instructions for My Personal Consulting Website

**Project Overview**
I am a senior software engineer specializing in LLM-based applications and enterprise-grade error-analysis AI evaluations. 
I run a solo-founded consulting business (scaling later with high-quality technical hires) that helps mid-market CTOs adopt AI risk-free: no wasted demo budgets, no inaccurate pilots, only production-ready LLM apps with reliable evals.

Website goal:
- Personal brand site that positions me as the trusted expert on “risk-free AI adoption”.
- Generate inbound leads from CTOs (target: Book a 20-min AI Risk Audit).
- Extremely simple, clean, fast, and text-first — modeled 1:1 after https://parlance-labs.com/
- Hosted on GitHub Pages using Quarto (pure markdown + Quarto HTML).

**Design & Style Rules (copy the vibe of parlance-labs.com)**
- Minimalist, professional, no fluff.
- Lots of white space, clean typography, dark text on light background.
- Text-first (very little imagery).
- Fast loading — no animations, no heavy hero images, no carousels.
- Use Quarto’s default clean theme (try `cosmo`, `journal`, or `flatly` — keep it simple).
- Navigation bar at the top on every page.
- One clear CTA per page: “Book a 20-min AI Risk Audit” (link to Calendly later).
- Mobile-friendly by default (Quarto handles this).

**Folder Structure (create exactly this)**
/
├── _quarto.yml
├── index.qmd          ← Homepage
├── services.qmd
├── about.qmd
├── content.qmd
├── styles.css         ← optional tiny custom styles (keep minimal)
├── images/            ← only my headshot (name it headshot.jpg)
└── README.md
**1. _quarto.yml (exact config)**
```yaml
project:
  type: website

website:
  title: "Your Name | Risk-Free AI for Mid-Market CTOs"
  navbar:
    background: light
    left:
      - text: "Home"
        href: index.qmd
      - text: "Services"
        href: services.qmd
      - text: "About"
        href: about.qmd
      - text: "Content"
        href: content.qmd
  page-footer:
    left: "© Your Name Consulting 2026"
    right: 
      - icon: linkedin
        href: "YOUR_LINKEDIN"
      - icon: twitter
        href: "YOUR_X"
    center: "hello@yourdomain.com | Book a 20-min AI Risk Audit"

format:
  html:
    theme: flatly
    css: styles.css
    toc: false
```


Technical Requirements

Everything must be valid Quarto markdown.
No JavaScript beyond what Quarto provides.
Keep total page weight tiny.
Use proper headings (H1, H2) for SEO.
Add meta description in YAML frontmatter for each page.