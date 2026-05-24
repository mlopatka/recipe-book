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

### `gluhwein.md`
- [ ] Verify inferred instructions (heating time, whether to simmer or steep)
- [ ] Verify brandy proportion (50 cl brandy to 1.5 L wine is quite generous)
- [ ] Cross-reference with `martins-mulled-wine.md` — may be a near-duplicate

### `mousaka.md`
- [ ] **Béchamel sauce recipe is completely missing** — needs quantities for butter, flour, milk and full method
- [ ] Verify inferred layering and baking instructions
- [ ] Add prep time and baking temperature

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

## Recipes Missing Attribution

These recipes clearly came from external sources but the URL or author was not captured:

- [ ] `courgette_soup.md` — source unknown
- [ ] `barszcz_czerwony.md` — source unknown
- [ ] `best_ratatouille.md` — source unknown (style suggests BuzzFeed Tasty)
- [ ] `bolognese_sauce.md` — source unknown
- [ ] `bourbon_balsamic_beef_roast.md` — source unknown
- [ ] `buttermilk_sweet_cornbread.md` — source unknown
- [ ] `chilli_con_carne.md` — source unknown
- [ ] `green_tomato_chutney.md` — source unknown
- [ ] `moroccan_lamb_stew.md` — source unknown
- [ ] `pan_seared_lemon_basil_scallops.md` — source unknown
- [ ] `prosciutto_wrapped_figs_blue_cheese.md` — source unknown
- [ ] `quince_pumpkin_eggplant_quinoa_salad.md` — source unknown
- [ ] `spinach_rucola_chicken_salad.md` — source unknown
- [ ] `tarte_flambe.md` — source unknown (style suggests Saveur magazine)
- [ ] `tartiflette.md` — source unknown
- [ ] `thanksgiving_soup.md` — source unknown
- [ ] `turkey_stuffing.md` — source unknown
- [ ] `turkey_roasting_guide.md` — source unknown
- [ ] `wild_mushroom_gravy.md` — source unknown
- [ ] `gluhwein.md` — source unknown
- [ ] `hungarian_goulash.md` — source unknown (style suggests Dr. Axe website)
- [ ] `bigos.md` — source unknown
- [ ] `appetizer_squash_muffins.md` — source unknown
- [ ] `georgian_shashlik.md` — source unknown

---

## Duplicate / Overlap Notes

- **`apricot_rub_slow_roast_lamb.md`** — merged from `henrik_lamb.rtf` + `lamb_roast_rub_recipe.rtf` (both were the same recipe at different stages of note-taking).
- **`moroccan_lamb_pumpkin_pie.md`** — merged from `moroccan_lamb_pie.rtf` + `morrocanPumpkinLambPie.rtf` (two versions of the same recipe).
- **`gluhwein.md`** — overlaps significantly with the existing `martins-mulled-wine.md` at root level. Consider merging or cross-referencing.
- **`hungarian_goulash.md`** and **`goulash.md`** (already at root) — two different goulash recipes. Consider cross-referencing.

---

## Unconvertable Files (see unconvertable_recipes.txt)
- `unformatted/Hong Kong Egg Tarts - The Woks of Life.pdf` — empty PDF extraction
- `unformatted/maple_walnut_salmon.jpg` — image file, no text
- `unformatted/ogorki_kiszone_kristina.jpeg` — image file, no text
