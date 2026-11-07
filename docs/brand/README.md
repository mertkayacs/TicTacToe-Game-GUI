# Tic-Tac-Toe brand kit

The Tic-Tac-Toe mark is a tic-tac-toe grid with one X and one O. The logo pairs it with the wordmark `Tic-Tac-Toe` set in Newsreader.

## Files

| Use | File |
|---|---|
| Logo on a light background | `svg/tictactoe-logo-on-light.svg`, `png/tictactoe-logo-on-light-1600.png` |
| Logo on a dark background | `svg/tictactoe-logo-on-dark.svg`, `png/tictactoe-logo-on-dark-1600.png` |
| Mark alone on a light background | `svg/tictactoe-mark.svg`, `png/tictactoe-mark-1024.png` |
| Mark alone on a dark background | `svg/tictactoe-mark-on-dark.svg` |
| App icon (512 px tile, corner radius 112) | `svg/tictactoe-appicon.svg`, `png/tictactoe-appicon-1024.png` |
| Favicon, the app icon tile at small size (reads on light and dark tabs) | `favicon/favicon.svg` |
| The same favicon for older browsers (16, 32 and 48 px in one file) | `favicon/favicon.ico` |
| The same favicon as a 32 px PNG | `favicon/favicon-32.png` |
| Home screen icon (180 px, opaque) | `favicon/apple-touch-icon.png` |

The logo and mark PNGs have transparent backgrounds. The app icon PNG and the favicons have transparent rounded corners. The home screen icon is a full opaque square, because iOS rounds the corners itself.

## Colour

| Role | Light surfaces | Contrast on #FFFFFF / #FDF8F1 | Dark surfaces | Contrast on #0D1117 / #12171D |
|---|---|---|---|---|
| Ink | `#1E2A38` | 14.55 / 13.77 | `#EEE7DB` | 15.40 / 14.66 |
| Accent | `#B5573A` | 4.78 / 4.53 | `#EF977C` | 8.46 / 8.05 |

| App icon | Colour | Contrast on the tile |
|---|---|---|
| Tile | `#1E2A38` | |
| Ink | `#EEE7DB` | 11.84 |
| Accent | `#EF977C` | 6.50 |

README icon colour: `#BD5E41`, 4.34 on #FFFFFF and 4.36 on #0D1117.

## Usage

- Pick the file that matches the background: on-light files for white or paper, on-dark files for dark surfaces. In a README, use a `<picture>` element with the dark logo as the `prefers-color-scheme: dark` source.
- Keep clear space around the logo of at least half the height of the mark.
- Smallest sizes: 16 px for the mark, 120 px wide for the logo.
- The wordmark is drawn as outlined paths, so it looks the same everywhere. Use the supplied files and leave the letters as they are.
- Do not recolour, rotate, stretch, outline or add effects to the mark.

## Font

Newsreader, wght 600, opsz 48. Source: `Newsreader[opsz,wght].ttf` from [google/fonts](https://github.com/google/fonts/tree/86aced91de05cd4f96a06838124cca45be337b2b/ofl/newsreader) at commit `86aced91de05`. Licence: SIL Open Font License 1.1. The letters are converted to paths, so the font is not needed to display the logo.
