# Third-party notices

The game code and content of Redning are © 2026 Stop60, all rights reserved (see `LICENSE`).
The game is a single self-contained `index.html` (plus `/pl/` and `/en/` entry pages). The public build additionally
loads the self-hosted, cookie-free GoatCounter script `count.js`; the opt-in online leaderboard talks to Supabase.

Original content: all artwork (ship, grabbers, mutants, humans, planet, radar, intro) is drawn as vector shapes on an
HTML canvas by the game's own code; icons are inline SVG / own PNG; all sounds are synthesised live with the Web Audio
API (no samples). No assets from other games are used.

Embedded components (inlined as base64 / minified source inside `index.html`):

| Component | Use | Licence | Copyright |
|---|---|---|---|
| IBM Plex Sans (Latin + Latin Extended) | body text | SIL Open Font License 1.1 | © IBM Corp. |
| Oswald (Latin + Latin Extended, weights 500/600) | headings, digits, buttons | SIL Open Font License 1.1 | © The Oswald Project Authors |
| qrcode-generator (minified, unmodified, copyright header kept) | in-page QR code for "Share the game" | MIT | © 2009 Kazuhiko Arase |
| GoatCounter count.js (public build only) | cookie-free visit statistics | ISC | © Martin Tournoij |

Full licence texts: `OFL-IBMPlexSans.txt`, `OFL-Oswald.txt`, `LICENSE-qrcode-generator.txt` (also linked from the in-game "Licences" page).

## QR code

The QR code is generated in the browser (no external QR service, no tracking) and encodes only the game's own address.
QR Code is a registered trademark of DENSO WAVE INCORPORATED.
