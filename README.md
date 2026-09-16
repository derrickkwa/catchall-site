# Stealth page

Single-page static site. No build step, no dependencies — open `index.html`.

## What it is

A pre-launch page for an applied AI research company building a judgment layer,
starting in marketing. Two audiences: research/engineering recruits, and investors.
One email CTA. No company name on the page by design — the name is unsettled, and
shipping nameless keeps that decision open.

## Structure

Everything is in `index.html`: inline CSS, inline SVG, one inline script.
Fonts are Instrument Sans and JetBrains Mono from Google Fonts.

- **Hero** — canvas field of cells completing, with judgment cells left unfilled
- **The gap** — Applied AI / Judgment / AI research, the middle one unclaimed
- **The hinge** — a general model has no priors but the internet's
- **The judgment engine** — context layer and research, plus the loop diagram
- **Per-business fit** — shared structure, local fit
- **Beachhead** — marketing first, then every function
- **Invitation** — researchers and investors, one mailto

## Colour system

Three states, used consistently in the diagram and the build columns:

| State | Token | Meaning |
|---|---|---|
| Solved | `--rule` | Largely works today (execution) |
| Being built | `--cool` | The context layer |
| Open | `--brass` | The judgment problem |

## Before this goes live

- [ ] Replace the placeholder email (`hello@example.com`)
- [ ] Confirm the thesis framing with Alex
- [ ] Decide the name and register a domain
- [ ] Move this repo to the venture's GitHub org
