# Key to Infinity · Divine Journey 2 2.23.4

[**Open the interactive diagram**](https://luisfsandsilva-star.github.io/dj2-key-to-infinity-flowchart/?v=r21).

**Work in progress.** The core selected route has **13 unresolved boundaries**, 5,356 resource identities and 2,313 selected recipes. The full ingredient graph contains **8,822 nodes and 15,721 connections**, including **124 unresolved resource boundaries and 17 unverified process previews**. These are different scopes; connected previews do not establish that their outputs are obtainable.

The English catalogue contains 43,986 resources and 38,747 processes. Search includes item, fluid and machine icons. The viewer is a single offline HTML file; catalog details, textures and animations decode when needed.

Download the [r21 preview package](https://github.com/luisfsandsilva-star/dj2-key-to-infinity-flowchart/releases/tag/dj2-2.23.4-preview-20261031-r21), extract it and open `index.html` in a modern browser. GitHub displays repository HTML as source; use the live link or the downloaded file.

- **Full chain to Key** opens the objective. Choose **Full chain** for unlimited ingredient depth, or 1–100 hops for a smaller view. Every catalogue item or fluid can be a starting point.
- **Ingredients** follows each selected producer and its required inputs. **Ingredients and uses** adds downstream uses. Byproducts are not extra ingredients.
- **Compact OR** collapses alternative helpers; the inspector retains all advertised choices. **Compact OR** and **Pending branches** preserve zoom, pan and surviving node positions.
- **Dim unrelated** fades nodes outside the selected connection scope. The inspector retains ingredients, quantities, crafting grids and conditions.
- **Whole route / Areas** provide alternate navigation. Groups describe mods and processes, not progression tiers.
- **Material plan** combines shared demand, reusable tools, local owned inventory and selected OR choices. Finite quest rewards and operations keep their owner limits; shortages remain unresolved. CSV export is available.
- **Animate icons** uses native texture animation sheets. Static frames remain available, only visible icons animate, and reduced-motion preferences start static. Base previews and unknown symbols are explicitly identified.

Repeated navigation now keeps at most three ingredient graph contexts and two combined contexts. Evicted graphs rebuild with the same geometry. New calculations and closing the planner cancel previous workers; workers receive calculation fields rather than display/source copies. Unused duplicate ingredient records were removed from presentation data while ingredient quantities, grids and private evidence remain intact. These changes reduce memory retention without limiting chain depth. Animated OR previews also use a bounded decoded-frame cache during generation. An optional WebP codec failure retains the complete APNG with native frames and timing.

This revision adds the paid first-dream bootstrap: one true first visit collects five native Shiny Pearls, exports one actual five-item stack through the earned portal, restores the owner’s normal inventory and collects the same exported stack in the Overworld. It is limited to one execution per owner and world. Four Pearls go directly into the Moon Clock; one pays its Eye of the Nightmare.

Native Menril harvesting credits one guaranteed chunk from one paid owned filled log, preserving the actual placement, barehand harvest and inventory pickup. Eighteen such allocations fund the two Menril blocks required by the Logic Programmer. The selected route now includes the native paid passive reactor route to its first Cyanite.

Verified native Chisel operations retain their actual owned ore and tool inputs. A joint first RF-dimension expedition can earn Peaceful, two separately harvested shard ores carved to variants 1 and 2, and one Electrotine Ore. It uses three distinct paid Silk Drills with 600 FE of actual aggregate debits. All four outputs share one actual first dimension and its single creation allowance. Catalogue operations remain conditional on their complete physical requirements; their presence does not establish global material closure.

Unknown expedition yields start at zero, and failed attempts retain their actual costs. The full graph has no depth or node cap. All 33 additional proposed choices were checked against current candidates with no stale or rejected choices; this is not a claim of global optimality.

Explicit acquisition metadata now preserves the actual item variant, including Rare Earth at metadata 10 and Bat Wing at metadata 15. Original acquisition evidence and payment remain unchanged. Verified item icons take priority over synthetic process placeholders.

Dark Tank capacity upgrades appear separately: 16,000 → 32,000 → 64,000 → 128,000 mB. The exact capacity-only requirement uses eight fresh tanks and seven upgrades: 24 Dark Steel Ingots, 40 Dark Gems and 8 Black Glass blocks, with no fluid. The fresh tank retains its nine-slot shaped grid.

Some first-state dependencies remain open, including the first Stone Pickaxe Head and several endgame material bootstraps. Conditional Rift and expedition attempts may return zero; unknown overall probabilities do not become guaranteed planner yields. Missing resources and unverified processes remain visible.

Per-run amounts are not a complete accumulated bill of materials. Random yields, unknown quantities, durability, finite rewards, actual world access and operating conditions still apply. Inventory and display preferences are stored in the current browser.

The selected route was checked against pinned local extraction from pack 2.23.4: all 2,313 selected recipe bodies are unchanged, all 9,201 selected edges descend strictly, and no partial recipe or unresolved registry entry is admitted as a producer. Offline staged data reconstructs the complete filtered projection exactly. Model, planner, loader and transport checks are automated; this terminal session had no connected browser for a new visual pass.

![Viewer interface from an earlier preview](preview.png)

`index.html` is the self-contained viewer; `viewer-data.json.gz` is its complete filtered data; `status.json` records scope, counts and hashes; `README.txt` contains offline instructions. Protected narrative content, raw snapshots, mod binaries, worlds and personal configuration are excluded.

Original pack: [Divine Journey 2 2.23.4](https://github.com/Divine-Journey-2/Divine-Journey-2/releases/tag/2.23.4). Mod names and content belong to their respective authors.
