# Stealth page

Single-page static site. No build step, no dependencies — open `index.html`.

## What it is

A stealth page for CatchAll. Just enough to state the thesis, tell the story, and
show it's a real company to anyone who looks us up after a conversation. It is not
meant to convince on its own. It ends with one invitation, to researchers and investors, and a mailto.

Copy and visual system follow the Series A deck ("CatchAll · Series A Draft (Team Flow)",
Oct 2026). When the deck changes, the site follows it.

## Structure

Everything is in `index.html`: inline CSS and one small script that starts the scroll animations. Font is Inter from Google Fonts.
Without JavaScript, or with reduced motion on, the page shows in its final state.

- **Hero** — the compression table: delivery, building, doing, *growth*
- **The shift** — AI took over the tasks; humans moved to watching; the bottleneck is judgment
- **What CatchAll is** — agents do the work, CatchAll makes the decisions; the context layer (carried over from the previous site)
- **How it works** — the loop diagram, with the deck's verbs (call it, do it, grade it, learn it) on its stages.
  States: works today (grey outline), being built (dashed orange), our research (solid orange)
- **Why it's hard** — a math problem, not a prompt: Cause, Confidence, Record, each paired with the research approach from the previous site
- **Team** — founder stats, founders, Think Tank, also building with us
- **Close** — marketing today, every decision next
- **Invite** — researchers & engineers, investors; one Get in touch button

## Visual system

| Token | Value | Use |
|---|---|---|
| `--night` | `#101214` | Dark sections |
| `--cream` | `#f2efe7` | Light sections |
| `--ember` | `#fe6a34` | Accent on dark, closing band |
| `--rust` | `#c34519` | Accent on cream, the one filled card |
| `--ash` / `--stone` | `#9b978e` / `#5e5a53` | Muted text on dark / cream |

Sections alternate dark and cream. Each opens with the deck's orange question.
Wordmark is `CatchAll.` with an orange dot.

## Content rules

- Only claims the deck states as fact. Anything bracketed or "confirm" in the deck stays off.
- Advisors are off the public page until leadership decides.
- No business model, pricing or raise details.

Earlier treatments (pre-deck) are kept in `variants/` and in git history.

## Before this goes live

- [ ] Confirm `hello@catchall.com` is a real, monitored address
- [ ] Leadership sign-off on the team list and copy
- [ ] Move this repo to the venture's GitHub org
