# Nivalis Grid Agent Instructions

This repository is a public, sanitized mirror for AI inspection of a wardrobe catalog. Treat it as read-only derived data.

## How To Navigate

1. Start with `AI_CONTEXT.md`. It is the intended single-file reading path.
2. Read sections in this order: active overview, owned by category, decision queues, category deep dives, use-case modules, archive.
3. Use the cell IDs in embedded grid pages to discuss visible pieces quickly.
4. Use `grids/index.json` to map each local `cellId` to the stable `itemId`.
5. Use `data/catalog.json` as the structured source of truth for item metadata.
6. Use `media.publicImageUrls` in `data/catalog.json` only when a grid cell needs closer visual inspection.

## Important Concepts

- `itemId` is the stable identifier. Prefer it in final recommendations.
- `cellId` is only local to a specific grid page and can change when grids are regenerated.
- `assets/<item_id>/*.jpg` contains re-encoded public JPEG images.
- `grids/` contains regenerated visual indexes. They are meant for overview and triage, not fine-grained image inspection.
- `data/items/*.json` mirrors individual item records from the consolidated catalog.
- `AI_CONTEXT.md` is a generated visual dossier that combines selected grids, summary stats, owned-by-category summaries, decision queues, normalized use-case modules, archive, and item tables.

## Suggested Analysis Workflow

- First inspect `AI_CONTEXT.md`.
- Identify broad color, silhouette, formality, category, and use-case patterns from the active overview and category grids.
- Use decision queues for buy/replace reasoning and use-case modules for outfit reasoning.
- Then consult `data/catalog.json` for exact names, categories, scores, ownership, tags, and source links.
- Open individual `media.publicImageUrls` only for items where the grid is too small or ambiguous.
- When recommending outfits, cite stable `itemId` values and optionally mention the grid/cell used for visual reference.

## Limitations

- This repo excludes private profile notes, outfits, capsules, source Git history, local paths, and private metadata.
- Some catalog items may not have public images.
- Product images can differ in scale, pose, and background, so use grids for visual triage rather than exact fit judgments.
- The public repo should not create new catalog data. Updates are produced by the private source repo and synced here.

Primary catalog URL:

https://raw.githubusercontent.com/tilvoro-labs/nivalis-grid/codex/wardrobe-ai-context/data/catalog.json
