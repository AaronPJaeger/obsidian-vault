# Library (Macros plugin)

Marcus logs foods/recipes here for the Obsidian **Macros** plugin.

**Storage path:** `Nutrition/Library`  
**Daily logs:** `Nutrition/Daily`

## How it works
1. Food files in this folder (`Nutrition/Library`) have frontmatter (`calories`, `protein`, `fat`, `carbs`, `serving_size`).
2. Daily log: put a `macros` code block in a note under `Nutrition/Daily` (date id `YYYY-MM-DD`) and add foods/meals by name.
3. Recipe meals are **per-serving estimates** (`source: marcus_estimate`) — good enough for deficit coaching; refine with live search for packaged items.

## Daily log example
````markdown
```macros
id: 2026-09-06

meal: Breakfast @07:00
- Wake-up Wrap: 1
- Protein Smoothie: 1

meal: Lunch @12:30
- Instant Pot Chili (serving): 1

meal: Dinner @18:30
- Butter Chicken Bowl (serving): 1
```
````

## Targets (locked)
- Weight now: **~190 lb** → goal **170 lb**
- Calories: **2,100 kcal/day** (mild deficit)
- Protein: **170 g** (priority — protects muscle)
- Fat: **65 g**
- Carbs: **~210 g** (fills the rest)

In Macros settings → Nutrition Targets, set those numbers (or start from High Protein / Cutting and edit).

Macros plugin Settings → **Storage folder** = `Nutrition/Library`.

Hit protein first. Pizza/free-food days: still log them; pull calories from elsewhere that day, don’t “save up” all week then blow it.
