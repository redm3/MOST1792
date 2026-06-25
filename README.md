# MOST 1792 — The Sorak Family Estate

Brand kit for a premium Croatian plum brandy (šljivovica) from the **Sorak family** orchard in
**Ličko Petrovo Selo, Lika** — beside the old stone bridge over the Korana river, in the village
founded in **1792**.

> *Most* means "bridge" in Croatian — so the engraved stone bridge is the logo — and 1792 is the
> founding year of the village. Aesthetic: cream · navy · antique gold; engraved bridge; gold plum
> crest; crowned Croatian (šahovnica) heritage seal.

## What's here

| Path | What it is |
|---|---|
| [`labels/most-1792-front.svg`](labels/most-1792-front.svg) | Front bottle label |
| [`labels/most-1792-back.svg`](labels/most-1792-back.svg) | Back label (product info, producer, barcode) |
| [`assets/`](assets/) | Reusable artwork: `bridge-engraving.svg`, `plum-crest.svg`, `heritage-seal.svg`, `crown.svg` |
| [`site/`](site/) | One-page brand website (`index.html` + `styles.css`) matching the labels |
| [`BRAND-BIBLE.md`](BRAND-BIBLE.md) | Chosen direction (MOST 1792) + alternate concepts, back stories, palettes, SKUs |
| [`LAUNCH-CHECKLIST.md`](LAUNCH-CHECKLIST.md) | Production, EU/Croatia excise + trademark, labeling law, packaging, pricing, route-to-market |

## Viewing the site locally

```bash
python -m http.server 4321 --directory .
# then open http://localhost:4321/site/index.html
```

The labels are SVGs that embed the pieces in `assets/` via relative paths — view them through the
local server (`http://localhost:4321/labels/most-1792-front.svg`) so the artwork resolves.

## Notes before printing / launching

- The bridge is a faithful **vector stand-in** — commission a hand-drawn engraving of the real
  Sorak bridge for the final artwork.
- Label SVGs leave placeholder values (`LOT`, barcode) — fill mandatory legal text (ABV, volume,
  lot, producer, allergen/excise) before printing. See `LAUNCH-CHECKLIST.md` §4.
- **Trademark:** file the stylised MOST 1792 lockup (crown + wordmark + bridge + crest) at
  EUIPO/DZIV; the "Sorak" name adds a second distinctive layer.

---
*Concept brand kit. Enjoy responsibly.*
