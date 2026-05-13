# Relien Property Maintenance — Website

Single-page website for Relien Property Maintenance LLC (Andrew Wenzler, Birmingham AL).

## Files
- `index.html` — all content and structure
- `styles.css` — all styling
- `images/` — photos and logo

## Adding photos

The site currently shows colored placeholders where photos go. To swap in real images, drop these files into `/images/` (filenames must match):

| File | Used for |
|------|----------|
| `logo.png` | Header + footer logo (RELIEN wordmark) |
| `hero.jpg` | Hero section, right of headline (Andrew or work-in-progress shot) |
| `about.jpg` | About section, "Dedicated to Reliable…" (tool-belt or workshop shot) |
| `service-repairs.jpg` | Services card 1 — Repairs & Maintenance |
| `service-improvements.jpg` | Services card 2 — Improvements |
| `service-emergency.jpg` | Services card 3 — Emergency Repairs |

Once dropped in, refresh the browser — they appear automatically.

## Viewing locally

Open `index.html` in a browser, or run a local server from this folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Editing copy

All text lives in `index.html`. Search for the section you want to change (e.g. `<!-- ============ FAQ ============ -->`) and edit between the tags.
