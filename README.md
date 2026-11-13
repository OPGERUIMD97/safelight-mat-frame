# Safelight Mat/Frame

A **Mat/Frame module** for [Safelight](https://github.com/anthonyreimche/SafeLight) (v2.6+). Top-level tab (like [Print](https://github.com/OPGERUIMD97/safelight-print)) to design passe-partout and frames, then apply them on **Export** and **Print**.

This is the **v2 architecture** for framing: export-first, no live Develop-canvas overlay (that fought SafeLight zoom/pan in Print Mat v1).

Requires the [module registry](https://github.com/anthonyreimche/SafeLight/discussions/142) (`registerModule`).

## vs Print Mat v1

| | Print Mat (`safelight-print-mat`) | Mat/Frame v2 (this) |
|---|---|---|
| UI | Side panel only | **Module tab** + settings rail |
| Develop overlay | Optional (zoom issues) | **None** |
| Export | Apply + Template in Export panel | Only while Mat/Frame module is open (on-screen template) |
| Print | Via export processors | Via export processors |
| Storage keys | `safelight-print-mat-*` | `safelight-mat-frame-*` (separate) |

If both extensions are installed, disable one export processor to avoid double-framing.

## Features

- Top-level **Mat/Frame** tab, Library toolbar button, **Ctrl+Shift+M**
- Presets, canvas stage, crop, No mat / No frame, matte bevel, frame colors, shadows, textures, EXIF captions
- Named templates + save/reset defaults
- Large module preview — **one framed photo per selected image** (‹ › pages, like Print)
- Default layout docks **Export** (right) and **Filmstrip** (bottom) with Mat/Frame settings
- **Export while Mat/Frame is open** → uses the template on screen (no separate Apply/Template controls)
- **Export from Library/Develop** → no mat/frame (module must be active)
- Formats: **JPEG, PNG, WebP, TIFF**
- Works with Print when you export/print from this module

## Installation

In Safelight → **View → Extensions**, load this folder or:

```
OPGERUIMD97/safelight-mat-frame
```

Safelight 2.6.0 or newer is required.

## Usage

1. Open the **Mat/Frame** tab (toolbar, module strip, or Ctrl+Shift+M)
2. Select one or more photos; tweak the template in **Mat/Frame settings**
3. Export (or print) **from this module** — framing uses what you see on screen

## License

MIT
