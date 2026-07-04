# Nivalis Grid

Public catalog export for AI inspection.

This repository mirrors selected sanitized artifacts from a private wardrobe catalog. It contains structured item metadata, product/source links, remote product image URLs where available, re-encoded public image assets, and regenerated visual grids. It intentionally excludes source Git history, personal profile notes, fit profile files, capsules, outfits, local paths, and private repository metadata.

## Files

- `data/catalog.json`: consolidated catalog with all items, aggregate stats, and image URLs.
- `data/items/*.json`: one sanitized item file per catalog item.
- `AI_CONTEXT.md`: single-file visual and structured context for AI review.
- `assets/<item_id>/*.jpg`: public JPEG images associated with items.
- `grids/index.md`: visual grid index for quick AI overview.
- `grids/index.json`: machine-readable map from grid cell IDs to item IDs and image paths.
- `schema/item.schema.json`: schema used by item files.

## Current Stats

- Items: 87
- Owned items: 66
- Public images: 136
- Items with public images: 83
- Status counts: archived: 6, candidate_buy: 15, owned: 66
- Ownership counts: archived: 6, not_owned: 15, owned: 66
- Tag counts: archived: 6, buy_more: 1, candidate_buy: 15, maybe_replace: 1
- Categories: accessory, bottom, footwear, outerwear, top, underwear

## Suggested AI Prompt

First inspect `AI_CONTEXT.md` for the single-file overview. Use embedded grid pages for visual triage, cite stable `itemId` values from the tables, and only open individual `media.publicImageUrls` when a grid cell needs closer inspection:

https://raw.githubusercontent.com/tilvoro-labs/nivalis-grid/main/data/catalog.json
