# Modern Libs brand assets

The symbol is a Goldberg polyhedron seen from the front: many cells forming one sphere, with one
copper cell highlighted. It comes in two optical sizes that use the same construction.

| Use | File |
|---|---|
| Large artwork, README headers, icons above 64 px | `large/modern-libs-t19-symbol.svg` (Goldberg G(3,2), T=19, 192 faces) |
| Primary wordmark, light / dark backgrounds | `large/modern-libs-t19-horizontal.svg`, `large/modern-libs-t19-horizontal-dark.svg` |
| Stacked logo | `large/modern-libs-t19-stacked.svg` |
| Single colour | `large/modern-libs-t19-monochrome.svg`, `small/modern-libs-g20-small-monochrome.svg` |
| Icons of 64 px and below | `small/modern-libs-g20-small-symbol.svg` (Goldberg G(2,0), T=4, 42 faces) |
| Icons of 24 px and below | `small/modern-libs-g20-micro.svg` (and `-dark`, `-light`) |
| Compact wordmark | `small/modern-libs-g20-horizontal-compact.svg` (and `-dark`) |
| GitHub organization avatar | `small/github-avatar-small-dark-512.png` |

`GEOMETRY.json` and `GEOMETRY-G20.json` record the face, edge and vertex counts of each construction.

## Colours

| Name | Hex |
|---|---|
| Bottle green | `#0B3D33` |
| Copper | `#B8734F` |
| Deep green | `#062821` |
| Ivory | `#F7F5EF` |

## Typography

The wordmark is set in Inter Display ExtraBold (800), converted to outlines, so the SVG files need no
fonts. Inter is licensed under the SIL Open Font License 1.1; the font files are not included here.

The SVG files are optimized with svgo 3.3.2 (`multipass`, `floatPrecision: 4`, `preset-default` keeping
`viewBox`, `<title>`, `<desc>` and IDs).

## Usage

The Modern Libs name and logos are not covered by any repository license. You may use them to refer to
Modern Libs; do not use them to imply endorsement or for other projects.
