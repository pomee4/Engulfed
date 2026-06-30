# Engulfed

A 2D *Vampire Survivors*–like game built with **Godot 4.7** and **GDScript**.

Survive escalating waves of enemies, level up, and stack synergistic upgrades
until the screen is engulfed.

## Status

Early development. This repository is the Godot project root.

## Requirements

- [Godot Engine 4.7](https://godotengine.org/) (GDScript, no C# required)

## Getting started

```bash
git clone <your-repo-url>
cd engulfed
```

Then open the project in Godot:

1. Launch Godot 4.7.
2. Click **Import**, select the `project.godot` file in this folder.
3. Press **F5** (or the Play button) to run.

> Note: `project.godot` is created automatically the first time you open the
> folder in the Godot editor.

## Project structure

```
engulfed/
├── scenes/        # .tscn scenes (main, menus, levels, UI)
├── entities/      # player, enemies, projectiles, pickups (scene + script pairs)
├── components/    # reusable node components (health, hurtbox, movement, etc.)
├── data/          # Resource definitions and game data (weapons, upgrades, waves)
├── globals/       # autoload singletons (game state, audio, events, save)
├── art/           # sprites, textures, tilesets
├── audio/         # music and sound effects
├── fonts/         # font resources
├── addons/        # third-party and custom editor plugins
└── .github/
    └── workflows/ # CI (lint, export builds)
```

Sibling folders outside the Godot project (not part of this repo):

- `../design/` — design docs, GDD, balance notes
- `../reference/` — reference material and inspiration
- `../art-sources/` — source art files (`.aseprite`, `.psd`, `.kra`)

## Contributing

Contributions are welcome. Please open an issue to discuss substantial changes
before submitting a pull request.

## License

Released under the [MIT License](LICENSE).
