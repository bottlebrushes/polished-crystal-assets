# Pokémon Polished Crystal — extracted graphics

Graphics from **Pokémon Polished Crystal** by Rangi42 and the Polished Crystal contributors ([project](https://github.com/Rangi42/polishedcrystal)), a Game Boy Color (Pokémon Crystal engine) fan game, organised as plain image files for reference, study and fan projects.

## Contents

| Folder | What | Count |
|---|---|---|
| `pokemon/` | Pokémon battle sprites | 281 |
| `trainers/` | trainer pictures | 151 |
| `overworld/` | overworld sprite sheets | 21 |
| `tilesets/` | map tilesets | 107 |
| `ui/` | interface graphics | 112 |

Each folder has a contact sheet (`_contact_*.png`) for browsing, and `manifest.json` lists every asset with notes.

## Format

- `pokemon/<name>/` — `front.png` (vertical strip of animation frames, colours applied, transparent background), `front_gray.png` (same in four grey levels), `back.png` / `back_gray.png`, `normal.pal` / `shiny.pal` (two 5-bit RGB lines: light and dark body colour), `anim.asm` (Crystal animation script) where the sprite is animated, and `preview.gif`.
- Other folders hold PNG sheets; tilesets are tile sheets 16 tiles wide.

## What is (and isn't) here

Only art that belongs to this game is included. Sprites, backs, interface pieces and icons that are identical to the official Pokémon Crystal graphics were left out, as were anything that could not be decoded reliably.

Pokémon sprites are stored the way the Polished Crystal source keeps them; overworld sprites are shown in a neutral grey palette.

## Credits

- Pokémon Polished Crystal: Rangi42 and the Polished Crystal contributors.
- Pokémon and all related characters and designs: © Nintendo, Creatures Inc. and GAME FREAK inc.

## Disclaimer

This is an unofficial fan archive. It contains no ROMs and no game code, only extracted images and palettes. All art remains the property of its creators; credit them if you use anything from here. Not affiliated with Nintendo, The Pokémon Company or the original fan-game authors. If you are an author and want something removed, open an issue.
