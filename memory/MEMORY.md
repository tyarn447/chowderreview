# Clam Chowder Review Blog — Memory

## Project Overview
Static GitHub Pages blog. No build system — raw HTML + CSS only.
Site: clamchowderreview (CNAME file present, likely a custom domain).
Author: Taylor Yarn, Security Engineer.

## Key Files
- `index.html` — homepage with review cards; add a new `.review-card` div per post
- `styles.css` — all styles; nautical theme CSS variables defined here
- `template.html` — template for restaurant review posts (has map embed)
- `template-essay.html` — template for essay/philosophy posts (no map, no rating)
- `AGENTS.md` — persona/style guide (brief)
- `CLAUDE.md` — my comprehensive working guide

## Two Post Types
1. **Restaurant Review** — uses `template.html`. Needs: location, rating, photo, Google Maps embed.
2. **Essay/Philosophy** — uses `template-essay.html`. No map, no rating, no location.

## Writing Style
- Voice: casual, fun, slightly absurd, genuinely passionate
- Audience: "mollusk friends"
- Bacon in chowder = bad. No bacon = good sign.
- Creaminess = virtue; oiliness = moral failing
- Esoteric digressions are encouraged

## Current Posts
| File | Type | Status |
|------|------|--------|
| `estella-chowder-review.html` | Review | Has lorem ipsum — needs real content |
| `pearl-station-review.html` | Review | Under construction |
| `chowder-rating-philosophy.html` | Essay | Under construction |
| `bacon-downfall-chowder.html` | Essay | Under construction |
| `cracker-modern-dilemma.html` | Essay | Under construction |

## Known Issues (not yet fixed)
- Footer copyright says 2024 in all existing post files (templates updated to 2026)
- `estella-chowder-review.html` has lorem ipsum placeholder text (git shows as modified)
- Under-construction essay posts still have the old map embed from original template — should be removed when written
