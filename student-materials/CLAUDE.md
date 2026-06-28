# Student Materials — CLAUDE.md

This repo contains vocab treatment HTML files for Terence Collins' Business English coaching students. Files are hosted on GitHub Pages and shared with students via URL — primarily WeChat, but the link works anywhere (email, QQ, SMS, or any other channel).

---

## Repo Identity

- **GitHub Pages base URL:** `https://lometogo.github.io/student-materials/`
- **Local path:** `~/Library/CloudStorage/OneDrive-Personal/Documents/ClaudeProjects/student-materials/`
- **URL formula:** `https://lometogo.github.io/student-materials/[filename].html`
- **Branch:** `main`

---

## Git Push Workflow

Always use Terminal. Four commands in sequence:

```bash
git add .
git commit -m "description of what changed"
git push origin main
```

---

## Design System

Every vocab treatment HTML file must use this design system consistently:

- **Header:** Dark navy (`#1a2744`)
- **Body background:** Warm cream (`#fdf6e3`)
- **Definition panel:** Dark background with gold accents
- **Fonts:** Playfair Display (headings), Source Serif 4 (body) — loaded from Google Fonts
- **Output:** Single self-contained HTML file — all CSS inline, no external dependencies except Google Fonts

---

## Vocab Treatment Conventions

### Verbatim Rule
Reproduce the full article text word for word. No omissions, no condensing, no summarizing. This is non-negotiable.

### What to Remove
Strip newsletter calls-to-action embedded in the article body (e.g. "Join X others on WhatsApp") that are not part of the article text itself.

### Vocabulary Marking
- Bold every target vocabulary word at its **first appearance** only
- Mark it with a superscript number: **pivotal**¹
- The superscript must be a clickable anchor link jumping down to that word's definition
- Each definition entry must have a return link (↑ back) jumping back up to the word in the article

### Definition Format
All on one line, word and synonyms bolded:

**Word**: (phonetic respelling in plain English, e.g. "kuh-RIK-yuh-lum" — NOT IPA symbols) - definition; **synonyms**. Example sentence.

### Vocabulary Selection
Target words above 6th grade US reading level. Use the two-pass workflow:
- **Pass 1:** Generate candidate word list for Terence's review and approval
- **Pass 2:** Build the full HTML after word list is confirmed

---

## Author's Comments (Optional — Pass 3)

Terence may insert his own commentary at specific locations in any article. Format each comment block as follows:

- Indented block, visually distinct from the article body
- Light amber or gold background with a left border accent
- Label: **Author's Note** in small caps above the comment
- Comment text in bold
- Placed immediately after the paragraph or sentence Terence specifies

Terence will indicate insertions like this:
- After paragraph 2: **Comment text here.**
- After the sentence ending "…word or phrase": **Comment text here.**

Output the full updated HTML file with all previous formatting intact.

---

## Key Rules

- Never omit or condense article text — reproduce verbatim always
- Never use IPA phonetic symbols — use plain English respelling only
- Never add external CSS or JS dependencies beyond Google Fonts
- Never create new files without discussing with Terence first
- Always confirm the word list with Terence before building the HTML (Pass 1 before Pass 2)
- Prefer CLI over MCP when both can accomplish the same task

---

## About Terence

- Business English and interview preparation coach based in Guangzhou, China
- 25+ years senior corporate experience: IBM, Fujitsu, Huawei and others
- Students are Chinese professionals pursuing multinational roles
- Primary sharing channel: WeChat
- WeChat ID: Chiangmai3047
