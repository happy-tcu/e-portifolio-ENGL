# E-Portfolio — Happy Herman

A simple, static e-portfolio for my writing course at TCU.

**Live site:** https://happy-tcu.github.io/e-portifolio-ENGL/

## Pages

| Page | File | Status |
| --- | --- | --- |
| About | `index.html` | Live |
| Genre Analysis Reflection | `genre-analysis.html` | Coming soon |
| Research Report Assignment Reflection | `research-report.html` | Coming soon |
| Visual Argument Assignment | `visual-argument.html` | Coming soon |
| Critical Reflection | `critical-reflection.html` | Coming soon |
| Reading Responses | `reading-responses.html` | Coming soon |

## Rationale

I wanted the portfolio to feel like a *reading room* more than a résumé — a place where the writing leads and the design quietly steps aside. A few choices follow from that:

- **One page per assignment.** Each piece of writing gets its own URL and its own room to breathe. Putting everything on a single scroll would have flattened the work into a feed; separate pages let me reflect on each genre on its own terms, the way the assignments themselves ask me to.
- **Serif typography on a cream background.** The default of the modern web is sans-serif on white — fine for a SaaS landing page, less fine for sustained reading. Serifs and a warm background invite you to slow down, which is what an e-portfolio is for.
- **Plain HTML and CSS, no framework.** The whole site is something I can read top-to-bottom in a few minutes. I wanted the portfolio to be transparent about what it is: text and a little structure. No build pipeline means no surprises and no version drift over the semester.
- **Coming-soon pages that say something.** Empty placeholders feel like broken promises. Each unfinished page has a small in-character note — a typewriter prompt, a progress bar, an ASCII sketch — so a visitor lands on *something* rather than nothing, and so I have to face the page every time I open it.
- **The repo is public.** Writing is revision, and the commit history of this repo is, in a way, a second reflection running alongside the assignments themselves.

## Stack

Plain HTML and CSS — no build step, no framework. Hosted on GitHub Pages from the `main` branch.

## Editing

1. Open the page you want to edit (e.g. `genre-analysis.html`).
2. Replace the `<div class="coming-soon">…</div>` block with the real content.
3. Commit and push:

   ```bash
   git add .
   git commit -m "Add genre analysis reflection"
   git push
   ```

GitHub Pages rebuilds in ~30 seconds.

## Local preview

```bash
python3 -m http.server 8765
```

Then open <http://localhost:8765/>.

## Contact

- Email: h.niyorurema@tcu.edu
- LinkedIn: [happyh](https://linkedin.com/in/happyh/)
