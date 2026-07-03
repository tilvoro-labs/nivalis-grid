# Nivalis Grid

Public catalog export for AI inspection.

This repository mirrors selected sanitized artifacts from a private wardrobe catalog. It contains structured item metadata, product/source links, remote product image URLs where available, re-encoded public image assets, and regenerated visual grids. It intentionally excludes source Git history, personal profile notes, fit profile files, capsules, outfits, local paths, and private repository metadata.

## Files

- `data/catalog.json`: consolidated catalog with all items, aggregate stats, and image URLs.
- `data/items/*.json`: one sanitized item file per catalog item.
- `assets/<item_id>/*.jpg`: public JPEG images associated with items.
- `grids/index.md`: visual grid index for quick AI overview.
- `grids/index.json`: machine-readable map from grid cell IDs to item IDs and image paths.
- `schema/item.schema.json`: schema used by item files.

## Current Stats

- Items: 57
- Owned items: 35
- Public images: 62
- Items with public images: 36
- Status counts: archived: 7, candidate_buy: 15, owned: 34, owned_buy_more: 1
- Categories: accessory, bottom, footwear, outerwear, top, underwear

## Suggested AI Prompt

First inspect `grids/index.md` for a quick visual overview. Use the grid cell IDs to reference visible pieces, then consult `data/catalog.json` for the stable `itemId`, metadata, and individual `media.publicImageUrls` when you need detail:

https://raw.githubusercontent.com/tilvoro-labs/nivalis-grid/main/data/catalog.json
