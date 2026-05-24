# Proposed Recipe Collection Ontology
## For Review — Please Comment and Approve Before Reorganization

This document proposes an organizational structure for the full recipe collection
(~107 recipes across root, bbq/, baked_goods/, drinks/, ceviches/, pickling/,
and elke-dag-stamppot-feb2021/).

The ontology uses **two primary axes**: cuisine/geographical origin and cooking
methodology. A tagging system is proposed in addition to folder structure,
since many recipes span multiple categories.

---

## Proposed Folder Structure

```
recipe-book/
│
├── soups/                          # All soups and broths
├── salads/                         # Cold salads, warm salads, meal salads
├── mains/
│   ├── dutch/                      # Dutch cuisine mains (stew, stamppot, etc.)
│   ├── polish/                     # Polish cuisine mains
│   ├── eastern-european/           # Hungarian, Russian, Georgian, etc.
│   ├── french-european/            # French, Alsatian, Belgian, Savoyard
│   ├── mediterranean/              # Italian, Greek, Turkish
│   ├── middle-eastern-north-african/ # Moroccan, Israeli, Levantine
│   ├── asian/                      # Japanese, Indonesian, Chinese
│   ├── american/                   # American, Tex-Mex, Cajun/Southern
│   └── bbq-and-grill/             # (merge with existing bbq/ folder)
├── sides/                          # Side dishes, accompaniments
├── baked_goods/                    # (existing — expand to include new cookies/donuts)
├── desserts/                       # Cakes, sweet pastries (separate from baked goods)
├── condiments-and-preserves/       # Chutneys, pickles, sauces, gravy
├── drinks/                         # (existing — mulled wine, cocktails)
└── stamppot/                       # (keep as-is — it's a coherent collection)
```

---

## Recipe Assignments by Proposed Category

### 🍲 soups/
- `Erwtensoep_variation1.md` (Dutch split pea)
- `Erwtensoep_variation2.md` (Dutch split pea variation)
- `cranberry-carrot-soup.md`
- `barszcz_czerwony.md` (Polish red borscht)
- `courgette_soup.md` (Italian-style)
- `louisiana_gumbo.md` (Cajun)
- `red_lentil_soup.md` (Dutch-style)
- `thanksgiving_soup.md` (pumpkin curry)

### 🥗 salads/
- `herring_under_a_fur_coat.md` (Russian layered salad)
- `cucumber_sunomono.md` (Japanese)
- `couscous_salad.md` (Middle Eastern herb)
- `quince_pumpkin_eggplant_quinoa_salad.md` (warm salad)
- `spinach_rucola_chicken_salad.md` (meal salad)
- `spinach_gomaae.md` (Japanese spinach sesame)
- `ceviches/jackfruit_ceviche.md`

### 🍖 mains/dutch/
- `captains dinner.md`
- `Hachee.md`
- `nasi-goreng.md`
- `witlof_met_ham_en_kaas.md`
- `belgisch_stoofvlees_met_bier_en_ontbijtkoek.md` *(Belgian but Dutch cooking tradition)*
- `cauliflower_casserole_weesperflat_special.md`
- `goulash.md` *(Dutch home version)*

### 🍖 mains/polish/
- `bigos.md` (hunter's stew)
- `barszcz_czerwony.md` *(also fits soups/)*
- `kotlety_rybne_salmon_fishcakes.md`
- `pierogi_dough.md` *(fragment — move when complete)*
- `latke_potato_pancakes.md` *(Jewish-Polish tradition)*

### 🍖 mains/eastern-european/
- `goulash.md` (Hungarian origin)
- `hungarian_goulash.md` (slow-cooker Hungarian)
- `herring_under_a_fur_coat.md` (Russian) *(also fits salads/)*
- `Georgian_eggplant_rolls.md` (Georgian)
- `georgian_shashlik.md` (Georgian)
- `sultans_delight_hunkar_begendi.md` (Turkish)
- `mousaka.md` (Greek)

### 🍖 mains/french-european/
- `best_ratatouille.md` (Provençal)
- `tarte_flambe.md` (Alsatian)
- `tartiflette.md` (Savoyard)
- `fennel_lemon_risotto.md` *(Italian but fits here)*
- `pumpkin_risotto.md` *(Italian)*
- `soft_boiled_eggs_halibut_dill_sauce.md` (Scandinavian)
- `bolognese_sauce.md` (Italian)

### 🍖 mains/mediterranean/
- `shakshuka.md` (Israeli/Levantine)
- `mousaka.md` (Greek) *(also fits eastern-european/)*
- `tapenade.md` *(condiment — move to condiments)*
- `Georgian_eggplant_rolls.md` *(also fits eastern-european/)*

### 🍖 mains/middle-eastern-north-african/
- `moroccan_lamb_stew.md`
- `moroccan_lamb_pumpkin_pie.md`
- `shakshuka.md` *(also fits mediterranean/)*
- `couscous_salad.md` *(also fits salads/)*
- `sultans_delight_hunkar_begendi.md` *(also fits eastern-european/)*

### 🍖 mains/asian/
- `gyoza.md` (Japanese)
- `spinach_gomaae.md` (Japanese) *(also fits salads/)*
- `cucumber_sunomono.md` (Japanese) *(also fits salads/)*
- `roast_monkfish_sake_broth.md` (Japanese-French fusion)
- `nasi-goreng.md` *(also fits dutch/ — it's a Dutch-Indonesian classic)*

### 🍖 mains/american/
- `carne_asada.md` (Tex-Mex)
- `chilli_con_carne.md` (Tex-Mex)
- `bourbon_balsamic_beef_roast.md` (American)
- `louisiana_gumbo.md` (Cajun) *(also fits soups/)*
- `turkey_roasting_guide.md` (Thanksgiving)
- `turkey_stuffing.md` (Thanksgiving)

### 🔥 mains/bbq-and-grill/ (merge bbq/ here)
- `bbq/BBQ-fried-halved-chicken.md`
- `bbq/Chinese_BBQ_pork.md`
- `bbq/bbq-smoked-beef-brisket.md`
- `bbq/burgers.md`
- `carne_asada.md` *(also fits american/)*
- `georgian_shashlik.md` *(also fits eastern-european/)*
- `smoked-stuffed-pumpkins.md`
- `prawns_pineapple_skewers.md`

### 🥗 sides/
- `buttermilk_sweet_cornbread.md`
- `turkey_stuffing.md` *(also fits american/)*
- `wild_mushroom_gravy.md`

### 🍞 baked_goods/ (expand existing)
- `baked_goods/Havermoutkoekjes.md`
- `baked_goods/Kerstkransjes.md`
- `baked_goods/Zandkoekjes.md`
- `baked_goods/chocolate_chip_cookies.md`
- `baked_goods/scones.md`
- `baked_goods/soda_bread.md`
- `Paasbrood.md` (Easter bread)
- `Pizza.md`
- `buttermilk_sweet_cornbread.md` *(also fits sides/)*
- `fluffy-pancakes.md`
- `tarte_flambe.md` *(also fits french-european/)*

### 🍰 desserts/
- `chocolate_chip_pudding_cookies.md`
- `ciasto_serowo_makowe.md` (Polish poppy cheesecake)
- `matcha_banana_donuts.md`
- `appetizer_squash_muffins.md` *(savory — could stay in sides/)*
- `buckwheat_quiche.md` *(savory — could also be mains/)*

### 🧂 condiments-and-preserves/
- `tapenade.md`
- `green_tomato_chutney.md`
- `ogorki_kiszone.md` *(also fits pickling/)*
- `pickling/pickled_wild_mushrooms_r1.md`
- `wild_mushroom_gravy.md` *(also fits sides/)*

### 🍷 drinks/ (keep as-is)
- `drinks/martins-mulled-wine.md`
- `drinks/[cocktail]bourbon-renewal.md`
- `gluhwein.md` *(merge or cross-reference with martins-mulled-wine)*

### 🥔 stamppot/ (keep elke-dag-stamppot-feb2021/ as-is)
All 28 dag-XX stamppot entries — this is a coherent standalone collection.
Rename folder from `elke-dag-stamppot-feb2021/` to `stamppot/` for clarity.

### 🫙 apricot_rub_slow_roast_lamb.md
- Fits: `mains/eastern-european/` or `mains/bbq-and-grill/` (slow-roast oven)

---

## Tagging System (for cross-referencing without moving files)

Rather than a strict folder hierarchy (where many recipes belong in 2+ places),
consider enriching the `_italic tag_` metadata at the top of each recipe to
enable future index/search use. Proposed tag taxonomy:

**Cuisine tags:**
`_Dutch_`, `_Belgian_`, `_French_`, `_Alsatian_`, `_Savoyard_`, `_Italian_`,
`_Greek_`, `_Turkish_`, `_Georgian_`, `_Russian_`, `_Polish_`, `_Hungarian_`,
`_Moroccan_`, `_North-African_`, `_Israeli_`, `_Middle-Eastern_`, `_Japanese_`,
`_Indonesian_`, `_Chinese_`, `_American_`, `_Cajun_`, `_Tex-Mex_`, `_British_`,
`_Scandinavian_`, `_Canadian_`, `_fusion_`

**Course tags:**
`_soup_`, `_salad_`, `_appetizer_`, `_main_`, `_side_`, `_dessert_`,
`_baked-goods_`, `_condiment_`, `_preserve_`, `_drink_`

**Method tags:**
`_slow-cook_`, `_braise_`, `_stew_`, `_BBQ_`, `_grill_`, `_charcoal_`, `_oven_`,
`_stovetop_`, `_pan-fried_`, `_risotto_`, `_steam_`, `_fermentation_`,
`_no-cook_`, `_quick_`

**Dietary tags:**
`_vegetarian_`, `_vegan_`, `_gluten-free_`, `_dairy-free_`, `_fish_`, `_seafood_`,
`_beef_`, `_pork_`, `_lamb_`, `_poultry_`

---

## Questions for Your Review

1. **Stamppot folder** — rename `elke-dag-stamppot-feb2021/` → `stamppot/`? Or keep the date in the name for historical context?
2. **Dutch/Belgian split** — should Belgian recipes (stoofvlees) sit in `dutch/` (as part of a broader "Low Countries / Dutch culinary tradition" folder) or have a separate `belgian/` folder?
3. **Duplicates** — `goulash.md` (Dutch home version) and `hungarian_goulash.md` (slow-cooker version) are two distinct recipes. Agree to keep both?
4. **Glühwein** — merge `gluhwein.md` and `martins-mulled-wine.md` into a single recipe (or keep as separate variants)?
5. **Folder move or tag-only?** — Would you prefer to physically reorganize files into subfolders, or keep everything flat at root level and rely purely on tags for organization?
6. **BBQ folder** — merge existing `bbq/` into a broader `mains/bbq-and-grill/` folder, or keep as a top-level folder?
