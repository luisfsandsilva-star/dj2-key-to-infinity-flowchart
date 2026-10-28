# Key to Infinity · Divine Journey 2 2.23.4

[**Open the interactive diagram**](https://luisfsandsilva-star.github.io/dj2-key-to-infinity-flowchart/?v=r17).

**Work in progress.** The core selected route has **29 unresolved boundaries**, 4,998 resource identities and 2,141 selected recipes. The full ingredient graph contains **10,049 nodes and 17,944 connections**, including **166 unresolved resource boundaries and 19 unverified process previews**. These are different scopes; connected previews do not establish that their outputs are obtainable.

The English catalogue contains 43,911 resources and 38,648 processes. Search includes item, fluid and machine icons. The viewer is a single offline HTML file; catalog details, textures and animations decode when needed.

Download the [r17 preview package](https://github.com/luisfsandsilva-star/dj2-key-to-infinity-flowchart/releases/tag/dj2-2.23.4-preview-20261027-r17), extract it and open `index.html` in a modern browser. GitHub displays repository HTML as source; use the live link or the downloaded file.

- **Full chain to Key** opens the objective. Choose **Full chain** for unlimited ingredient depth, or 1–100 hops for a smaller view. Every catalogue item or fluid can be a starting point.
- **Ingredients** follows each selected producer and its required inputs. **Ingredients and uses** adds downstream uses. Byproducts are not extra ingredients.
- **Compact OR** collapses alternative helpers; the inspector retains all advertised choices. **Compact OR** and **Pending branches** preserve zoom, pan and surviving node positions.
- **Dim unrelated** fades nodes outside the selected connection scope. The inspector retains ingredients, quantities, crafting grids and conditions.
- **Whole route / Areas** provide alternate navigation. Groups describe mods and processes, not progression tiers.
- **Material plan** combines shared demand, reusable tools, local owned inventory and selected OR choices. Finite quest rewards and operations keep their owner limits; shortages remain unresolved. CSV export is available.
- **Animate icons** uses native texture animation sheets. Static frames remain available, only visible icons animate, and reduced-motion preferences start static. Base previews and unknown symbols are explicitly identified.

Repeated navigation now keeps at most three ingredient graph contexts and two combined contexts. Evicted graphs rebuild with the same geometry. New calculations and closing the planner cancel previous workers; workers receive calculation fields rather than display/source copies. Unused duplicate ingredient records were removed from presentation data while ingredient quantities, grids and private evidence remain intact. These changes reduce memory retention without limiting chain depth.

This update adds or corrects native processing for Shulker capture, empty tank upgrades, pressurized tanks, Robit and its Personal Chest, Rough Iron Mesh, Pickaxe Head Casts, raw Buffalo Meat, all five Ayeraco statues, cabbage access, Gaean Gem, Marimorphosis, paid fusion and reactor waste, Snow Globe charging, and exact Arcanium/Conducted Impetus conditions. Tank and Robit intermediate crafts appear as individual steps.

Some first-state dependencies remain open. Examples include the first Stone Pickaxe Head, actual 300-Impetus charging infrastructure, and paid access to warded Ancient Glyphed Stone. Existing biome settings, preview outputs or a plain uncharged item do not supply these states. The map keeps missing resources and unverified processes visible.

Per-run amounts are not a complete accumulated bill of materials. Random yields, unknown quantities, durability, finite rewards, actual world access and operating conditions still apply. Inventory and display preferences are stored in the current browser.

The selected route was checked against pinned local extraction from pack 2.23.4: all 2,141 selected recipe bodies are unchanged, all 8,369 selected edges descend strictly, and no partial recipe or unresolved registry entry is admitted as a producer. Offline staged data reconstructs the complete filtered projection exactly. Model, planner, loader and transport checks are automated; this terminal session had no connected browser for a new visual pass.

![Viewer interface from an earlier preview](preview.png)

`index.html` is the self-contained viewer; `viewer-data.json.gz` is its complete filtered data; `status.json` records scope, counts and hashes; `README.txt` contains offline instructions. Protected narrative content, raw snapshots, mod binaries, worlds and personal configuration are excluded.

Original pack: [Divine Journey 2 2.23.4](https://github.com/Divine-Journey-2/Divine-Journey-2/releases/tag/2.23.4). Mod names and content belong to their respective authors.
