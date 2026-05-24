# Recipe Todo List
## Converted Recipes Requiring Correction or Completion

This file tracks all converted recipes that could not fully populate the canonical
recipe schema due to missing or incomplete information in the source files.
Use this as a checklist to fill in gaps manually.

---

### Schema reference (what a complete recipe needs)
- [ ] Title (H1, native language if applicable)
- [ ] English subtitle (H2, if non-English title)
- [ ] Tags (_cuisine_, _dietary_, _method_)
- [ ] Preparation time
- [ ] Servings / portions
- [ ] Complete ingredients list (with quantities for every item)
- [ ] Complete step-by-step preparation instructions
- [ ] Closing line
- [ ] Attribution / source link (if known)

---

## Recipes with Missing Instructions

These recipes had **ingredients only** in the source file. Inferred/placeholder
instructions have been written but must be verified.

### `louisiana_gumbo.md`
- [ ] Verify inferred instructions (roux method, order of operations, timing)
- [ ] Add prep time
- [ ] Add source/attribution if known

### `prawns_pineapple_skewers.md`
- [ ] Verify inferred instructions (grilling time, whether to marinate fish and fruit separately)
- [ ] Add source/attribution if known

### `bolognese_sauce.md`
- [ ] Verify inferred instructions (resting time, wine reduction specifics)
- [ ] Add prep time
- [ ] Add source/attribution if known

### `moroccan_lamb_stew.md`
- [ ] Verify inferred instructions (liquid quantity, stewing time)
- [ ] Add prep time
- [ ] Add source/attribution if known

### `bigos.md`
- [ ] Verify inferred instructions
- [ ] Add prep time
- [ ] Clarify hot sauce quantity and type
- [ ] Consider adding traditional spices (bay leaves, allspice, juniper berries, red wine)

### ~~`gluhwein.md`~~ ✅ merged into `drinks/martins-mulled-wine.md`
- [x] Merged — brandy proportion noted in the recipe; instructions from Martin's version used as the canonical method.

### ~~`mousaka.md`~~ — deleted
Removed from repo: béchamel recipe was entirely absent from the source file, making the conversion too incomplete to be useful.

### `wild_mushroom_gravy.md`
- [ ] Verify inferred instructions (reduction time, consistency)
- [ ] Add prep time
- [ ] Confirm whether turkey drippings or stock is preferred base

---

## Recipes with Incomplete Ingredients

### `buckwheat_quiche.md`
- [ ] **Pine nuts** — mentioned in the preparation steps but absent from the ingredients list. Add quantity (suggested: 2–3 tablespoons).

### `red_lentil_soup.md`
- [ ] **Rosemary sprig** — mentioned in preparation but absent from the ingredients list. Add quantity.

---

## Recipes with Truncated or Unclear Instructions

### `tartiflette.md`
- [ ] Step 7 in the source file was truncated ("then spoon the remaining la..."). Step 8 has been inferred — **verify the layering method for crème fraîche**.

### `appetizer_squash_muffins.md`
- [ ] Baking time and temperature were not in the source — inferred as 180°C for ~20 mins. **Verify before serving at an event**.
- [ ] Add prep time (total).

### `ciasto_serowo_makowe.md`
- [ ] Source says "bake for 10 minutes at 170°C" but this seems truncated. **Verify whether a water bath is needed**, and whether the tin should be covered.
- [ ] Confirm the baking sequence is correct (10 mins at 170°C → 50 mins at 160°C).

### `morrocanPumpkinLambPie.rtf` → `moroccan_lamb_pumpkin_pie.md`
- [ ] Source had truncated oven temperature ("Preheat oven to 2g"). Confirmed as 180°C from context — **verify this**.
- [ ] Clarify: use quince paste OR sambal badjak, or both? Two source files gave different guidance.

### `thanksgiving_soup.md`
- [ ] Red curry paste quantity (125–200 ml) is a very wide range — **verify preferred heat level**.

---

## Recipes with Incomplete Serving / Timing Information

### `courgette_soup.md`
- [ ] Add source/attribution if known.

### `sultans_delight_hunkar_begendi.md`
- [ ] **Missing the lamb stew topping** that classically goes with Hünkar Beğendi. The source file contained the eggplant base only. Consider adding a slow-braised lamb recipe as the main topping.

### `pierogi_dough.md`
- [ ] **This is a dough-only fragment** — no filling recipe or assembly instructions were recorded.
- [ ] Add a filling recipe (potato-cheese, sauerkraut-mushroom, or meat) to complete the recipe.
- [ ] Add prep time.

### `apricot_rub_slow_roast_lamb.md`
- [ ] **No quantities** for rub ingredients (how many apricots, how much parsley, how much oil). Add when verified.
- [ ] Compiled from two overlapping source files (`henrik_lamb.rtf` and `lamb_roast_rub_recipe.rtf`).

### `turkey_roasting_guide.md`
- [ ] **Missing quantities** for sage butter, maple glaze (maple syrup amount, bacon drippings amount) and gravy (flour amount).

---

## Recipes Missing Attribution ✅

Source attribution resolved for all recipes — either credited to Martin Lopatka, marked as traditional, or noted as `source: unknown` where origin is lost or too adapted to attribute:

- [x] `courgette_soup.md` — source unknown
- [x] `barszcz_czerwony.md` — source unknown
- [x] `best_ratatouille.md` — source unknown
- [x] `bolognese_sauce.md` — source unknown
- [x] `bourbon_balsamic_beef_roast.md` — source unknown
- [x] `buttermilk_sweet_cornbread.md` — source unknown
- [x] `chilli_con_carne.md` — source unknown
- [x] `green_tomato_chutney.md` — source unknown
- [x] `moroccan_lamb_stew.md` — source unknown
- [x] `pan_seared_lemon_basil_scallops.md` — source unknown
- [x] `prosciutto_wrapped_figs_blue_cheese.md` — source unknown
- [x] `quince_pumpkin_eggplant_quinoa_salad.md` — source unknown
- [x] `spinach_rucola_chicken_salad.md` — source unknown
- [x] `tarte_flambe.md` — source unknown
- [x] `tartiflette.md` — source unknown
- [x] `thanksgiving_soup.md` — original recipe by Martin Lopatka
- [x] `turkey_stuffing.md` — original recipe by Martin Lopatka
- [x] `turkey_roasting_guide.md` — original recipe by Martin Lopatka
- [x] `wild_mushroom_gravy.md` — original recipe by Martin Lopatka
- [x] `gluhwein.md` — merged into `drinks/martins-mulled-wine.md`, deleted
- [x] `hungarian_goulash.md` — source unknown
- [x] `bigos.md` — traditional Polish recipe, no source needed
- [x] `appetizer_squash_muffins.md` — source unknown
- [x] `georgian_shashlik.md` — source unknown

---

## Duplicate / Overlap Notes

- **`apricot_rub_slow_roast_lamb.md`** — merged from `henrik_lamb.rtf` + `lamb_roast_rub_recipe.rtf` (both were the same recipe at different stages of note-taking).
- **`moroccan_lamb_pumpkin_pie.md`** — merged from `moroccan_lamb_pie.rtf` + `morrocanPumpkinLambPie.rtf` (two versions of the same recipe).
- [x] **`gluhwein.md`** — **merged** into `drinks/martins-mulled-wine.md` as a two-variant recipe (Martin's 4-serving version + large party batch). `gluhwein.md` deleted from root.
- **`hungarian_goulash.md`** and **`goulash.md`** (already at root) — two different goulash recipes. Consider cross-referencing.

---

## Unconvertable Files (see unconvertable_recipes.txt)
- `unformatted/Hong Kong Egg Tarts - The Woks of Life.pdf` — empty PDF extraction
- `unformatted/maple_walnut_salmon.jpg` — image file, no text
- `unformatted/ogorki_kiszone_kristina.jpeg` — image file, no text
