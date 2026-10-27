# Key to Infinity · Divine Journey 2 2.23.4

**Preview: 49 dependencies awaiting verification.** The research route remains incomplete.

An English viewer with ingredients → process → products, search, navigation history, an expandable chain, focused route explorer and material planner. The selected route contains **4,748 resources and 2,007 recipes**; the browsable catalog includes **42,267 resources and 36,964 processes**.

Cards, ingredient chains and search results display embedded pack texture previews where the item, variant or fluid mapping has been verified. Other entries use explicit type symbols. A texture preview is a visual aid, not proof that a resource is obtainable; icon coverage is reported separately in the package state.

Cards, search, ingredient chains and the map now use 24,531 direct resource texture/model previews and 1,867 marked OR candidate previews. Generic resource icons on the selected map decreased from 1,585 to 101; 8,324 catalog entries gained previews. This includes native chemical/singularity colors, vanilla variants, Chisel, Underground Biomes, magic components, fluids, cables and registered machine items. Blood Magic forge/crystallizer previews are rendered from their native OBJ geometry and UV textures.

**Animate icons** switches between motion and visible static frames. Only visible icons animate; hidden tabs pause. Reduced-motion settings start static. OR previews retain an OR badge. Base texture previews are identified in tooltips; unknown procedural geometry, undisclosed item states and protected narrative assets retain explicit type symbols.

![Interactive route explorer](preview.png)

## Open the diagram

[**Open the diagram in your browser**](https://luisfsandsilva-star.github.io/dj2-key-to-infinity-flowchart/).

Download the [updated preview package](https://github.com/luisfsandsilva-star/dj2-key-to-infinity-flowchart/releases/tag/dj2-2.23.4-preview-20261027-r14), extract it and open `index.html` in a modern browser. It works offline without a server. GitHub displays HTML source files as code; use the download to open the viewer.

- **By recipe:** select an ingredient to follow its crafting chain.
- **Expandable chain:** open only the branches you want to inspect.
- **Focused chain:** explore 1, 2 or 3 directed hops around the selection. The nearest 360 nodes are shown for large hubs; select a node to continue.
- **Dim unrelated:** fade cards, text, icons and badges outside the selected scope. Toggle it off to restore normal opacity. Choose direct connections or the dependency chain; it also works far zoomed out.
- **Whole route / Areas:** keep the full route accessible, or expand navigation groups such as Chemistry, Electronics, Magic and Infrastructure. These are navigation groups, not progression tiers.
- **Compact OR:** collapse transparent alternative helpers while retaining every option in the inspector. OR choices affect the material plan; the map retains the researched route.
- **Recipe inspector:** select map nodes to read ingredients, quantities, grids and conditions without leaving the map. Whole-route selections preserve pan and zoom.
- **Progress and paths:** record inventory quantities in this browser, highlight a path to Key to Infinity, or show branches with unverified recipes.
- **Material plan:** enter a target quantity, deduct recorded inventory, inspect shared batch counts and reusable tools, and export CSV. Random, symbolic and unsupported routes remain explicit unresolved boundaries.
- **Deferred loading:** search is available over the full catalog, while catalog rows, textures and animations decode when needed. Planning runs in a temporary worker; the offline HTML remains self-contained.
- **Search:** find resources, fluids and machines throughout the catalog, with icons alongside results.

Recipe cards retain quantities per run. The material planner accumulates demand along selected producers and combines shared requirements before rounding batches. Its totals remain partial at unknown or random yields; conditions, world access and tool durability still apply. Choose one OR alternative at a time. Inventory and display preferences are stored locally in this browser.

Energy Cube crafting includes an expandable sequence of intermediate crafts with links to their grids. Capture routes, lunar materials, Enchanter operations and sunlight charging retain their conditions and quantities. The cold boiler includes construction layers, and the Oblivion Catalyst ritual shows the living sacrifice. Verified acquisitions remain available in the catalog even when the main route does not select them. The physical Soul Snare, first Tartaric Gem and RAW64 charging chains retain costs, randomness, carrier limits and unclaimed remnants.

The Totemic and Roots chain includes Cedar Saplings, Buffalo with actual maturation, Parrots and Eagles, Baykok summoning and Wildwood cultivation. Cards explain ceremony selection, instruments, costs, minimum quantities and random yields.

The Hemp source shows natural seeds, paid cultivation and the distribution of 0–3 fibers per harvest. Fluid Transposer and Arboreal Extractor factory configurations are corroborated against local extraction outputs.

Cards include the Nether Star, the Asorah fight and the Powerstone search in an Abyssal Stronghold. Athame sources show their random 0–4 yield; the four Blood Magic elemental reagents use a physical RAW64 gem with minimum 8 and drain 4, leaving its remainder unclaimed.

This preview also includes Coralium, Abyssal Essence through the Drain Staff, paid Aether access and Aerogel, the 5 × 5 Sigil of Purity grid, Watcher and Ancient Entity fights, random Inferium, Nether Prosperity, Industrial Diamond through an explosion and wet Fluix conversion. Cards retain each operation's physical debits, yields and requirements. Initial Aether access is paid once and retained for later operations in the same world with the same player.

## Preview scope

The **2,007 selected recipes** retain their source operands, and the **7,863 route edges** satisfy a strictly descending height. There are **0 selected partial recipes**, **0 selected unresolved registry entries** and **49 pending dependencies**. A pending dependency is not presented as a free raw material. Selection and auditing reject incomplete processes as producers; catalog cards that have not been corroborated show their pending status.

Recipes have been compared against local extraction from pack 2.23.4 and mechanical evidence from its classes and configuration. Records omitted by the exporter retain their declared mechanical source. Each process's stated conditions and prior construction are part of its scope; this preview does not claim complete dependency closure.

The protected narrative note is excluded. Mods, worlds, game logs and personal configuration are not distributed.

## Files

- `index.html`: self-contained viewer with its filtered data and embedded icons.
- `viewer-data.json.gz`: the same public viewer data.
- `status.json`: package version, language, status, counts, icon coverage and hashes.
- `README.txt`: usage instructions and scope.

Original pack: [Divine Journey 2, version 2.23.4](https://github.com/Divine-Journey-2/Divine-Journey-2/releases/tag/2.23.4). Mod names and content belong to their respective authors.

Map labels and icons remain visible down to 18% zoom. Connections for the selected node remain visible at every zoom level; selecting a node above that detail threshold preserves the current zoom.
