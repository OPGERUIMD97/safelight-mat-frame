# Safelight Framing / Border

A **Framing / Border** module for [Safelight](https://github.com/anthonyreimche/SafeLight) (v2.6+). Top-level tab (like [Print](https://github.com/OPGERUIMD97/safelight-print)) with two modes:

- **Framing** — passe-partout, frame, canvas, crop, shadows, textures, EXIF captions  
- **Border** — solid-color border in pixels around the photo (nothing cropped)

Export/print uses the **on-screen** template only while this module is open. Export from Library/Develop leaves photos unchanged.

Requires the [module registry](https://github.com/anthonyreimche/SafeLight/discussions/142) (`registerModule`).

## Replaces

| Old extension | Status |
|---|---|
| [Print Mat](https://github.com/OPGERUIMD97/safelight-print-mat) | Discontinued — deactivate & uninstall |
| [Border](https://github.com/OPGERUIMD97/safelight-border) | Discontinued — deactivate & uninstall |

Use **Import Print Mat** / **Import Border** in this module to migrate templates.

## Features

- Top-level **Framing / Border** tab, Library toolbar button, **Ctrl+Shift+M**
- Modes: **Framing** · **Border**
- Multi-select pages (‹ › / ← →), Filmstrip + Export docked by default
- Export panel shows the active choice, e.g. `Framing: Classic Mat` or `Border: White subtle`
- Formats: **JPEG, PNG, WebP, TIFF**

## Installation

```
OPGERUIMD97/safelight-mat-frame
```

Safelight 2.6.0 or newer is required.

## Usage

1. Open **Framing / Border**
2. Pick **Framing** or **Border**, select a template, tweak settings
3. Export (or print) **from this module**

## License

MIT
