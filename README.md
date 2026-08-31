# ai-coc

**AI Code of Conduct** — a nohello.net-style page of house rules for
working with AI on a team. Terse, shareable, link straight to a rule
mid-conversation. Filterable by theme, and every rule (or the whole
page) copies to markdown with one click.

Live in `index.html` (no build step, no dependencies beyond a Google
Fonts stylesheet — just open it or serve it statically).

## Rules so far

01. **Own your AI-generated code** (craft)
02. **Communicate like a human** (comms)
03. **Never paste what you can't take back** (data)
04. **Say when it's AI** (comms)
05. **Verify before you ship it** (craft)
06. **Agents get a leash** (agents)
07. **AI doesn't get a vote on people** (people)
08. **Don't wear someone else's face** (people)

More get added as new edge cases come up. Open an issue to propose one.

## Deploying

This is a single static HTML file. Auto-deploys to GitHub Pages via
`.github/workflows/deploy-pages.yml` on every push to `main` — see
that PR for the one-time "Settings → Pages → Source: GitHub Actions"
toggle required to enable it.
