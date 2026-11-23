# Safelight Framing / Border

A **Framing / Border** module for [Safelight](https://github.com/anthonyreimche/SafeLight) (v2.6+). Top-level tab (like [Print](https://github.com/OPGERUIMD97/safelight-print)) with two modes:

- **Framing** — passe-partout, frame, canvas, crop, shadows, textures, EXIF captions  
- **Border** — solid-color border in pixels around the photo (nothing cropped)

**Border or Framing / Border?** For a simple border per photo in Develop, use the separate [Border](https://github.com/OPGERUIMD97/safelight-border) extension. Once it is active, this module's Border mode steps aside and the module is for mats, frames and print.

Export/print uses the **on-screen** template only while this module is open. Export from Library/Develop leaves photos unchanged.

Requires the [module registry](https://github.com/anthonyreimche/SafeLight/discussions/142) (`registerModule`).

## Replaces

| Old extension | Status |
|---|---|
| [Print Mat](https://github.com/OPGERUIMD97/safelight-print-mat) | Discontinued — deactivate & uninstall |

From Safelight 3.2.6, installing or updating Framing / Border turns Print Mat off automatically (the top bar says so). Use **Import Print Mat** in this module to migrate templates.

## Works with Border

[Border](https://github.com/OPGERUIMD97/safelight-border) 2.x is a separate extension again: a border per photo in Develop, visible everywhere. While it is active, the **Border** mode here is hidden and the module shows a note instead. Turn Border off and the mode, with your Border templates, is back.

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

## Changelog

### 2.2.0
- Border is a separate extension again: no longer turned off by this module (`supersedes` now lists only Print Mat).
- Border mode hides itself while the Border extension is active.

### 2.1.1
- Turns off the discontinued Print Mat and Border extensions automatically (`supersedes`, Safelight 3.2.6+), so you no longer end up with two sets of border settings.

### 2.1.0
- Framing / Border modes; Border mode (solid px) replaces the Border extension; Import Border.

## License

MIT
