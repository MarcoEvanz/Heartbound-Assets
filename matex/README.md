# Mate-Assets

The mod's full `assets/<namespace>` folder, mounted as a git submodule at
`src/main/resources/assets/matex` (branch per mod branch: matex,
Forge_1.20.1, mate_1.21.1, mate_1.20.1 — the mate branches use namespace `mate`).

Artists work on the `matex` branch:
- `textures/` PNG · `geo/` Blockbench geometry · `animations/` Blockbench animations
  (keys `animation.<girlId>.<name>`) · `sounds/` .ogg voice lines
- Adding a NEW sound also needs a `sounds.json` entry (tell the dev).
- Test without building: drop files into a resource pack under `assets/matex/...`, F3+T in game.
- `lang/`, `keyframe_events/`, `blockstates/`, `models/`, `patchouli_books/` are dev-maintained.

Pushing here does NOT change mod builds until the dev bumps the submodule pin.
