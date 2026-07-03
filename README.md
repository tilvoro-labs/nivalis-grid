# Nivalis Grid

Public catalog export for AI inspection.

This repository contains a sanitized wardrobe catalog: structured item metadata, product/source links, remote product image URLs where available, and re-encoded public image assets for visual outfit reasoning. It intentionally excludes source Git history, personal profile notes, fit profile files, capsules, outfits, local paths, and private repository metadata.

## Files

- `data/catalog.json`: consolidated catalog with all items, aggregate stats, and image URLs.
- `data/items/*.json`: one sanitized item file per catalog item.
- `assets/<item_id>/*.jpg`: public JPEG images associated with items.
- `schema/item.schema.json`: schema used by item files.

## Current Stats

- Items: 57
- Owned items: 34
- Public images: 62
- Items with public images: 36
- Status counts: archived: 7, candidate_buy: 15, owned: 34, owned_buy_more: 1
- Categories: accessory, bottom, footwear, outerwear, top, underwear

## Suggested AI Prompt

Use `data/catalog.json` as the source of truth. Inspect the wardrobe catalog and the linked `media.publicImageUrls`, identify redundancies and gaps, and suggest practical outfits or capsule changes using the included item metadata and images.
