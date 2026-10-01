# Doodle Codex Valley

A living, zoomable sample world built from the Krita Tile Factory tileset (64px, 6 frames, 10 fps): a 51×34 world of 9 terrains (grass, forest, dirt, roads, water, mountain, swamp, ice, peaks) with four variants each, 25 terrain borders, 12 structures, 22 creatures of 11 kinds, and 38 heroes and NPCs.

The valley moves:
- NPCs walk short errands in all four facings.
- Monsters patrol and roam.
- Nine scripted bouts play out: heroes against monsters, and monsters against each other. Each bout runs through attack, hurt, die and the poof that clears the body.

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
