# AIM MOD assets

Downloadable content for **AIM MOD** (a Left 4 Dead 2 aim trainer). **Assets only** — the mod itself is not here,
there is no executable, no source code and no DLL in this repository.

The AIM MOD Loader reads `manifest.json`, downloads what it needs, checks each file's SHA-256 and size against the
manifest, and only then uses it. If a check fails the file is deleted and never loaded. Nothing in this repository is
ever run as a program; every file is data (`.vpk` materials, `.png` images, `.jpg` previews, `.wav` audio).

## What's here

| Folder | Contents |
|---|---|
| `skies/` | Animated sky addons, `aimmod_sky_<name>.vpk`. Drop one into `left4dead2\addons\` and it mounts like any addon. Each is a six-face skybox with 24 drift frames: one full 360° turn per minute, looping seamlessly. |
| `sources/` | The original 2:1 panoramas the skies were cut from (2048×1024 PNG), for reference and re-export. |
| `sounds/` | Hit sounds AIM MOD can play (hit / headshot / kill, plus alternates). The loader puts them in `aimmod\sounds\` where the plugin reads them. |
| `CREDITS.md` | Where every sky and every sound came from, and its licence (or lack of one). |
| `manifest.json` | Every file with its size and SHA-256. |

## Skies included

Clear day, blue sky, partly cloudy, overcast, sunset (×3: warm, red, golden), night (×2), toxic green — from
**Poly Haven** and **Screaming Brain Studios**. All **CC0 / public domain**, so they can be redistributed freely; the
credits are there as a courtesy. Details in `CREDITS.md`.

## Licence

The sky images are CC0 (see `CREDITS.md`). The `manifest.json`, `README.md` and `CREDITS.md` text may be reused freely.

**The sounds in `sounds/` are NOT licensed for redistribution.** They are hit sounds taken from other games (CS:GO,
COD, MW2/MW3, Fortnite, Overwatch, Rust, TF2, VALORANT, Natural Selection 2) and from KovaaK's; they are here for the
mod's own use. `CREDITS.md` lists every source. Don't re-host them, and read nothing here as a grant of rights.

AIM MOD itself is not distributed here and its licence is not affected by this repository.

## Not here, on purpose

GTA V content (the effect packs' textures are cut from its `.rpf` archives), the plugin, the loader and all source code
stay private.
