# Al Majlis Montage app icon

Al Majlis Studio icon, made for the Ministry with Higgsfield (Ideogram Vector), 2026-11-12. Owner approved 2026-11-12.

The Al Majlis Studio family look: an Al Majlis blue rounded tile (`#2a78f9`, corner radius 20 % of
the tile, transparent corners) with a white line glyph: a film strip with a playhead and play button.

## Files

| File | What |
|---|---|
| `filmcraft.svg`, `filmcraft-small.svg`, `hicolor/scalable/apps/ai.storyteller.filmcraft.svg` | the vector (the approved trace, cropped and clipped to the rounded tile) |
| `hicolor/<n>x<n>/apps/ai.storyteller.filmcraft.png` | full-bleed renders, 16-512 px; the 128 px one is the in-app mark and About icon, the 256 px one the window icon |
| `filmcraft-1024.png`, `filmcraft-macos-512.png`, `filmcraft.icns`, `filmcraft.ico` | the same tile at the placement each file had before (Apple grid on macOS, full bleed on Windows) |
| `apps/filmcraft-web/web/favicon.png` (outside this folder) | the web app's tab icon and loading image |

File names and the app id `ai.storyteller.filmcraft` are unchanged (code and packaging depend on them).
Licence: see [LICENSE.txt](LICENSE.txt). `packaging/icons.sh` still renders the derived files from `filmcraft.svg`.
