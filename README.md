# vishrut-portfolio

Personal portfolio. One static `index.html`, no build step. Theme: trading terminal, with me as the ticker `VTLA` and projects as "holdings".

## Deploy
1. Create the repo `vtalla-hq/portfolio` and push `index.html` + `resume.pdf`.
2. Import it in Vercel with Framework Preset "Other". There's no build command.

## Before shipping (for Claude Code)
- [x] Add `resume.pdf` to the repo root. The Resume buttons link to it.
- [x] Add live URLs for market-sql, MacroPulse AI and Trump vs S&P 500.
- [ ] Fill in the "In the pipeline" row (`.pipe`) once the finance project is public.
- [x] Check that every GitHub repo linked here is public, since private repos 404 for recruiters.
- [ ] Optional: custom domain, OG image (`og.png`, 1200x630), favicon.

## Editing
- Projects are the `<details class="row">` blocks under `#holdings`. Copy one to add a project.
- The ticker tape text is the `tape` array in the script.
- Colors are CSS variables in `:root`.
- Keys 1–4 jump to sections.
