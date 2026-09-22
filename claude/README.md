# Cat Quest — Claude build notes

Rebuild requirements:
- Use each of the 4 supplied animated GIFs exactly once. Do not duplicate an animation instance.
- Environment art must come only from the Ancient Ruins and Grass Land 2.0 packs.
- Remove all snow-biome visuals.
- Construct the playable route from actual stone/brick tile assets, not tinted/cropped ground.
- Do not use FreeEnvironment cactus/pine/rock assets.

Natural map design pass:
- Build a single readable route instead of a noisy patchwork. The level should feel like a guided walk, not a random tile collage.
- Use a gentle S-curve or arc for the main road so the player can visually read the direction and the map feels organic.
- Keep the path 2–3 tiles wide and reinforce it with repeated brick/stone tiles; avoid abrupt turns or disconnected segments.
- Place landmarks at natural intervals: starting gate, first ruin cluster, central clearing, shrine/marker, final approach.
- Use asymmetry intentionally: one side can have ruins or grass clusters, the other side open space, so the composition looks handcrafted rather than uniform.
- Keep environmental props in clusters, not single scattered objects. Clumps of foliage, ruins, and rocks should form a believable scene.
- Reserve empty space around the route to prevent the map from feeling crowded or artificial.
- Ensure the four animations sit on logical beats along the route, not floating in isolated pockets.

Source GIFs supplied in the conversation:
1. Animation 3 no bg (1).gif
2. Animation 1 0.5x speed no bg.gif
3. Animation 5 try 2 (1).gif
4. Animation 2 no bg (1).gif

See also: MAP_LEVEL_DESIGN.md for the recommended level composition and pacing.
