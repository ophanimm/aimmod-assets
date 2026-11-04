# Sky image sources

All skies here are CC0 / public domain. Each sky is a 2:1 equirectangular
panorama (2048×1024 PNG): `sources/<name>.png` in this repo holds the source
panorama and `skies/aimmod_sky_<name>.vpk` (a release asset) is the built
six-face animated skybox: 24 frames, each the panorama rolled by 1/24 of its
width, so a full 360° turn loops with no seam.

| Sky | Source | Licence |
|---|---|---|
| sbs_04_clear_day, sbs_11_night_purple, sbs_14_toxic_green, sbs_15_dark_night, sbs_16_blue_sky, sbs_17_sunset, sbs_22_red_sunset, sbs_24_overcast | Screaming Brain Studios, "Cloudy Skyboxes" pack (panoramas), Terragen renders: https://screamingbrainstudios.itch.io/cloudy-skyboxes-pack and https://opengameart.org/content/cloudy-skyboxes-0 | CC0 1.0 (Licence.txt inside the pack) |
| ph_clear_day | Poly Haven "Kloofendal 43d Clear (Pure Sky)": https://polyhaven.com/a/kloofendal_43d_clear_puresky | CC0 (https://polyhaven.com/license) |
| ph_partly_cloudy | Poly Haven "Kloofendal 48d Partly Cloudy (Pure Sky)": https://polyhaven.com/a/kloofendal_48d_partly_cloudy_puresky | CC0 |
| ph_sunset | Poly Haven "Belfast Sunset (Pure Sky)": https://polyhaven.com/a/belfast_sunset_puresky | CC0 |
| ph_overcast | Poly Haven "Kloofendal Overcast (Pure Sky)": https://polyhaven.com/a/kloofendal_overcast_puresky | CC0 |
| ph_night_stars | Poly Haven "Kloppenheim 02 (Pure Sky)" (night, stars, moon, galaxy): https://polyhaven.com/a/kloppenheim_02_puresky | CC0 |
| ph_moonrise | Poly Haven "Qwantani Moonrise (Pure Sky)": https://polyhaven.com/a/qwantani_moonrise_puresky | CC0 |

## What we changed
- **Screaming Brain Studios:** the source panoramas are unmodified. The built VPKs cut them into six cube faces and
  roll them into 24 drift frames.
- **Poly Haven:** downloaded as the 2k HDR original and tonemapped to 8-bit PNG offline (log tonemap, exposure from the
  sky dome, gamma 2.0). The HDR originals are at the URLs above.

Both authors allow redistribution without credit; this file is courtesy and provenance. Original downloads:
`sbs_-_cloudy_skyboxes_-_panorama_0.zip` (OpenGameArt) and the 2k HDRs from dl.polyhaven.org.
