# Key to Infinity · Divine Journey 2 2.23.4

[**Open the interactive diagram**](https://luisfsandsilva-star.github.io/dj2-key-to-infinity-flowchart/?v=r22).

**Work in progress.** The selected core route has **13 unresolved boundaries**, 5,356 resource identities and 2,313 recipes. The full ingredient graph has **8,857 nodes and 15,863 connections**, including **115 unresolved resources and 16 unverified process previews**. Connected previews do not establish that their outputs are obtainable.

The English catalogue contains 43,998 resources and 38,803 processes. Items, fluids and machines have icons in search and on the map. Catalogue details, textures and native animations decode when needed.

Download the [r22 offline package](https://github.com/luisfsandsilva-star/dj2-key-to-infinity-flowchart/releases/tag/dj2-2.23.4-preview-20261031-r22), extract it and open `index.html` in a modern browser. The viewer works offline. GitHub displays repository HTML as source; use the live link or download.

- **Full chain to Key** opens the objective. Choose **Full chain** for unlimited ingredient depth, or 1–100 hops for a smaller view. Every catalogue item or fluid can be a starting point.
- **Ingredients** follows each selected producer and its inputs. **Ingredients and uses** also follows downstream uses. Byproducts are displayed separately.
- **Compact OR** collapses alternative helpers; the inspector retains the available choices. **Compact OR** and **Pending branches** preserve zoom, pan and surviving node positions.
- **Dim unrelated** fades nodes outside the selected connection scope. The inspector shows ingredients, quantities, crafting grids and operating conditions.
- **Whole route / Areas** provide alternate navigation. Groups describe mods and processes.
- **Material plan** combines shared demand, reusable tools, owned inventory and selected OR choices. Finite claims keep their owner limits; unknown yields and shortages remain unresolved. CSV export is available.
- **Animate icons** uses native animation sheets. Static frames remain available, only visible icons animate, and reduced-motion preferences start static. Base previews and unknown symbols are labeled.

This preview adds explicit Atum heart and Silk Touch ore expeditions, all variants in the two verified Chisel ore groups, Scarab material drops, native Cow shearing for Fey Leather, and qualified Rock Crystal harvesting. The Astral Core path now includes four Celestial Crystal growth operations and eight world attunements, retaining four distinct required traits. The Network Reader factory preserves energy transferred from its paid inputs. Each operation keeps its ingredients, native conditions, ownership, wear and output limits.

The selected route and the full catalogue have different scopes. An additional catalogue producer does not automatically replace every selected route. The full graph has no depth or node cap. Conditional expeditions and world operations begin with guaranteed yield zero; a successful branch does not promise a finite successful batch or refund failed attempts.

Navigation retains at most three ingredient graph contexts and two combined contexts. Superseded planner workers are canceled, workers receive calculation fields, and animation frame caches are bounded. Generation also releases completed catalogue indexes before processing icons and avoids copying entire indexes for process aliases.

Dark Tank upgrades remain separate: 16,000 → 32,000 → 64,000 → 128,000 mB. Recipe quantities are per operation, not a complete accumulated bill of materials. Random yields, durability, finite rewards, world access, machine power and operating conditions still apply. Inventory and display preferences stay in the current browser.

Validation checked all 2,313 selected recipe bodies, strictly descending selected edges, complete untruncated graph traversal and exact reconstruction of the filtered offline data. No partial recipe or unresolved registry entry is admitted as a selected producer. Model, planner, loader and transport checks are automated; this terminal session had no new visual browser pass.

![Viewer interface from an earlier preview](preview.png)

`index.html` is the self-contained viewer; `viewer-data.json.gz` is its complete filtered data; `status.json` records counts and hashes; `README.txt` contains offline instructions. Protected narrative content, raw snapshots, mod binaries, worlds and personal configuration are excluded.

Original pack: [Divine Journey 2 2.23.4](https://github.com/Divine-Journey-2/Divine-Journey-2/releases/tag/2.23.4). Mod names and content belong to their respective authors.
