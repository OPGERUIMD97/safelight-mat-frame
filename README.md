# Framing

A **Framing** module for [Safelight](https://github.com/anthonyreimche/SafeLight): passe-partout, frames, canvas, crop, shadows, textures and EXIF captions. A top-level tab (like [Print](https://github.com/OPGERUIMD97/safelight-print)).

Export and print use the **on-screen** template only while this module is open. Export from Library or Develop leaves photos unchanged.

For a simple border per photo in Develop, use the separate [Border](https://github.com/OPGERUIMD97/safelight-border) extension.

## Install

In Safelight, go to **View ▸ Extensions** and enter:

```
OPGERUIMD97/safelight-mat-frame
```

Requires the module registry (`registerModule`).

## Usage

1. Open **Framing** (tab, Library toolbar button or **Ctrl+Shift+M**).
2. Select one or more photos and pick a template; page through a selection with ‹ › or ← →.
3. Export or print **from this module**. The Export panel shows the active template, e.g. `Framing: Classic Mat`.

Formats: JPEG, PNG, WebP and TIFF. Filmstrip and Export are docked by default.

## Replaces

[Print Mat](https://github.com/OPGERUIMD97/safelight-print-mat) is discontinued. From Safelight 3.2.6, installing Framing turns it off automatically; use **Import Print Mat** to bring your templates over.

## Changelog

### 3.0.1
- Release zip is now built automatically, so Safelight can install the release directly.

### 3.0.0
- Mats and frames only: the Border mode is gone. Borders per photo are the separate [Border](https://github.com/OPGERUIMD97/safelight-border) extension again, with its own templates.
- Renamed to **Framing**.

### 2.2.0
- No longer turns the Border extension off.

### 2.1.1
- Turns off the discontinued Print Mat and Border extensions automatically (`supersedes`, Safelight 3.2.6+).

### 2.1.0
- Framing / Border modes; Import Border.

## License

MIT
