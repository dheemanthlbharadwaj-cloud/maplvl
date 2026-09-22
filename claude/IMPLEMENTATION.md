# Implementation target

Build the map in claude/ around a clean asset registry so the renderer can enforce the whitelist.

Suggested registry:
- environmentSources: Ancient Ruins, Grass Land 2.0
- forbiddenSources: FreeEnvironment, snow
- animations: four entries, each with uses 1
- pathTiles: tile sprites selected from the two environment packs

QA gates:
1. No FreeEnvironment asset references in rendered config or markup.
2. No snow-biome references.
3. Each of the four exact GIF filenames appears once.
4. Path is a repeated actual stone/brick tile sprite, not a tinted/cropped ground image.
5. Level nodes remain visually prominent and readable.
