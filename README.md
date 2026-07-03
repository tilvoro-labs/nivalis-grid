# Nivalis Grid

Text-only public catalog export for AI inspection.

This repository contains a sanitized wardrobe catalog: structured item metadata, product/source links, and remote product image URLs where available. It intentionally excludes source Git history, local/manual photos, personal profile notes, fit profile files, capsules, outfits, local paths, and private repository metadata.

## Files

- `data/catalog.json`: consolidated catalog with all items and aggregate stats.
- `data/items/*.json`: one sanitized item file per catalog item.
- `schema/item.schema.json`: schema used by item files.

## Current Stats

- Items: 57
- Owned items: 34
- Status counts: archived: 7, candidate_buy: 15, owned: 34, owned_buy_more: 1
- Categories: accessory, bottom, footwear, outerwear, top, underwear

## Suggested AI Prompt

Use `data/catalog.json` as the source of truth. Inspect the wardrobe catalog, identify redundancies and gaps, and suggest practical outfits or capsule changes using only the included item metadata and public product links.
