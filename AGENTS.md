# Nivalis Grid Agent Instructions

This repository is a public, sanitized mirror for AI inspection of a wardrobe catalog. Treat it as read-only derived data.

## How To Navigate

1. Start with `grids/index.md` for the visual overview.
2. Use the cell IDs in each grid page to discuss visible pieces quickly.
3. Use `grids/index.json` to map each local `cellId` to the stable `itemId`.
4. Use `data/catalog.json` as the structured source of truth for item metadata.
5. Use `media.publicImageUrls` in `data/catalog.json` only when a grid cell needs closer visual inspection.

## Important Concepts

- `itemId` is the stable identifier. Prefer it in final recommendations.
- `cellId` is only local to a specific grid page and can change when grids are regenerated.
- `assets/<item_id>/*.jpg` contains re-encoded public JPEG images.
- `grids/` contains regenerated visual indexes. They are meant for overview and triage, not fine-grained image inspection.
- `data/items/*.json` mirrors individual item records from the consolidated catalog.

## Suggested Analysis Workflow

- First inspect `grids/index.md`.
- Identify broad color, silhouette, formality, and category patterns from the grids.
- Then consult `data/catalog.json` for exact names, categories, scores, status, and source links.
- Open individual `media.publicImageUrls` only for items where the grid is too small or ambiguous.
- When recommending outfits, cite stable `itemId` values and optionally mention the grid/cell used for visual reference.

## Limitations

- This repo excludes private profile notes, outfits, capsules, source Git history, local paths, and private metadata.
- Some catalog items may not have public images.
- Product images can differ in scale, pose, and background, so use grids for visual triage rather than exact fit judgments.
- The public repo should not create new catalog data. Updates are produced by the private source repo and synced here.

Primary catalog URL:

https://raw.githubusercontent.com/tilvoro-labs/nivalis-grid/main/data/catalog.json
