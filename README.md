# Safelight Mat/Frame (v2 alpha)

A **Mat/Frame module** for [Safelight](https://github.com/anthonyreimche/SafeLight) (v2.6+). Top-level tab (like [Print](https://github.com/OPGERUIMD97/safelight-print)) to design passe-partout and frames, then apply them on **Export** and **Print**.

This is the **v2 architecture** for framing: export-first, no live Develop-canvas overlay (that fought SafeLight zoom/pan in Print Mat v1).

Requires the [module registry](https://github.com/anthonyreimche/SafeLight/discussions/142) (`registerModule`).

## vs Print Mat v1

| | Print Mat (`safelight-print-mat`) | Mat/Frame v2 (this) |
|---|---|---|
| UI | Side panel only | **Module tab** + settings rail |
| Develop overlay | Optional (zoom issues) | **None** |
| Export | Apply + Template | Apply + Template |
| Print | Via export processors | Via export processors |
| Storage keys | `safelight-print-mat-*` | `safelight-mat-frame-*` (separate) |

Keep v1 installed while testing v2. Disable one export processor if both would double-frame.

## Features

- Top-level **Mat/Frame** tab, Library toolbar button, **Ctrl+Shift+M**
- Presets, canvas stage, crop, No mat / No frame, matte bevel, frame colors, shadows, textures, EXIF captions
- Named templates + save/reset defaults
- Large module preview of the selected / active photo
- Export panel: **Apply mat/frame** + **Template**
- Works with Print module via `api.export.renderPhotos` (processors run in the pipeline)

## Installation

In Safelight → **View → Extensions**, load this folder or (once published):

```
OPGERUIMD97/safelight-mat-frame
```

Safelight 2.6.0 or newer is required.

## Usage

1. Open the **Mat/Frame** tab (toolbar, module strip, or Ctrl+Shift+M)
2. Select a photo; tweak templates in **Mat/Frame settings**
3. Export with **Apply mat/frame**, or print via the Print module

## License

MIT
