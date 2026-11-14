# My Studio

A shelf of interactive HTML pages: courses, instruments, tools and family projects. Each one is a single self-contained file that runs in any browser.

## What's here

| Piece | Folder | What it is |
| --- | --- | --- |
| Biology From Zero | `biology-from-zero/` | A course in eight sittings |
| Color Theory Studio | `color-theory-studio/` | Labs for wheels, mixing, value, contrast and palettes |
| Meet Your Kernel | `meet-your-kernel/` | A visual guide to the operating system kernel |
| Power BI Field Course | `power-bi-field-course/` | Nine self-paced Power Query and Power BI modules |
| By Ear Piano | `by-ear-piano/` | Learn songs by number, with an ear gym |
| Middle C Piano Lab | `middle-c-piano-lab/` | Piano theory you can hear, see and play |
| Margin Grain Bridge | `margin-grain-bridge/` | A margin reconciliation workbook |
| The Little Book | `little-book/` | Franklin's virtue chart and daily page |
| Crazy Forts Build Book | `crazy-forts-build-book/` | Six fort plans with 3D diagrams |

## How it's laid out

```
index.html            the front page (a gallery of everything below)
thumbs/<folder>.jpg   one screenshot per piece, shown on the front page
<folder>/index.html   one folder per piece
```

## Seeing it as a website

Turn on GitHub Pages once: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save**.
A minute or two later the studio is live at `https://<your-username>.github.io/my-studio/`.

## Adding a new piece

1. Make a folder with a short lowercase name, such as `my-new-thing/`, and save the page inside it as `index.html`.
2. Add a screenshot at `thumbs/my-new-thing.jpg` (1200 × 750 works well).
3. Open the root `index.html` and add one line to the `WORKS` list near the bottom.

## Good to know

- Progress and notes in these pages are saved in the browser you use, on that device only. Nothing is sent anywhere.
- The Little Book saves to your private Claude storage when opened on claude.ai. The copy here saves to the browser instead, so the two do not share entries.
