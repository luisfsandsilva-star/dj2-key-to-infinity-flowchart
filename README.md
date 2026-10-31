# Key to Infinity · Divine Journey 2 2.23.4

[**Open the interactive diagram**](https://luisfsandsilva-star.github.io/dj2-key-to-infinity-flowchart/?v=r25).

**Work in progress.** The selected core route has **5 unresolved boundaries**, 5,742 resource identities and 2,496 recipes. The full ingredient graph has **5,623 nodes and 10,259 connections**, including **5 unresolved resources and 0 unverified process previews**. Connected previews do not establish that their outputs are obtainable.

The English catalogue contains 44,039 resources and 38,857 processes. Items, fluids and machines have icons in search and on the map. Catalogue details, textures and native animations decode when needed.

Download the [r25 offline package](https://github.com/luisfsandsilva-star/dj2-key-to-infinity-flowchart/releases/tag/dj2-2.23.4-preview-20261031-r25), extract it and open `index.html` in a modern browser. The viewer works offline. GitHub displays repository HTML as source; use the live link or download.

- **Full chain to Key** opens the objective. Choose **Full chain** for unlimited ingredient depth, or 1–100 hops for a smaller view. Every catalogue item or fluid can be a starting point.
- **Ingredients** follows each selected producer and its inputs. **Ingredients and uses** also follows downstream uses. Byproducts are displayed separately.
- **Compact OR** collapses alternative helpers; the inspector retains the available choices. **Compact OR** and **Pending branches** preserve zoom, pan and surviving node positions.
- **Dim unrelated** fades nodes outside the selected connection scope. The inspector shows ingredients, quantities, crafting grids and operating conditions.
- **Whole route / Areas** provide alternate navigation. Groups describe mods and processes.
- **Material plan** combines shared demand, reusable tools, owned inventory and selected OR choices. Finite claims keep their owner limits; unknown yields and shortages remain unresolved. CSV export is available.
- **Animate icons** uses native animation sheets. Static frames remain available, only visible icons animate, and reduced-motion preferences start static. Base previews and unknown symbols are labeled.

This update preserves explicit initial-stock boundaries and shows dependency-cycle notices in the inspector. Candidate recipes remain available, while material planning requires the actual stock or earned context you enter. It adds paid Cthulhu Coin engraving, native Aether Blueberry and Golden Amber harvesting, and exact Marble Pillar carving. It also repairs the Primal Crusher inputs to use the actual paid infused Elemental tools produced upstream, retaining all original ingredients and its 400000 RF cost. Existing world expeditions, Dragon operations, Astral Crystal uses, empty Drum upgrades, machine inputs and elemental fusion paths remain available.

Galactic Ingot now has a coordinated selected path. Every operation retains its ingredients, machine, power, world access, native conditions, ownership, durability and output limits. The five remaining core boundaries are listed in the viewer and remain unresolved; no free material or assumed quest progress was added to close them.

The full graph records 5 explicit initial-stock boundaries and 3 structural dependency-cycle groups. A cycle does not imply that every member is unobtainable; inspect its starting stock and recipe choices.

The selected route and the full catalogue have different scopes. An additional catalogue producer does not automatically replace every selected route. The full graph has no depth or node cap. Conditional expeditions and world operations begin with guaranteed yield zero; a successful branch does not promise a finite successful batch or refund failed attempts.

Navigation retains at most three ingredient graph contexts and two combined contexts. Superseded planner workers are canceled, workers receive calculation fields, and animation frame caches are bounded. Generation releases completed catalogue indexes before processing icons and avoids copying entire indexes for process aliases. Heavy build stages run in series with the previous memory limits.

Dark Tank upgrades remain separate: 16,000 → 32,000 → 64,000 → 128,000 mB. Recipe quantities are per operation, not a complete accumulated bill of materials. Random yields, finite rewards, world access, machine power and operating conditions still apply. Inventory and display preferences stay in the current browser.

Validation checked all 2,496 selected recipe bodies, strictly descending selected edges, complete untruncated graph traversal and exact reconstruction of the filtered offline data. No partial recipe or unresolved registry entry is admitted as a selected producer. All additional choices were validated against current candidates. Model, planner, loader and transport checks are automated; this terminal session had no new visual browser pass.

![Viewer interface from an earlier preview](preview.png)

`index.html` is the self-contained viewer; `viewer-data.json.gz` is its complete filtered data; `status.json` records counts and hashes; `README.txt` contains offline instructions. Protected narrative content, raw snapshots, mod binaries, worlds and personal configuration are excluded.

Original pack: [Divine Journey 2 2.23.4](https://github.com/Divine-Journey-2/Divine-Journey-2/releases/tag/2.23.4). Mod names and content belong to their respective authors.
