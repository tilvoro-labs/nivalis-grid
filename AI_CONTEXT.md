# AI Wardrobe Context

Generated dossier for AI inspection of the wardrobe catalog. Regenerate this file instead of editing it by hand.

## How To Use

1. Start with the overview and category grids to understand silhouette, color, category balance, and visible duplicates.
2. Use stable `itemId` values in reasoning and final recommendations. Grid `cellId` values are only local to one grid page.
3. Treat `Owned By Category`, `Decision Queues`, and `Use-Case Modules` as the main reasoning surfaces.
4. Open the full grid index or individual images only when the embedded overview is too small or ambiguous.
5. Archived items are historical context. Do not use them in outfit recommendations unless explicitly requested.

- Structured catalog: [data/catalog.json](data/catalog.json)
- Full visual grid index: [grids/index.md](grids/index.md)
- Grid pages: `71`
- Grid cells: `594`
- Max cells per grid page: `16`

## Snapshot

- Items: `87`
- Owned: `66`
- Candidate/not owned: `15`
- Archived: `6`
- Maybe replace: `1`
- Buy more: `1`
- Active items without this context's image field: `0`
- Ownership: owned: 66, not_owned: 15, archived: 6
- Categories: top: 30, bottom: 18, outerwear: 15, footwear: 13, accessory: 9, underwear: 2
- Presentation modules: Urban: 22, Formal/Social: 14, Outdoor/Rain: 13, Thermal/Cold: 10, Active/Bike: 8, Hot/Water: 8, Sleep/Indoor: 4, Laundry/Base: 2
- Tags: candidate_buy: 15, archived: 6, buy_more: 1, maybe_replace: 1
- Color families: dark: 48, neutral: 26, earth: 19, graphic: 6, bright: 3

## Presentation Strategy

The source catalog keeps granular fields such as `category`, `subcategory`, raw `module`, `status`, `ownership`, and `tags`. This context intentionally presents them in a smaller decision-oriented hierarchy:

1. Active visual overview.
2. Owned wardrobe by physical category.
3. Candidate, replacement, and buy-more queues.
4. Category deep dives for visual comparison.
5. Normalized use-case modules for outfit reasoning.
6. Archive at the end.

This avoids making tiny one-item subcategories the primary navigation layer while preserving exact source metadata in the tables.

## Public Mirror Scope

This public file is generated from sanitized mirror data. It excludes private profile files, source Git history, local paths, outfits, capsules, and private repository metadata. Treat it as read-only context for inspection and recommendations.

## Active Visual Overview

### Active Items Overview p1/6

![overview/active-items-p01](grids/overview/active-items-p01.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `gloves_uniqlo_black_touchscreen_01` | UNIQLO luvas pretas touchscreen | Gloves |  |
| B01 | `scarf_plaid_black_beige_01` | Cachecol xadrez preto/bege | Scarf |  |
| C01 | `socks_aztec_technical_grey_01` | AZTEC meia técnica cinza | Socks |  |
| D01 | `socks_quechua_lightgrey_worn_01` | Meia técnica cinza clara gasta | Socks |  |
| A02 | `socks_black_fuzzy_sleep_01` | Meias pretas felpudas para frio | Socks |  |
| B02 | `socks_cns_modal_social_01` | Meias sociais modal CNS | Socks |  |
| C02 | `socks_decathlon_hiking_01` | Meias técnicas hiking Decathlon | Socks |  |
| D02 | `socks_mountain_warehouse_melange_blue_01` | Mountain Warehouse Melange Walking Socks azul | Socks |  |
| A03 | `tie_navy_social_01` | Gravata social navy | Tie |  |
| B03 | `pants_uniqlo_ultra_stretch_active_jogger_darkgrey_01` | UNIQLO Ultra Stretch Active Jogger Pants dark gray | Active jogger | candidate_buy |
| C03 | `shorts_uniqlo_ultra_stretch_active_5in_black_01` | UNIQLO Ultra Stretch Active Shorts 5in black | Active shorts | candidate_buy |
| D03 | `shorts_black_gym_01` | Shorts preto de academia | Active shorts |  |
| A04 | `baselayer_uniqlo_heattech_leggings_black_01` | UNIQLO HEATTECH legging térmica preta | Base layer bottom |  |
| B04 | `shorts_cycling_padded_black_01` | Shorts de ciclismo preto com forro | Cycling shorts |  |
| C04 | `pants_tailored_beige_wedding_01` | Calça social bege de casamento | Dress pants |  |
| D04 | `pants_tailored_black_old_01` | Calça social preta alfaiataria antiga | Dress pants |  |

### Active Items Overview p2/6

![overview/active-items-p02](grids/overview/active-items-p02.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `pants_rei_sahara_convertible_taupe_01` | REI Co-op Sahara Convertible Pants | Hiking convertible pants |  |
| B01 | `pants_uniqlo_airism_stretch_jogger_beige_01` | UNIQLO AIRism / Stretch jogger bege | Jogger pants |  |
| C01 | `pants_uniqlo_ultra_stretch_tall_beige_01` | UNIQLO Ultra Stretch Pants Tall beige | Pants | candidate_buy |
| D01 | `pants_uniqlo_ultra_stretch_black_01` | UNIQLO Ultra Stretch Pants black | Pants |  |
| A02 | `pants_uniqlo_airism_stretch_darkgrey_01` | UNIQLO Ultra Stretch Pants dark gray | Pants |  |
| B02 | `pants_uniqlo_ultra_stretch_olive_01` | UNIQLO Ultra Stretch Pants olive | Pants |  |
| C02 | `pants_uniqlo_ultra_stretch_dry_ex_tapered_beige_01` | UNIQLO Ultra Stretch DRY-EX Tapered Pants | Performance tapered pants | candidate_buy |
| D02 | `shorts_uniqlo_stretch_easy_beige_01` | UNIQLO Stretch Easy Shorts beige | Shorts | candidate_buy |
| A03 | `pants_renner_flannel_plaid_01` | Calça flanela xadrez Renner | Sleep pants |  |
| B03 | `shorts_taco_walkshort_flex_beige_01` | TACO Walkshort Flex bege | Walkshort |  |
| C03 | `sneaker_velluti_everyday_brown_01` | Velluti Everyday sapatênis marrom | Casual sneaker |  |
| D03 | `flipflop_havaianas_01` | Havaianas | Flip-flop |  |
| A04 | `boots_timberland_mt_maddsen_wp_brown_01` | Timberland Mt. Maddsen Mid Waterproof Hiking Boot | Hiking boot |  |
| B04 | `shoes_cns_austin_oxford_17358_01` | CNS Austin Oxford social | Oxford shoe |  |
| C04 | `slippers_lightweight_01` | Pantufas leves | Slippers |  |
| D04 | `shoes_democrata_dune_hisoft_298201_black_01` | Democrata Dune Hi-Soft 32 preto | Smart casual derby |  |

### Category: accessory p1/1

![category/accessory-p01](grids/category/accessory-p01.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `gloves_uniqlo_black_touchscreen_01` | UNIQLO luvas pretas touchscreen | Gloves |  |
| B01 | `scarf_plaid_black_beige_01` | Cachecol xadrez preto/bege | Scarf |  |
| C01 | `socks_aztec_technical_grey_01` | AZTEC meia técnica cinza | Socks |  |
| D01 | `socks_quechua_lightgrey_worn_01` | Meia técnica cinza clara gasta | Socks |  |
| A02 | `socks_black_fuzzy_sleep_01` | Meias pretas felpudas para frio | Socks |  |
| B02 | `socks_cns_modal_social_01` | Meias sociais modal CNS | Socks |  |
| C02 | `socks_decathlon_hiking_01` | Meias técnicas hiking Decathlon | Socks |  |
| D02 | `socks_mountain_warehouse_melange_blue_01` | Mountain Warehouse Melange Walking Socks azul | Socks |  |
| A03 | `tie_navy_social_01` | Gravata social navy | Tie |  |

### Category: bottom p1/2

![category/bottom-p01](grids/category/bottom-p01.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `pants_uniqlo_ultra_stretch_active_jogger_darkgrey_01` | UNIQLO Ultra Stretch Active Jogger Pants dark gray | Active jogger | candidate_buy |
| B01 | `shorts_uniqlo_ultra_stretch_active_5in_black_01` | UNIQLO Ultra Stretch Active Shorts 5in black | Active shorts | candidate_buy |
| C01 | `shorts_black_gym_01` | Shorts preto de academia | Active shorts |  |
| D01 | `baselayer_uniqlo_heattech_leggings_black_01` | UNIQLO HEATTECH legging térmica preta | Base layer bottom |  |
| A02 | `shorts_cycling_padded_black_01` | Shorts de ciclismo preto com forro | Cycling shorts |  |
| B02 | `pants_tailored_beige_wedding_01` | Calça social bege de casamento | Dress pants |  |
| C02 | `pants_tailored_black_old_01` | Calça social preta alfaiataria antiga | Dress pants |  |
| D02 | `pants_rei_sahara_convertible_taupe_01` | REI Co-op Sahara Convertible Pants | Hiking convertible pants |  |
| A03 | `pants_uniqlo_airism_stretch_jogger_beige_01` | UNIQLO AIRism / Stretch jogger bege | Jogger pants |  |
| B03 | `pants_uniqlo_ultra_stretch_tall_beige_01` | UNIQLO Ultra Stretch Pants Tall beige | Pants | candidate_buy |
| C03 | `pants_uniqlo_ultra_stretch_black_01` | UNIQLO Ultra Stretch Pants black | Pants |  |
| D03 | `pants_uniqlo_airism_stretch_darkgrey_01` | UNIQLO Ultra Stretch Pants dark gray | Pants |  |
| A04 | `pants_uniqlo_ultra_stretch_olive_01` | UNIQLO Ultra Stretch Pants olive | Pants |  |
| B04 | `pants_uniqlo_ultra_stretch_dry_ex_tapered_beige_01` | UNIQLO Ultra Stretch DRY-EX Tapered Pants | Performance tapered pants | candidate_buy |
| C04 | `shorts_uniqlo_stretch_easy_beige_01` | UNIQLO Stretch Easy Shorts beige | Shorts | candidate_buy |
| D04 | `pants_renner_flannel_plaid_01` | Calça flanela xadrez Renner | Sleep pants |  |

### Category: bottom p2/2

![category/bottom-p02](grids/category/bottom-p02.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `shorts_taco_walkshort_flex_beige_01` | TACO Walkshort Flex bege | Walkshort |  |

### Category: footwear p1/1

![category/footwear-p01](grids/category/footwear-p01.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `sneaker_velluti_everyday_brown_01` | Velluti Everyday sapatênis marrom | Casual sneaker |  |
| B01 | `flipflop_havaianas_01` | Havaianas | Flip-flop |  |
| C01 | `boots_timberland_mt_maddsen_wp_brown_01` | Timberland Mt. Maddsen Mid Waterproof Hiking Boot | Hiking boot |  |
| D01 | `shoes_cns_austin_oxford_17358_01` | CNS Austin Oxford social | Oxford shoe |  |
| A02 | `slippers_lightweight_01` | Pantufas leves | Slippers |  |
| B02 | `shoes_democrata_dune_hisoft_298201_black_01` | Democrata Dune Hi-Soft 32 preto | Smart casual derby |  |
| C02 | `sandals_teva_hurricane_xlt2_01` | Teva Hurricane XLT2 masculina | Sport sandal |  |
| D02 | `shoes_nike_pegasus_trail_5_01` | Nike Pegasus Trail 5 | Trail runner | candidate_buy |
| A03 | `shoes_danner_trail2650_gtx_black_shadow_01` | Danner Trail 2650 GTX Black Shadow | Trail shoe | candidate_buy |
| B03 | `boots_danner_mountain600_leaf_gtx_obsidian_01` | Danner Mountain 600 Leaf GTX Obsidian/Kangaroo | Urban hiking boot | candidate_buy |
| C03 | `shoes_aku_bellamont_iv_nbk_gtx_black_grey_01` | AKU Bellamont IV NBK GTX black-grey | Urban-outdoor GTX shoe | candidate_buy |

### Category: outerwear p1/1

![category/outerwear-p01](grids/category/outerwear-p01.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `blazer_tailored_beige_wedding_01` | Blazer bege de casamento | Blazer |  |
| B01 | `blazer_casual_navy_01` | Blazer casual azul marinho | Blazer |  |
| C01 | `blazer_tailored_black_old_01` | Blazer preto alfaiataria antiga | Blazer |  |
| D01 | `down_uniqlo_navy_xs_01` | Jaqueta down UNIQLO azul marinho | Down jacket |  |
| A02 | `down_uniqlo_grey_s_01` | Jaqueta down UNIQLO cinza | Down jacket |  |
| B02 | `fleece_uniqlo_green_halfzip_01` | Fleece UNIQLO verde meio zíper | Fleece |  |
| C02 | `fleece_inextenso_black_s_01` | Fleece preto In Extenso | Fleece |  |
| D02 | `fleece_quechua_plaid_red_01` | Fleece/flanela Quechua xadrez vermelha | Fleece |  |
| A03 | `hoodie_renner_dark_01` | Blusa de manga longa com touca Renner | Hoodie |  |
| B03 | `hoodie_factored_blue_01` | Moletom Factored azul | Hoodie |  |
| C03 | `dry_ex_uv_hoodie_uniqlo_grey_01` | UNIQLO DRY-EX UV Protection Full-Zip Hoodie | Light performance hoodie | candidate_buy |
| D03 | `shell_tnf_alta_vista_blue_01` | The North Face Alta Vista azul | Rain shell | maybe_replace |
| A04 | `shell_uniqlo_blocktech_navy_xs_01` | UNIQLO BLOCKTECH Parka | Rain/wind shell | candidate_buy |
| B04 | `shell_uniqlo_pocketable_01` | Corta-vento UNIQLO ultracompacto | Wind shell |  |

### Category: top p1/2

![category/top-p01](grids/category/top-p01.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `heattech_crew_neck_longsleeve_black_uniqlo_01` | UNIQLO HEATTECH Crew Neck Long Sleeve T-Shirt black | Base layer | candidate_buy |
| B01 | `baselayer_longsleeve_black_01` | Second skin preta manga longa | Base layer |  |
| C01 | `baselayer_uniqlo_merino_light_01` | UNIQLO HEATTECH Crew Neck Long Sleeve T-Shirt | Base layer |  |
| D01 | `shirt_muji_buttondown_navy_s_01` | MUJI camisa button-down navy | Button-down shirt |  |
| A02 | `jersey_vale_europeu_longsleeve_fullzip_01` | Jersey manga longa Vale Europeu | Cycling jersey |  |
| B02 | `shirt_tailored_white_wedding_01` | Camisa social branca sob medida | Dress shirt |  |
| C02 | `shirt_tailored_lilac_old_01` | Camisa social lilás clara alfaiataria antiga | Dress shirt |  |
| D02 | `shirt_uniqlo_super_non_iron_slim_navy_01` | UNIQLO Super Non-Iron Slim Fit Shirt navy | Dress shirt |  |
| A03 | `sweater_uniqlo_merino_black_01` | UNIQLO Merino Sweater navy | Knitwear |  |
| B03 | `tshirt_ondeck_longsleeve_navy_01` | On Deck camiseta manga longa azul escura | Long sleeve T-shirt |  |
| C03 | `shirt_decathlon_longsleeve_orange_plaid_01` | Decathlon camisa manga longa laranja xadrez | Long sleeve shirt |  |
| D03 | `polo_uniqlo_airism_black_01` | UNIQLO AIRism polo preta | Polo |  |
| A04 | `polo_vuori_strato_black_01` | Vuori Strato Tech Polo Charcoal Heather | Polo |  |
| B04 | `shirt_uniqlo_premium_linen_tbd_01` | UNIQLO Premium Linen Shirt | Shirt | candidate_buy |
| C04 | `shirt_muji_brown_s_01` | MUJI Men's Flannel Shirt brown | Shirt |  |
| D04 | `shirt_marfinno_linen_green_01` | Marfinno camisa verde de linho/algodão | Shirt |  |

### Category: top p2/2

![category/top-p02](grids/category/top-p02.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `shirt_avalanche_tropical_blue_01` | Avalanche camisa manga curta estampada | Short sleeve shirt |  |
| B01 | `shirt_decathlon_short_sleeve_blue_technical_01` | Decathlon camisa técnica azul manga curta | Short sleeve shirt |  |
| C01 | `shirt_vuori_short_sleeve_bluegrey_01` | Vuori camisa manga curta azul acinzentada | Short sleeve shirt |  |
| D01 | `tee_uniqlo_airism_crew_black_01` | UNIQLO AIRism Crew Neck T-Shirt | T-shirt | candidate_buy |
| A02 | `tee_uniqlo_dry_ex_black_01` | UNIQLO DRY-EX T-Shirt black | T-shirt | candidate_buy |
| B02 | `tshirt_insider_beige_sleep_01` | Camiseta Insider bege para pijama | T-shirt |  |
| C02 | `tshirt_factored_black_01` | Factored camiseta preta | T-shirt |  |
| D02 | `tee_uniqlo_dry_color_black_xs_01` | UNIQLO DRY Color T-Shirt preta | T-shirt | buy_more |
| A03 | `tshirt_uniqlo_navy_01` | UNIQLO camiseta lisa navy | T-shirt |  |
| B03 | `tshirt_uniqlo_black_01` | UNIQLO camiseta lisa preta | T-shirt |  |
| C03 | `undershirt_uniqlo_airism_vneck_black_01` | UNIQLO AIRism V-Neck undershirt | Undershirt |  |
| D03 | `vest_tailored_beige_wedding_01` | Colete bege de casamento | Vest |  |

### Category: underwear p1/1

![category/underwear-p01](grids/category/underwear-p01.jpg)

| Cell | Item ID | Name | Category | Tags |
|---|---|---|---|---|
| A01 | `underwear_uniqlo_01` | Cuecas UNIQLO | Briefs/boxer briefs |  |
| B01 | `swim_briefs_speedo_black_01` | Speedo sunga preta | Swim briefs |  |

## Owned By Category

| Category | Count | Representative item IDs | Notes |
|---|---:|---|---|
| Tops | 24 | `baselayer_longsleeve_black_01`, `baselayer_uniqlo_merino_light_01`, `shirt_muji_buttondown_navy_s_01`, `jersey_vale_europeu_longsleeve_fullzip_01`, `shirt_tailored_white_wedding_01`, `shirt_tailored_lilac_old_01` | 18 more |
| Bottoms | 12 | `shorts_black_gym_01`, `baselayer_uniqlo_heattech_leggings_black_01`, `shorts_cycling_padded_black_01`, `pants_tailored_beige_wedding_01`, `pants_tailored_black_old_01`, `pants_rei_sahara_convertible_taupe_01` | 6 more |
| Outerwear | 12 | `blazer_tailored_beige_wedding_01`, `blazer_casual_navy_01`, `blazer_tailored_black_old_01`, `down_uniqlo_navy_xs_01`, `down_uniqlo_grey_s_01`, `fleece_uniqlo_green_halfzip_01` | 6 more |
| Footwear | 7 | `sneaker_velluti_everyday_brown_01`, `flipflop_havaianas_01`, `boots_timberland_mt_maddsen_wp_brown_01`, `shoes_cns_austin_oxford_17358_01`, `slippers_lightweight_01`, `shoes_democrata_dune_hisoft_298201_black_01` | 1 more |
| Accessories | 9 | `gloves_uniqlo_black_touchscreen_01`, `scarf_plaid_black_beige_01`, `socks_aztec_technical_grey_01`, `socks_quechua_lightgrey_worn_01`, `socks_black_fuzzy_sleep_01`, `socks_cns_modal_social_01` | 3 more |
| Underwear | 2 | `underwear_uniqlo_01`, `swim_briefs_speedo_black_01` |  |

## Decision Queues

### Candidate Buy Queue

| Item ID | Name | Category | Action | Priority | Notes |
|---|---|---|---|---|---|
| `pants_uniqlo_ultra_stretch_active_jogger_darkgrey_01` | UNIQLO Ultra Stretch Active Jogger Pants dark gray | Active jogger | Buy 1 to compare with current beige jogger | medium | Pode sobrepor o jogger bege atual; decisao depende da composicao final com a calca Ultra Stretch bege. |
| `shorts_uniqlo_ultra_stretch_active_5in_black_01` | UNIQLO Ultra Stretch Active Shorts 5in black | Active shorts | Buy 1 to validate fit and inseam | medium | Pode sobrepor o shorts Nike atual; validar se o fit 5in e conforto em uso real compensam. |
| `pants_uniqlo_ultra_stretch_tall_beige_01` | UNIQLO Ultra Stretch Pants Tall beige | Pants | Buy 1 to validate fit and inseam | high | Pode sobrepor a Ultra Stretch atual; valor principal e inseam mais longo e proporcao melhor. |
| `pants_uniqlo_ultra_stretch_dry_ex_tapered_beige_01` | UNIQLO Ultra Stretch DRY-EX Tapered Pants | Performance tapered pants | Buy 1 to compare with current Ultra Stretch | high | Pode duplicar funcao das Ultra Stretch atuais; validar se traz ganho real em conforto e secagem. |
| `shorts_uniqlo_stretch_easy_beige_01` | UNIQLO Stretch Easy Shorts beige | Shorts | Buy 1 to test fit and fabric | medium | Pode sobrepor outros shorts casuais; validar ganho real versus os modelos tecnicos já catalogados. |
| `shoes_nike_pegasus_trail_5_01` | Nike Pegasus Trail 5 | Trail runner | Test before buy | low | Not waterproof |
| `shoes_danner_trail2650_gtx_black_shadow_01` | Danner Trail 2650 GTX Black Shadow | Trail shoe | Test before buy | medium | Less ankle support |
| `boots_danner_mountain600_leaf_gtx_obsidian_01` | Danner Mountain 600 Leaf GTX Obsidian/Kangaroo | Urban hiking boot | Test before buy | high | Expensive/import |
| `shoes_aku_bellamont_iv_nbk_gtx_black_grey_01` | AKU Bellamont IV NBK GTX black-grey | Urban-outdoor GTX shoe | Test before buy | high | Low shoe not boot |
| `dry_ex_uv_hoodie_uniqlo_grey_01` | UNIQLO DRY-EX UV Protection Full-Zip Hoodie | Light performance hoodie | Buy 1 to test fit and UV utility | medium | Pode sobrepor o uso do pocketable e de camisetas tecnicas dependendo do clima. |
| `shell_uniqlo_blocktech_navy_xs_01` | UNIQLO BLOCKTECH Parka | Rain/wind shell | Test/buy if fit confirmed | high | Own not yet |
| `heattech_crew_neck_longsleeve_black_uniqlo_01` | UNIQLO HEATTECH Crew Neck Long Sleeve T-Shirt black | Base layer | Buy 1 to test warmth and layering | medium | Pode sobrepor o HEATTECH owned na cor cinza; foco e variacao de cor e rotacao. |
| `shirt_uniqlo_premium_linen_tbd_01` | UNIQLO Premium Linen Shirt | Shirt | Buy 1 after choosing final color | medium | Pode sobrepor camisas casuais atuais; ganho principal e conforto termico em calor com look arrumado. |
| `tee_uniqlo_airism_crew_black_01` | UNIQLO AIRism Crew Neck T-Shirt | T-shirt | Test before buy | medium | Candidate basic technical tee |
| `tee_uniqlo_dry_ex_black_01` | UNIQLO DRY-EX T-Shirt black | T-shirt | Buy 1 to test fit and fabric behavior | high | Pode competir com outras camisetas tecnicas pretas; validar caimento e sensacao no uso real. |

### Maybe Replace / Buy More

| Item ID | Name | Category | Action | Priority | Notes |
|---|---|---|---|---|---|
| `shell_tnf_alta_vista_blue_01` | The North Face Alta Vista azul | Rain shell | Keep / maybe replace color | medium | Cor chamativa |
| `tee_uniqlo_dry_color_black_xs_01` | UNIQLO DRY Color T-Shirt preta | T-shirt | Buy more if fit consistent | high | Cotton blend, não técnica pura |

## Active Category Deep Dives

### Tops

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `heattech_crew_neck_longsleeve_black_uniqlo_01` | UNIQLO HEATTECH Crew Neck Long Sleeve T-Shirt black | not_owned, candidate_buy | Base layer | Thermal Layering | 09 BLACK | Base layer termica preta | urban 2.5 / travel 3 | 1 |
| `baselayer_longsleeve_black_01` | Second skin preta manga longa | owned | Base layer | Thermal Layering / Active | Preta | Base layer preta leve e compacta | urban 2.2 / travel 2.8 | 1 |
| `baselayer_uniqlo_merino_light_01` | UNIQLO HEATTECH Crew Neck Long Sleeve T-Shirt | owned | Base layer | Thermal Layering | 08 DARK GRAY | Base térmica core | urban 2.5 / travel 2.9 | 1 |
| `shirt_muji_buttondown_navy_s_01` | MUJI camisa button-down navy | owned | Button-down shirt | Urban Core / Formal-Social casual | Navy | Camisa casual-profissional navy | urban 4 / travel 4 | 3 |
| `jersey_vale_europeu_longsleeve_fullzip_01` | Jersey manga longa Vale Europeu | owned | Cycling jersey | Bike/Active | Multicolorida | Bike/sun module | urban 0.5 / travel 1.8 | 1 |
| `shirt_tailored_white_wedding_01` | Camisa social branca sob medida | owned | Dress shirt | Formal/Social | Branca | Camisa formal clássica | urban 2.8 / travel 2.8 | 1 |
| `shirt_tailored_lilac_old_01` | Camisa social lilás clara alfaiataria antiga | owned | Dress shirt | Formal / Social | Lilás clara | Camisa social antiga | urban 2 / travel 2.5 | 1 |
| `shirt_uniqlo_super_non_iron_slim_navy_01` | UNIQLO Super Non-Iron Slim Fit Shirt navy | owned | Dress shirt | Formal/Social / Urban Core | Navy | Camisa social/corporativa navy | urban 3.6 / travel 3.6 | 1 |
| `sweater_uniqlo_merino_black_01` | UNIQLO Merino Sweater navy | owned | Knitwear | Urban Core | NAVY | Sueter versatil para camada urbana de frio leve | urban 4 / travel 3.8 | 1 |
| `tshirt_ondeck_longsleeve_navy_01` | On Deck camiseta manga longa azul escura | owned | Long sleeve T-shirt | Casual / Work | Azul escuro / navy | Manga longa casual/corporativa On Deck para casa e home office | urban 2.2 / travel 2.4 | 1 |
| `shirt_decathlon_longsleeve_orange_plaid_01` | Decathlon camisa manga longa laranja xadrez | owned | Long sleeve shirt | Outdoor Core / Travel Legacy | Laranja xadrez | Camisa técnica respirável de manga longa | urban 1.8 / travel 2.4 | 2 |
| `polo_uniqlo_airism_black_01` | UNIQLO AIRism polo preta | owned | Polo | Urban Core / Casual Work | Preta | Polo preta casual com bom caimento | urban 3.2 / travel 3.3 | 2 |
| `polo_vuori_strato_black_01` | Vuori Strato Tech Polo Charcoal Heather | owned | Polo | Urban Core | Grafite (Charcoal Heather) | Polo técnica smart-casual | urban 4 / travel 4.2 | 1 |
| `shirt_uniqlo_premium_linen_tbd_01` | UNIQLO Premium Linen Shirt | not_owned, candidate_buy | Shirt | Urban Core | TBD: OLIVE / GREEN / NAVY / NATURAL | Camisa de linho versatil para calor e visual arrumado | urban 4 / travel 4 | 4 |
| `shirt_muji_brown_s_01` | MUJI Men's Flannel Shirt brown | owned | Shirt | Formal/Social | Brown | Camisa flanela regular fit para layering urbano | urban 3.5 / travel 3.3 | 1 |
| `shirt_marfinno_linen_green_01` | Marfinno camisa verde de linho/algodão | owned | Shirt | Urban Core / Hot Weather | Verde claro / sage | Camisa leve que adiciona formalidade sem ocupar muito espaço | urban 3.2 / travel 3.4 | 2 |
| `shirt_avalanche_tropical_blue_01` | Avalanche camisa manga curta estampada | owned | Short sleeve shirt | Hot/Water / Casual Summer | Azul com estampa tropical branca/azul clara | Camisa casual de verão/praia | urban 2.4 / travel 2.4 | 2 |
| `shirt_decathlon_short_sleeve_blue_technical_01` | Decathlon camisa técnica azul manga curta | owned | Short sleeve shirt | Outdoor Core / Hot Weather | Azul acinzentado listrado | Camisa técnica respirável de manga curta | urban 2.4 / travel 2.8 | 2 |
| `shirt_vuori_short_sleeve_bluegrey_01` | Vuori camisa manga curta azul acinzentada | owned | Short sleeve shirt | Urban Core / Hot Weather | Azul acinzentado / slate blue | Camisa técnica casual para calor | urban 4 / travel 4 | 1 |
| `tee_uniqlo_airism_crew_black_01` | UNIQLO AIRism Crew Neck T-Shirt | not_owned, candidate_buy | T-shirt | Urban Core | 09 BLACK | Camiseta técnica leve versátil | urban 3.5 / travel 3.5 | 1 |
| `tee_uniqlo_dry_ex_black_01` | UNIQLO DRY-EX T-Shirt black | not_owned, candidate_buy | T-shirt | Urban Core | 09 BLACK | Camiseta tecnica de secagem rapida para uso diario e ativo | urban 3.5 / travel 4 | 1 |
| `tshirt_insider_beige_sleep_01` | Camiseta Insider bege para pijama | owned | T-shirt | Sleep / Base | Bege | Camiseta de dormir | urban 2 / travel 2.5 | 1 |
| `tshirt_factored_black_01` | Factored camiseta preta | owned | T-shirt | Casual / Work | Preta | Camiseta corporativa casual discreta | urban 2.8 / travel 2.8 | 1 |
| `tee_uniqlo_dry_color_black_xs_01` | UNIQLO DRY Color T-Shirt preta | owned, buy_more | T-shirt | Urban Core | Preta | Camiseta urbana core | urban 3.5 / travel 3.3 | 1 |
| `tshirt_uniqlo_navy_01` | UNIQLO camiseta lisa navy | owned | T-shirt | Urban Core | Navy | Base urbana navy | urban 3.6 / travel 3.6 | 4 |
| `tshirt_uniqlo_black_01` | UNIQLO camiseta lisa preta | owned | T-shirt | Urban Core | Preta | Base urbana preta | urban 3.8 / travel 3.8 | 2 |
| `undershirt_uniqlo_airism_vneck_black_01` | UNIQLO AIRism V-Neck undershirt | owned | Undershirt | Laundry / Base | Preta | Camada de reuso/lavanderia | urban 1 / travel 2.3 | 4 |
| `vest_tailored_beige_wedding_01` | Colete bege de casamento | owned | Vest | Formal / Social | Bege | Colete social | urban 2 / travel 2.5 | 1 |

### Bottoms

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `pants_uniqlo_ultra_stretch_active_jogger_darkgrey_01` | UNIQLO Ultra Stretch Active Jogger Pants dark gray | not_owned, candidate_buy | Active jogger | Bike/Active | 08 DARK GRAY | Jogger tecnico para treinos e uso casual ativo | urban 3.5 / travel 3.7 | 1 |
| `shorts_uniqlo_ultra_stretch_active_5in_black_01` | UNIQLO Ultra Stretch Active Shorts 5in black | not_owned, candidate_buy | Active shorts | Bike/Active | 09 BLACK | Short tecnico leve para clima quente e atividade | urban 2.5 / travel 3.4 | 1 |
| `shorts_black_gym_01` | Shorts preto de academia | owned | Active shorts | Bike/Active | Preto | Shorts ativo atual | urban 2 / travel 2.5 | 2 |
| `baselayer_uniqlo_heattech_leggings_black_01` | UNIQLO HEATTECH legging térmica preta | owned | Base layer bottom | Thermal Layering | Preta | Camada térmica inferior | urban 2 / travel 2.5 | 4 |
| `shorts_cycling_padded_black_01` | Shorts de ciclismo preto com forro | owned | Cycling shorts | Bike/Active | Preto | Shorts específico para bike que parece shorts normal | urban 1.5 / travel 2 | 1 |
| `pants_tailored_beige_wedding_01` | Calça social bege de casamento | owned | Dress pants | Formal / Social | Bege | Calça social clara | urban 2 / travel 2.5 | 2 |
| `pants_tailored_black_old_01` | Calça social preta alfaiataria antiga | owned | Dress pants | Formal / Social | Preta | Calça de terno antigo | urban 2 / travel 2.5 | 1 |
| `pants_rei_sahara_convertible_taupe_01` | REI Co-op Sahara Convertible Pants | owned | Hiking convertible pants | Outdoor Core | Armadillo Taupe / bege | Outdoor modular pants | urban 1.5 / travel 2.2 | 2 |
| `pants_uniqlo_airism_stretch_jogger_beige_01` | UNIQLO AIRism / Stretch jogger bege | owned | Jogger pants | Urban Core | Bege | Jogger claro de viagem | urban 3.5 / travel 3.8 | 1 |
| `pants_uniqlo_ultra_stretch_tall_beige_01` | UNIQLO Ultra Stretch Pants Tall beige | not_owned, candidate_buy | Pants | Urban Core | 32 BEIGE | Calca tapered tall para uso diario versatil | urban 4 / travel 4.1 | 1 |
| `pants_uniqlo_ultra_stretch_black_01` | UNIQLO Ultra Stretch Pants black | owned | Pants | Urban Core | Preto / quase preto | Calça urbana core preta | urban 4.2 / travel 4.2 | 3 |
| `pants_uniqlo_airism_stretch_darkgrey_01` | UNIQLO Ultra Stretch Pants dark gray | owned | Pants | Urban Core | 08 DARK GRAY | Calca tapered versatil para office/travel | urban 4 / travel 4 | 3 |
| `pants_uniqlo_ultra_stretch_olive_01` | UNIQLO Ultra Stretch Pants olive | owned | Pants | Urban Core | 57 OLIVE | Calça tapered versátil olive | urban 2 / travel 2.5 | 4 |
| `pants_uniqlo_ultra_stretch_dry_ex_tapered_beige_01` | UNIQLO Ultra Stretch DRY-EX Tapered Pants | not_owned, candidate_buy | Performance tapered pants | Urban Core | 32 BEIGE | Calca tapered tecnica para uso urbano e viagem | urban 4 / travel 4.1 | 1 |
| `shorts_uniqlo_stretch_easy_beige_01` | UNIQLO Stretch Easy Shorts beige | not_owned, candidate_buy | Shorts | Hot/Water | 31 BEIGE | Short casual leve para clima quente | urban 3 / travel 3.5 | 1 |
| `pants_renner_flannel_plaid_01` | Calça flanela xadrez Renner | owned | Sleep pants | Sleep / Camp | Xadrez escuro | Calça de pijama fria | urban 2 / travel 2.5 | 2 |
| `shorts_taco_walkshort_flex_beige_01` | TACO Walkshort Flex bege | owned | Walkshort | Hot/Water / Casual Summer | Bege / khaki | Bermuda casual de verão | urban 2.8 / travel 2.8 | 2 |

### Outerwear

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `blazer_tailored_beige_wedding_01` | Blazer bege de casamento | owned | Blazer | Formal / Social | Bege | Blazer social claro | urban 2 / travel 2.5 | 1 |
| `blazer_casual_navy_01` | Blazer casual azul marinho | owned | Blazer | Urban Core | Azul marinho | Blazer casual urbano | urban 2 / travel 2.5 | 1 |
| `blazer_tailored_black_old_01` | Blazer preto alfaiataria antiga | owned | Blazer | Formal / Social | Preto / charcoal | Blazer de terno antigo | urban 2 / travel 2.5 | 1 |
| `down_uniqlo_navy_xs_01` | Jaqueta down UNIQLO azul marinho | owned | Down jacket | Thermal Layering | Azul marinho | Clean insulation | urban 3 / travel 3.5 | 2 |
| `down_uniqlo_grey_s_01` | Jaqueta down UNIQLO cinza | owned | Down jacket | Thermal Layering | Cinza | Beater down | urban 2 / travel 2.9 | 1 |
| `fleece_uniqlo_green_halfzip_01` | Fleece UNIQLO verde meio zíper | owned | Fleece | Thermal Layering | Verde | Fleece meio zíper | urban 2 / travel 2.5 | 1 |
| `fleece_inextenso_black_s_01` | Fleece preto In Extenso | owned | Fleece | Thermal Layering | Preto | Comfort midlayer | urban 2.5 / travel 3 | 2 |
| `fleece_quechua_plaid_red_01` | Fleece/flanela Quechua xadrez vermelha | owned | Fleece | Thermal Layering | Vermelho xadrez | Fleece/flanela casual | urban 2 / travel 2.5 | 1 |
| `hoodie_renner_dark_01` | Blusa de manga longa com touca Renner | owned | Hoodie | Casual / Comfort | Azul escuro / cinza escuro | Hoodie casual | urban 2 / travel 2.5 | 1 |
| `hoodie_factored_blue_01` | Moletom Factored azul | owned | Hoodie | Casual / Comfort | Azul vivo | Hoodie da empresa | urban 2 / travel 2.5 | 1 |
| `dry_ex_uv_hoodie_uniqlo_grey_01` | UNIQLO DRY-EX UV Protection Full-Zip Hoodie | not_owned, candidate_buy | Light performance hoodie | Urban Core | 07 GRAY | Camada tecnica leve com protecao UV | urban 3.5 / travel 3.9 | 1 |
| `shell_tnf_alta_vista_blue_01` | The North Face Alta Vista azul | owned, maybe_replace | Rain shell | Outdoor Core | Azul | Rain shell técnica | urban 2.5 / travel 2.8 | 4 |
| `shell_uniqlo_blocktech_navy_xs_01` | UNIQLO BLOCKTECH Parka | not_owned, candidate_buy | Rain/wind shell | Urban Core | Navy / preto / grafite | Shell urbana principal | urban 4 / travel 3.9 | 1 |
| `shell_uniqlo_pocketable_01` | Corta-vento UNIQLO ultracompacto | owned | Wind shell | Zero Bag | ? | Zero bag wind shell | urban 2.5 / travel 3.1 | 1 |

### Footwear

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `sneaker_velluti_everyday_brown_01` | Velluti Everyday sapatênis marrom | owned | Casual sneaker | Urban Core / Casual | Marrom escuro com detalhes marrom médio | Sapatênis urbano marrom | urban 3.4 / travel 3.4 | 3 |
| `flipflop_havaianas_01` | Havaianas | owned | Flip-flop | Hot/Water | ? | Banho/praia | urban 1 / travel 1.8 | 1 |
| `boots_timberland_mt_maddsen_wp_brown_01` | Timberland Mt. Maddsen Mid Waterproof Hiking Boot | owned | Hiking boot | Outdoor Core | Marrom | Bota robusta principal | urban 2 / travel 1.9 | 1 |
| `shoes_cns_austin_oxford_17358_01` | CNS Austin Oxford social | owned | Oxford shoe | Formal/Social | ? | Sapato formal clássico | urban 3 / travel 3.2 | 5 |
| `slippers_lightweight_01` | Pantufas leves | owned | Slippers | Indoor/Comfort | ? | Conforto indoor | urban 0 / travel 1.8 | 2 |
| `shoes_democrata_dune_hisoft_298201_black_01` | Democrata Dune Hi-Soft 32 preto | owned | Smart casual derby | Formal/Social | Preto com sola marrom e faixa clara | Social descontraído | urban 3.5 / travel 3.2 | 2 |
| `sandals_teva_hurricane_xlt2_01` | Teva Hurricane XLT2 masculina | owned | Sport sandal | Hot/Water | Preta | Water/hot sandal | urban 1.5 / travel 1.9 | 2 |
| `shoes_nike_pegasus_trail_5_01` | Nike Pegasus Trail 5 | not_owned, candidate_buy | Trail runner | Bike/Active | Preta/grafite ideal | Corrida + trilha leve | urban 3.5 / travel 2.6 | 1 |
| `shoes_danner_trail2650_gtx_black_shadow_01` | Danner Trail 2650 GTX Black Shadow | not_owned, candidate_buy | Trail shoe | Bike/Active | Black Shadow | Exploração leve | urban 3.5 / travel 2.7 | 3 |
| `boots_danner_mountain600_leaf_gtx_obsidian_01` | Danner Mountain 600 Leaf GTX Obsidian/Kangaroo | not_owned, candidate_buy | Urban hiking boot | Urban Core | Obsidian/Kangaroo | Bota urbano-rugged premium | urban 4 / travel 3.1 | 3 |
| `shoes_aku_bellamont_iv_nbk_gtx_black_grey_01` | AKU Bellamont IV NBK GTX black-grey | not_owned, candidate_buy | Urban-outdoor GTX shoe | Urban Core | Black-grey | Urban-outdoor low shoe | urban 4.5 / travel 3.3 | 1 |

### Accessories

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `gloves_uniqlo_black_touchscreen_01` | UNIQLO luvas pretas touchscreen | owned | Gloves | Thermal Layering | Preta | Luvas compactas para frio e celular | urban 3.2 / travel 3.4 | 1 |
| `scarf_plaid_black_beige_01` | Cachecol xadrez preto/bege | owned | Scarf | Thermal Layering / Urban Core | Xadrez preto/bege | Cachecol compacto para frio leve/moderado | urban 3 / travel 3.2 | 1 |
| `socks_aztec_technical_grey_01` | AZTEC meia técnica cinza | owned | Socks | Outdoor Core | Cinza / grafite | Meia técnica cinza para trilha/uso ativo | urban 2.2 / travel 2.8 | 1 |
| `socks_quechua_lightgrey_worn_01` | Meia técnica cinza clara gasta | owned | Socks | Outdoor Core | Cinza clara | Meia técnica gasta | urban 2 / travel 2.5 | 1 |
| `socks_black_fuzzy_sleep_01` | Meias pretas felpudas para frio | owned | Socks | Sleep / Camp | Preta | Meia quente de dormir | urban 2 / travel 2.5 | 2 |
| `socks_cns_modal_social_01` | Meias sociais modal CNS | owned | Socks | Formal/Social | ? | Social socks | urban 3 / travel 3.7 | 1 |
| `socks_decathlon_hiking_01` | Meias técnicas hiking Decathlon | owned | Socks | Outdoor Core | ? | Outdoor socks | urban 1 / travel 2 | 1 |
| `socks_mountain_warehouse_melange_blue_01` | Mountain Warehouse Melange Walking Socks azul | owned | Socks | Outdoor Core | Azul | Meia de caminhada azul | urban 2 / travel 2.5 | 1 |
| `tie_navy_social_01` | Gravata social navy | owned | Tie | Formal / Social | Navy | Acessório social | urban 2 / travel 2.5 | 1 |

### Underwear

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `underwear_uniqlo_01` | Cuecas UNIQLO | owned | Briefs/boxer briefs | Laundry / Base | ? | Core underwear | urban 1 / travel 2.2 | 1 |
| `swim_briefs_speedo_black_01` | Speedo sunga preta | owned | Swim briefs | Hot/Water | Preta | Sunga de natação compacta | urban 0.5 / travel 2.5 | 1 |

## Use-Case Modules

These are presentation modules for AI reasoning. They normalize the noisier raw `module` values without changing catalog source data.

| Module | Count | Raw module values folded here |
|---|---:|---|
| Urban | 22 | Casual / Comfort, Casual / Work, Urban Core, Urban Core / Casual, Urban Core / Casual Work |
| Formal/Social | 14 | Formal / Social, Formal/Social, Formal/Social / Urban Core, Urban Core / Formal-Social casual |
| Outdoor/Rain | 13 | Outdoor Core, Outdoor Core / Hot Weather, Outdoor Core / Travel Legacy, Urban Core, Zero Bag |
| Thermal/Cold | 10 | Thermal Layering, Thermal Layering / Urban Core |
| Active/Bike | 8 | Bike/Active, Thermal Layering / Active |
| Hot/Water | 8 | Hot/Water, Hot/Water / Casual Summer, Urban Core / Hot Weather |
| Sleep/Indoor | 4 | Indoor/Comfort, Sleep / Base, Sleep / Camp |
| Laundry/Base | 2 | Laundry / Base |

### Urban

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `pants_uniqlo_airism_stretch_jogger_beige_01` | UNIQLO AIRism / Stretch jogger bege | owned | Jogger pants | Urban Core | Bege | Jogger claro de viagem | urban 3.5 / travel 3.8 | 1 |
| `pants_uniqlo_ultra_stretch_tall_beige_01` | UNIQLO Ultra Stretch Pants Tall beige | not_owned, candidate_buy | Pants | Urban Core | 32 BEIGE | Calca tapered tall para uso diario versatil | urban 4 / travel 4.1 | 1 |
| `pants_uniqlo_ultra_stretch_black_01` | UNIQLO Ultra Stretch Pants black | owned | Pants | Urban Core | Preto / quase preto | Calça urbana core preta | urban 4.2 / travel 4.2 | 3 |
| `pants_uniqlo_airism_stretch_darkgrey_01` | UNIQLO Ultra Stretch Pants dark gray | owned | Pants | Urban Core | 08 DARK GRAY | Calca tapered versatil para office/travel | urban 4 / travel 4 | 3 |
| `pants_uniqlo_ultra_stretch_olive_01` | UNIQLO Ultra Stretch Pants olive | owned | Pants | Urban Core | 57 OLIVE | Calça tapered versátil olive | urban 2 / travel 2.5 | 4 |
| `pants_uniqlo_ultra_stretch_dry_ex_tapered_beige_01` | UNIQLO Ultra Stretch DRY-EX Tapered Pants | not_owned, candidate_buy | Performance tapered pants | Urban Core | 32 BEIGE | Calca tapered tecnica para uso urbano e viagem | urban 4 / travel 4.1 | 1 |
| `sneaker_velluti_everyday_brown_01` | Velluti Everyday sapatênis marrom | owned | Casual sneaker | Urban Core / Casual | Marrom escuro com detalhes marrom médio | Sapatênis urbano marrom | urban 3.4 / travel 3.4 | 3 |
| `blazer_casual_navy_01` | Blazer casual azul marinho | owned | Blazer | Urban Core | Azul marinho | Blazer casual urbano | urban 2 / travel 2.5 | 1 |
| `hoodie_renner_dark_01` | Blusa de manga longa com touca Renner | owned | Hoodie | Casual / Comfort | Azul escuro / cinza escuro | Hoodie casual | urban 2 / travel 2.5 | 1 |
| `hoodie_factored_blue_01` | Moletom Factored azul | owned | Hoodie | Casual / Comfort | Azul vivo | Hoodie da empresa | urban 2 / travel 2.5 | 1 |
| `dry_ex_uv_hoodie_uniqlo_grey_01` | UNIQLO DRY-EX UV Protection Full-Zip Hoodie | not_owned, candidate_buy | Light performance hoodie | Urban Core | 07 GRAY | Camada tecnica leve com protecao UV | urban 3.5 / travel 3.9 | 1 |
| `sweater_uniqlo_merino_black_01` | UNIQLO Merino Sweater navy | owned | Knitwear | Urban Core | NAVY | Sueter versatil para camada urbana de frio leve | urban 4 / travel 3.8 | 1 |
| `tshirt_ondeck_longsleeve_navy_01` | On Deck camiseta manga longa azul escura | owned | Long sleeve T-shirt | Casual / Work | Azul escuro / navy | Manga longa casual/corporativa On Deck para casa e home office | urban 2.2 / travel 2.4 | 1 |
| `polo_uniqlo_airism_black_01` | UNIQLO AIRism polo preta | owned | Polo | Urban Core / Casual Work | Preta | Polo preta casual com bom caimento | urban 3.2 / travel 3.3 | 2 |
| `polo_vuori_strato_black_01` | Vuori Strato Tech Polo Charcoal Heather | owned | Polo | Urban Core | Grafite (Charcoal Heather) | Polo técnica smart-casual | urban 4 / travel 4.2 | 1 |
| `shirt_uniqlo_premium_linen_tbd_01` | UNIQLO Premium Linen Shirt | not_owned, candidate_buy | Shirt | Urban Core | TBD: OLIVE / GREEN / NAVY / NATURAL | Camisa de linho versatil para calor e visual arrumado | urban 4 / travel 4 | 4 |
| `tee_uniqlo_airism_crew_black_01` | UNIQLO AIRism Crew Neck T-Shirt | not_owned, candidate_buy | T-shirt | Urban Core | 09 BLACK | Camiseta técnica leve versátil | urban 3.5 / travel 3.5 | 1 |
| `tee_uniqlo_dry_ex_black_01` | UNIQLO DRY-EX T-Shirt black | not_owned, candidate_buy | T-shirt | Urban Core | 09 BLACK | Camiseta tecnica de secagem rapida para uso diario e ativo | urban 3.5 / travel 4 | 1 |
| `tshirt_factored_black_01` | Factored camiseta preta | owned | T-shirt | Casual / Work | Preta | Camiseta corporativa casual discreta | urban 2.8 / travel 2.8 | 1 |
| `tee_uniqlo_dry_color_black_xs_01` | UNIQLO DRY Color T-Shirt preta | owned, buy_more | T-shirt | Urban Core | Preta | Camiseta urbana core | urban 3.5 / travel 3.3 | 1 |
| `tshirt_uniqlo_navy_01` | UNIQLO camiseta lisa navy | owned | T-shirt | Urban Core | Navy | Base urbana navy | urban 3.6 / travel 3.6 | 4 |
| `tshirt_uniqlo_black_01` | UNIQLO camiseta lisa preta | owned | T-shirt | Urban Core | Preta | Base urbana preta | urban 3.8 / travel 3.8 | 2 |

### Formal/Social

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `socks_cns_modal_social_01` | Meias sociais modal CNS | owned | Socks | Formal/Social | ? | Social socks | urban 3 / travel 3.7 | 1 |
| `tie_navy_social_01` | Gravata social navy | owned | Tie | Formal / Social | Navy | Acessório social | urban 2 / travel 2.5 | 1 |
| `pants_tailored_beige_wedding_01` | Calça social bege de casamento | owned | Dress pants | Formal / Social | Bege | Calça social clara | urban 2 / travel 2.5 | 2 |
| `pants_tailored_black_old_01` | Calça social preta alfaiataria antiga | owned | Dress pants | Formal / Social | Preta | Calça de terno antigo | urban 2 / travel 2.5 | 1 |
| `shoes_cns_austin_oxford_17358_01` | CNS Austin Oxford social | owned | Oxford shoe | Formal/Social | ? | Sapato formal clássico | urban 3 / travel 3.2 | 5 |
| `shoes_democrata_dune_hisoft_298201_black_01` | Democrata Dune Hi-Soft 32 preto | owned | Smart casual derby | Formal/Social | Preto com sola marrom e faixa clara | Social descontraído | urban 3.5 / travel 3.2 | 2 |
| `blazer_tailored_beige_wedding_01` | Blazer bege de casamento | owned | Blazer | Formal / Social | Bege | Blazer social claro | urban 2 / travel 2.5 | 1 |
| `blazer_tailored_black_old_01` | Blazer preto alfaiataria antiga | owned | Blazer | Formal / Social | Preto / charcoal | Blazer de terno antigo | urban 2 / travel 2.5 | 1 |
| `shirt_muji_buttondown_navy_s_01` | MUJI camisa button-down navy | owned | Button-down shirt | Urban Core / Formal-Social casual | Navy | Camisa casual-profissional navy | urban 4 / travel 4 | 3 |
| `shirt_tailored_white_wedding_01` | Camisa social branca sob medida | owned | Dress shirt | Formal/Social | Branca | Camisa formal clássica | urban 2.8 / travel 2.8 | 1 |
| `shirt_tailored_lilac_old_01` | Camisa social lilás clara alfaiataria antiga | owned | Dress shirt | Formal / Social | Lilás clara | Camisa social antiga | urban 2 / travel 2.5 | 1 |
| `shirt_uniqlo_super_non_iron_slim_navy_01` | UNIQLO Super Non-Iron Slim Fit Shirt navy | owned | Dress shirt | Formal/Social / Urban Core | Navy | Camisa social/corporativa navy | urban 3.6 / travel 3.6 | 1 |
| `shirt_muji_brown_s_01` | MUJI Men's Flannel Shirt brown | owned | Shirt | Formal/Social | Brown | Camisa flanela regular fit para layering urbano | urban 3.5 / travel 3.3 | 1 |
| `vest_tailored_beige_wedding_01` | Colete bege de casamento | owned | Vest | Formal / Social | Bege | Colete social | urban 2 / travel 2.5 | 1 |

### Outdoor/Rain

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `socks_aztec_technical_grey_01` | AZTEC meia técnica cinza | owned | Socks | Outdoor Core | Cinza / grafite | Meia técnica cinza para trilha/uso ativo | urban 2.2 / travel 2.8 | 1 |
| `socks_quechua_lightgrey_worn_01` | Meia técnica cinza clara gasta | owned | Socks | Outdoor Core | Cinza clara | Meia técnica gasta | urban 2 / travel 2.5 | 1 |
| `socks_decathlon_hiking_01` | Meias técnicas hiking Decathlon | owned | Socks | Outdoor Core | ? | Outdoor socks | urban 1 / travel 2 | 1 |
| `socks_mountain_warehouse_melange_blue_01` | Mountain Warehouse Melange Walking Socks azul | owned | Socks | Outdoor Core | Azul | Meia de caminhada azul | urban 2 / travel 2.5 | 1 |
| `pants_rei_sahara_convertible_taupe_01` | REI Co-op Sahara Convertible Pants | owned | Hiking convertible pants | Outdoor Core | Armadillo Taupe / bege | Outdoor modular pants | urban 1.5 / travel 2.2 | 2 |
| `boots_timberland_mt_maddsen_wp_brown_01` | Timberland Mt. Maddsen Mid Waterproof Hiking Boot | owned | Hiking boot | Outdoor Core | Marrom | Bota robusta principal | urban 2 / travel 1.9 | 1 |
| `boots_danner_mountain600_leaf_gtx_obsidian_01` | Danner Mountain 600 Leaf GTX Obsidian/Kangaroo | not_owned, candidate_buy | Urban hiking boot | Urban Core | Obsidian/Kangaroo | Bota urbano-rugged premium | urban 4 / travel 3.1 | 3 |
| `shoes_aku_bellamont_iv_nbk_gtx_black_grey_01` | AKU Bellamont IV NBK GTX black-grey | not_owned, candidate_buy | Urban-outdoor GTX shoe | Urban Core | Black-grey | Urban-outdoor low shoe | urban 4.5 / travel 3.3 | 1 |
| `shell_tnf_alta_vista_blue_01` | The North Face Alta Vista azul | owned, maybe_replace | Rain shell | Outdoor Core | Azul | Rain shell técnica | urban 2.5 / travel 2.8 | 4 |
| `shell_uniqlo_blocktech_navy_xs_01` | UNIQLO BLOCKTECH Parka | not_owned, candidate_buy | Rain/wind shell | Urban Core | Navy / preto / grafite | Shell urbana principal | urban 4 / travel 3.9 | 1 |
| `shell_uniqlo_pocketable_01` | Corta-vento UNIQLO ultracompacto | owned | Wind shell | Zero Bag | ? | Zero bag wind shell | urban 2.5 / travel 3.1 | 1 |
| `shirt_decathlon_longsleeve_orange_plaid_01` | Decathlon camisa manga longa laranja xadrez | owned | Long sleeve shirt | Outdoor Core / Travel Legacy | Laranja xadrez | Camisa técnica respirável de manga longa | urban 1.8 / travel 2.4 | 2 |
| `shirt_decathlon_short_sleeve_blue_technical_01` | Decathlon camisa técnica azul manga curta | owned | Short sleeve shirt | Outdoor Core / Hot Weather | Azul acinzentado listrado | Camisa técnica respirável de manga curta | urban 2.4 / travel 2.8 | 2 |

### Thermal/Cold

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `gloves_uniqlo_black_touchscreen_01` | UNIQLO luvas pretas touchscreen | owned | Gloves | Thermal Layering | Preta | Luvas compactas para frio e celular | urban 3.2 / travel 3.4 | 1 |
| `scarf_plaid_black_beige_01` | Cachecol xadrez preto/bege | owned | Scarf | Thermal Layering / Urban Core | Xadrez preto/bege | Cachecol compacto para frio leve/moderado | urban 3 / travel 3.2 | 1 |
| `baselayer_uniqlo_heattech_leggings_black_01` | UNIQLO HEATTECH legging térmica preta | owned | Base layer bottom | Thermal Layering | Preta | Camada térmica inferior | urban 2 / travel 2.5 | 4 |
| `down_uniqlo_navy_xs_01` | Jaqueta down UNIQLO azul marinho | owned | Down jacket | Thermal Layering | Azul marinho | Clean insulation | urban 3 / travel 3.5 | 2 |
| `down_uniqlo_grey_s_01` | Jaqueta down UNIQLO cinza | owned | Down jacket | Thermal Layering | Cinza | Beater down | urban 2 / travel 2.9 | 1 |
| `fleece_uniqlo_green_halfzip_01` | Fleece UNIQLO verde meio zíper | owned | Fleece | Thermal Layering | Verde | Fleece meio zíper | urban 2 / travel 2.5 | 1 |
| `fleece_inextenso_black_s_01` | Fleece preto In Extenso | owned | Fleece | Thermal Layering | Preto | Comfort midlayer | urban 2.5 / travel 3 | 2 |
| `fleece_quechua_plaid_red_01` | Fleece/flanela Quechua xadrez vermelha | owned | Fleece | Thermal Layering | Vermelho xadrez | Fleece/flanela casual | urban 2 / travel 2.5 | 1 |
| `heattech_crew_neck_longsleeve_black_uniqlo_01` | UNIQLO HEATTECH Crew Neck Long Sleeve T-Shirt black | not_owned, candidate_buy | Base layer | Thermal Layering | 09 BLACK | Base layer termica preta | urban 2.5 / travel 3 | 1 |
| `baselayer_uniqlo_merino_light_01` | UNIQLO HEATTECH Crew Neck Long Sleeve T-Shirt | owned | Base layer | Thermal Layering | 08 DARK GRAY | Base térmica core | urban 2.5 / travel 2.9 | 1 |

### Active/Bike

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `pants_uniqlo_ultra_stretch_active_jogger_darkgrey_01` | UNIQLO Ultra Stretch Active Jogger Pants dark gray | not_owned, candidate_buy | Active jogger | Bike/Active | 08 DARK GRAY | Jogger tecnico para treinos e uso casual ativo | urban 3.5 / travel 3.7 | 1 |
| `shorts_uniqlo_ultra_stretch_active_5in_black_01` | UNIQLO Ultra Stretch Active Shorts 5in black | not_owned, candidate_buy | Active shorts | Bike/Active | 09 BLACK | Short tecnico leve para clima quente e atividade | urban 2.5 / travel 3.4 | 1 |
| `shorts_black_gym_01` | Shorts preto de academia | owned | Active shorts | Bike/Active | Preto | Shorts ativo atual | urban 2 / travel 2.5 | 2 |
| `shorts_cycling_padded_black_01` | Shorts de ciclismo preto com forro | owned | Cycling shorts | Bike/Active | Preto | Shorts específico para bike que parece shorts normal | urban 1.5 / travel 2 | 1 |
| `shoes_nike_pegasus_trail_5_01` | Nike Pegasus Trail 5 | not_owned, candidate_buy | Trail runner | Bike/Active | Preta/grafite ideal | Corrida + trilha leve | urban 3.5 / travel 2.6 | 1 |
| `shoes_danner_trail2650_gtx_black_shadow_01` | Danner Trail 2650 GTX Black Shadow | not_owned, candidate_buy | Trail shoe | Bike/Active | Black Shadow | Exploração leve | urban 3.5 / travel 2.7 | 3 |
| `baselayer_longsleeve_black_01` | Second skin preta manga longa | owned | Base layer | Thermal Layering / Active | Preta | Base layer preta leve e compacta | urban 2.2 / travel 2.8 | 1 |
| `jersey_vale_europeu_longsleeve_fullzip_01` | Jersey manga longa Vale Europeu | owned | Cycling jersey | Bike/Active | Multicolorida | Bike/sun module | urban 0.5 / travel 1.8 | 1 |

### Hot/Water

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `shorts_uniqlo_stretch_easy_beige_01` | UNIQLO Stretch Easy Shorts beige | not_owned, candidate_buy | Shorts | Hot/Water | 31 BEIGE | Short casual leve para clima quente | urban 3 / travel 3.5 | 1 |
| `shorts_taco_walkshort_flex_beige_01` | TACO Walkshort Flex bege | owned | Walkshort | Hot/Water / Casual Summer | Bege / khaki | Bermuda casual de verão | urban 2.8 / travel 2.8 | 2 |
| `flipflop_havaianas_01` | Havaianas | owned | Flip-flop | Hot/Water | ? | Banho/praia | urban 1 / travel 1.8 | 1 |
| `sandals_teva_hurricane_xlt2_01` | Teva Hurricane XLT2 masculina | owned | Sport sandal | Hot/Water | Preta | Water/hot sandal | urban 1.5 / travel 1.9 | 2 |
| `shirt_marfinno_linen_green_01` | Marfinno camisa verde de linho/algodão | owned | Shirt | Urban Core / Hot Weather | Verde claro / sage | Camisa leve que adiciona formalidade sem ocupar muito espaço | urban 3.2 / travel 3.4 | 2 |
| `shirt_avalanche_tropical_blue_01` | Avalanche camisa manga curta estampada | owned | Short sleeve shirt | Hot/Water / Casual Summer | Azul com estampa tropical branca/azul clara | Camisa casual de verão/praia | urban 2.4 / travel 2.4 | 2 |
| `shirt_vuori_short_sleeve_bluegrey_01` | Vuori camisa manga curta azul acinzentada | owned | Short sleeve shirt | Urban Core / Hot Weather | Azul acinzentado / slate blue | Camisa técnica casual para calor | urban 4 / travel 4 | 1 |
| `swim_briefs_speedo_black_01` | Speedo sunga preta | owned | Swim briefs | Hot/Water | Preta | Sunga de natação compacta | urban 0.5 / travel 2.5 | 1 |

### Sleep/Indoor

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `socks_black_fuzzy_sleep_01` | Meias pretas felpudas para frio | owned | Socks | Sleep / Camp | Preta | Meia quente de dormir | urban 2 / travel 2.5 | 2 |
| `pants_renner_flannel_plaid_01` | Calça flanela xadrez Renner | owned | Sleep pants | Sleep / Camp | Xadrez escuro | Calça de pijama fria | urban 2 / travel 2.5 | 2 |
| `slippers_lightweight_01` | Pantufas leves | owned | Slippers | Indoor/Comfort | ? | Conforto indoor | urban 0 / travel 1.8 | 2 |
| `tshirt_insider_beige_sleep_01` | Camiseta Insider bege para pijama | owned | T-shirt | Sleep / Base | Bege | Camiseta de dormir | urban 2 / travel 2.5 | 1 |

### Laundry/Base

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `undershirt_uniqlo_airism_vneck_black_01` | UNIQLO AIRism V-Neck undershirt | owned | Undershirt | Laundry / Base | Preta | Camada de reuso/lavanderia | urban 1 / travel 2.3 | 4 |
| `underwear_uniqlo_01` | Cuecas UNIQLO | owned | Briefs/boxer briefs | Laundry / Base | ? | Core underwear | urban 1 / travel 2.2 | 1 |

## Archive

Archived items are kept for historical reference and duplicate tracking. They should not be used in normal outfit recommendations unless explicitly requested.

| Item ID | Name | Ownership/tags | Subcategory | Module | Color | Use/role | Scores | Images |
|---|---|---|---|---|---|---|---|---|
| `shorts_nike_running_01` | Shorts Nike de corrida | archived, archived | Running shorts | Bike/Active | ? | Active/light shorts | urban 1 / travel 2.2 | 3 |
| `shoes_salomon_xultra_mid_gtx_black_01` | Salomon X Ultra Mid GTX preto | archived, archived | Technical hiking boot/shoe | Outdoor Core | Preto | Opção técnica de trilha | urban 2.5 / travel 2 | 1 |
| `boots_timberland_redwood_falls_wp_01` | Timberland Redwood Falls Waterproof | archived, archived | Waterproof casual boot | Urban Core | Marrom escuro/preto ideal | Bota pragmática urbano-outdoor | urban 4 / travel 2.9 | 0 |
| `shell_quechua_raincut_halfzip_black_01` | Quechua Raincut 1/2 preta | archived, archived | Emergency rain shell | Outdoor Core | Preta | Emergency rain shell | urban 1.5 / travel 2.2 | 0 |
| `jersey_longsleeve_fullzip_neutral_01` | Jersey manga longa neutra full zip | archived, archived | Cycling jersey | Bike/Active | Preta/grafite/navy | Neutral bike jersey | urban 1.5 / travel 2.4 | 0 |
| `tshirt_factored_white_01` | Factored camiseta branca | archived, archived | T-shirt | Casual / Work | Branca | Camiseta corporativa casual | urban 2.5 / travel 2.5 | 0 |

## Prompt Pattern

Use this when asking an AI to work from the context:

```text
Read AI_CONTEXT.md / wardrobe-context.md first. Start from Active Visual Overview, Owned By Category, Decision Queues, and Use-Case Modules. Cite stable itemId values from the tables. Use category grids for visual comparison. Only ask for individual image inspection when a grid cell is ambiguous. Preserve owned/not_owned/candidate_buy/maybe_replace/archive distinctions.
```

## Regeneration

Private repo:

```bash
npm run wardrobe:build
npm run wardrobe:grids
npm run wardrobe:context
```

Public mirror:

```bash
npm run wardrobe:sync-public
```
