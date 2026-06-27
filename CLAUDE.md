

# Landing Page Builder — CLAUDE.md

## Project Purpose

A single-page landing page for Terrance Collins' Business English teaching services, targeting Chinese business professionals (primarily businesswomen). Built with plain HTML, CSS, and JavaScript — no frameworks or build tools.

## Tech Stack

- **HTML** — single `index.html`, all content and structure
- **CSS** — custom properties, flexbox/grid, mobile-first responsive; all styles in `style.css`
- **JavaScript** — vanilla JS for smooth scroll and fade-in animations; `main.js`

## File Structure

```
Landing Page Builder/
├── CLAUDE.md
├── index.html       # Full single-page site
├── style.css        # All styles
├── main.js          # Smooth scroll + scroll animations
└── terence.png      # Profile photo (circular crop in hero)
```

## Design

- **Color palette**: Navy (`#1a2744`), deep teal accent (`#2a7d6f`), green CTA (`#2e9e4f`)
- **Font**: Inter (Google Fonts)
- **Style**: Clean, minimal, lots of whitespace, professional but warm
- **Photo treatment**: Circular crop in hero section (right side)
- **Mobile-first**: Stacks to single column on small screens

## Page Sections (top to bottom)

1. **Nav** — sticky, logo + links (About, Services, Reviews, Contact)
2. **Hero** — headline, subheadline, green CTA button, Ren Zhengfei quote, circular photo
3. **Stats bar** — dark navy band: 25+ years, IBM·Fujitsu·Huawei, 10 countries
4. **About** — Terrance's background and teaching philosophy
5. **Services** — 4 cards: Meetings & Negotiations, Interviews, Emails & Presentations, 1-on-1 Coaching
6. **Testimonials** — 3 cards with teal left border
7. **Contact** — centered CTA + WeChat ID (Chiangmai3047)
8. **Footer** — dark navy, copyright

## Key Copy Decisions

- Headline: "Business English Taught by a *Real* Business Professional"
- Subheadline: "No textbooks. No classroom English. We tackle real interviews, real meetings, and real business life, the English your career actually needs."
- CTA button: "Book a FREE 15-Minute WeChat Call" — green background, black font
- WeChat ID: Chiangmai3047
- Hero quote: Ren Zhengfei, Founder Huawei

## Tool Usage Preferences

Prefer CLI over MCP when both can accomplish the same task.
CLI tools use significantly fewer tokens and are more reliable.
Only use MCP when CLI cannot do the job (e.g., auth-gated APIs,
multi-user workflows, or services with no CLI equivalent).

## Writing Style

Use em dashes minimally. Prefer commas, periods, or rewritten sentences instead.

## What to Avoid

- No CSS frameworks (Bootstrap, Tailwind)
- No JavaScript frameworks (React, Vue)
- No build steps or package managers
- Keep all changes in the existing three files — do not add new files without discussion
