# biodiversity-modules-toolkit

An open-source toolkit for making, installing and observing modular bioreceptive habitat panels from locally available waste. It supports the paper *Distributed Bioreceptive Modules for Urban Ecology: An Open-Source Toolkit for Citizen Participation* 

Bioreceptive surfaces are surfaces that mosses, lichens and other small organisms can colonise. This toolkit extends an earlier institutional, robot-fabricated prototype into a DIY format that is local, low-tech, repairable and distributed, using everyday tools, kitchen equipment and low-cost 3D printing.

## Status: v0.1 (work in progress)

| Stage | Status |
|---|---|
| Material recipes (eggshell, spent coffee grounds) | Made and tested in Bir, India |
| Design files and mould files (Rhino, Grasshopper, STL) | Included |
| Fabrication notes | Included, from one production run |
| Installation / deployment | Described, **not yet field-tested** |
| Citizen-science observation | Sheet and protocol drafted, **not yet used** |
| Colonisation, durability, water resistance | **Not yet tested** |
| Reproduction by someone other than the author | **Not yet tested** |

Please treat this as a proposal, not a finished product.

## What is in the repository

```
01-materials/        recipe notes and links (eggshell, spent coffee grounds)
02-design-files/     Rhino and Grasshopper files, STL moulds
03-fabrication/      printing, casting, drying and demoulding notes
04-deployment/       installation steps (untested)
05-observation/      observation sheet, protocol, accessibility matrix
images/              photographs and diagrams
```

## Quick start

1. **Pick and source a local waste material.** The tested materials are eggshells and spent coffee grounds. Cafes and kitchens are good sources.
2. **Prepare the material** following the recipe in `01-materials/` (summary below).
3. **Prepare or adapt the mould files** in `02-design-files/`. Scale the pattern to allow for shrinkage of 7–10%.
4. **Print the moulds** in PLA (or PETG) on a low-cost FDM printer, or ask a local print shop or Fab Lab.
5. **Cast, dry and demould.** Dry indoors, out of direct sun, in a place without large temperature swings.
6. **Assemble** the modules in a frame and **install** them (see `04-deployment/`).
7. **Observe** using the sheet in `05-observation/`.

## Materials and recipes

Recipes were adapted from [Materiom](https://www.materiom.org), an open-access materials database:
- Eggshell: https://commons.materiom.org/materials-database/recipe/649c36218e0f06dcab0b7d04
- Coffee: https://commons.materiom.org/materials-database/recipe/649c36218e0f06dcab0b7d0c

**Prototype A (eggshell).** Clean, boil, dry, crush and sieve the eggshells. Mix with a 2% sodium alginate solution in a 2:1 proportion. 2 parts eggshell to 1 part alginate solution, by weight**. Pour into the PLA moulds. Spray a 10% calcium chloride solution on the top surface to cross-link the alginate.

**Prototype B (spent coffee grounds).** Sun-dry the grounds, then oven-dry at 200 °C for 15–20 minutes to remove all moisture, which helps prevent mould growth. Mix with sawdust, 2% sodium alginate solution and glycerol. 100 g SCGs, 20 g sawdust, 210 g alginate and 3 g glycerin.

Measured shrinkage: about 7–10%.

## Design and fabrication

- **Pattern:** a branching growth pattern generated in Grasshopper (Kangaroo plugin), then taken to Rhino to add the base and walls of the mould.
- **Layout:** a 3 × 3 grid of modules in a timber frame. Each square is 100 mm × 100 mm and 15 mm deep, with a 10 mm frame width. The frame dimensions were 350 mm by 350 mm, with the internal timber grid thickness of 15 mm and outer frame of 30 mm.
- **Printer used:** Creality Ender-3 V3 SE with PLA and PETG, sliced in Creality Print. The usable print area limits a mould to 220 mm × 220 mm. A 3 mm brim helped certain components. Moulds were printed within two days.
- **Parameters you can change:** installation size, grid size, module depth, timber size. Rhino and Grasshopper version 7.

## Known limitations

- Thin sections (mould width under about 5 mm) cracked on demoulding.
- Concave pockets act as mechanical locks, so demoulding is hard until the casting is completely dry.
- Some components were not fully packed at the bottom.
- The timber frame and the module grid did not match exactly.
- The samples were kept indoors and **not tested for water resistance or durability**. Eggshell and coffee samples may disintegrate in water, while moss needs sustained moisture.
- Rhino and Grasshopper are commercial software. STL files are included for anyone without them.

## Safety and hygiene

Take care with the 200 °C oven and boiling water. Wear gloves and eye protection when handling calcium chloride solution, which can irritate skin and eyes. Wash and boil food waste before use, and dry it fully to avoid mould. Wearing a mask while processing eggshells and sawdust would be advisable.

## Observation protocol (drafted, untested)

The sheet in `05-observation/` asks participants to record:
- **Site:** date, location, site ID.
- **Environment:** changes in coverage and moisture, with photographs from consistent viewpoints.
- **Colonisation:** visible mosses, lichens and other identifiable organisms. Unknown species can be recorded and marked as *uncertain* for checking by specialists.
- **Module condition:** any damage or deterioration.

Suggested frequency: monthly for the first 3–6 months, then by season. An expert can adjust this to the target species and local climate. Observations can be shared through platforms such as [iNaturalist](https://www.inaturalist.org).

## Accessibility matrix

`05-observation/` also holds the reproducibility and accessibility matrix, which lists the knowledge, skills, equipment and barriers for each production stage: design adaptation, mould fabrication, material preparation, casting and curing, installation and observation.

## Contributing

This is an open toolkit. If you reproduce or adapt it, please share your changes: record the parameters you adjusted (materials, sizes, settings), what worked and what failed, and any observations. You can contribute to these changes by emailing them to the author. 

## Licence

Unless stated otherwise, the documentation, recipes, images, design files (Rhino, Grasshopper, STL) and observation materials in this repository are licensed under CC BY-SA 4.0. Recipes adapted from Materiom remain share-alike under the same licence. Third-party material keeps its original licence. Please credit: Sneham Pandey, Biodiversity Module Toolkit [ADD: repo link].

## Citation

Sneham Pandey (2026). *Biodiversity Module Toolkit* (v0.1). https://github.com/snehampandey97-dotcom/biodiversity-modules-toolkit.

## Acknowledgements

Valldaura Labs and IAAC (Institute for Advanced Architecture of Catalonia), Fab Lab Barcelona and Materiom, and the community in Bir where the prototypes were made.

