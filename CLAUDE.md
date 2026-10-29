# Floor plan workflow

Floor plans in this repo are made in a fixed order, from files the user provides.

## Inputs (provided by the user, in this order)

1. **Reference style** → `floorplans/1-reference-style/`
   A sample floor plan whose look we copy: line weights, wall fills, colours,
   fonts, label placement, dimension style, north arrow, legend.
2. **Template** → `floorplans/2-template/`
   The sheet/page layout the plan goes on (title block, borders, logo area).
3. **Assets** → `floorplans/3-assets/`
   The furniture, fixtures, doors, windows, symbols and icons to use.
4. **Floor plan to create** → `floorplans/4-floor-plan-to-create/`
   The actual layout to draw (sketch, measurements, existing plan, notes).

Finished plans go in `floorplans/output/`.

## Rules

- Use ONLY the user's assets. Never draw, generate or substitute your own
  furniture, fixtures, symbols or icons. Place, scale and rotate the provided
  files as they are.
- If the plan needs an asset that was not provided, stop and ask for it.
  Do not make a stand-in.
- Match the reference style; do not invent a new one.
- Put the plan on the provided template without changing the template's layout.
- Do not start drawing until all four inputs are in. If one is missing, ask for it.
- Before finishing, list which asset files were used where, and flag anything
  that was unclear in the plan (missing dimensions, unlabelled rooms).
