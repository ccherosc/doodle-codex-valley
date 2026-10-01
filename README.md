# Doodle Codex Valley

A living, zoomable sample world built from the Krita Tile Factory tileset (64px, 6 frames, 10 fps): a 51×34 world of 9 terrains (grass, forest, dirt, roads, water, mountain, swamp, ice, peaks) with four variants each, 25 terrain borders, 12 structures, 22 creatures of 11 kinds, and 38 heroes and NPCs.

The valley moves:
- NPCs walk short errands in all four facings.
- Monsters patrol and roam.
- Scripted bouts play out: heroes against monsters, and monsters against each other. Some can go either way.
- Fighters use their gear. Swords and axes strike in melee. Rangers loose arrows, and mages cast firebolts and arcane bolts that fly across the map and spark on impact.
- A slain creature dies and vanishes in a puff of smoke. It leaves treasure behind: gold every time, a gem (ruby, emerald or sapphire) more often than not, and now and then a dropped sword or axe. Walk over treasure to pick it up; your purse is in the hint bar.
- People do not poof. A fallen hero or NPC lies dead where they fell until the morning.

Fallen creatures walk back in after a few seconds. The whole valley resets to its morning every 6 minutes.

## Play

| | |
| --- | --- |
| **W A S D** / arrows | move your hero (the camera follows) |
| **Space** | strike; anything you hit fights back for a while |
| **F** | toggle the follow camera |
| **0** | fit the map |
| **P** | pause |
| **♂ Hero / ♀ Hero** | swap between the two player heroes |

You can also swap heroes from the browser console with `setHero('female')` or `setHero('male')`.

Drag to pan; use the wheel or pinch to zoom. The legend lists every structure, creature and person, and clicking one flies the camera to it.

![preview](preview.png)
