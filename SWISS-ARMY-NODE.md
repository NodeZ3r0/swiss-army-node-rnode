# Swiss Army Node — RNode firmware flavor

This repository is a **flavor** of the RNode firmware for the WOPR Systems /
BlackoutLabs **Swiss Army Node** hardware.

## Attribution

Forked from **[liberatedsystems/RNode_Firmware_CE](https://github.com/liberatedsystems/RNode_Firmware_CE)**,
the community edition of Mark Qvist's original
**[markqvist/RNode_Firmware](https://github.com/markqvist/RNode_Firmware)**.

- RNode / Reticulum project: <https://reticulum.network> · <https://unsigned.io>
- **License: GNU GPL v3** (unchanged). All upstream copyright and license
  notices are preserved. Original work © Mark Qvist and the RNode_Firmware_CE
  contributors.

This is an **independent, unofficial** build. It is **not affiliated with, nor
endorsed by**, the upstream RNode or Reticulum projects. "RNode" is the name of
the upstream project; this flavor is distributed under the Swiss Army Node name.

## Changes from upstream

As required by the GPLv3, changes made in this fork are recorded here:

- **`Graphics.h`** — replaced the `bm_boot` 64×27 boot-splash bitmap with branded
  Swiss Army Node artwork (white "WOPR" wordmark on black). No functional or
  protocol changes. The bitmap is generated from the brand assets by
  `swiss-army-node/brand/make_bm_boot.py` (1-bit → Adafruit_GFX `drawBitmap`
  format, 216 bytes).

_Further changes will be appended here as they land._
