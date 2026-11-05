# 🎯 Dart Counter

Mobile dart scoreboard in a single `index.html` – no build step, no tracking, works offline.
Design: "Pub Oche Arcade" (brass on dark green), made in Google Stitch.

- 301 / 501 / 701, Double-Out or Straight-Out
- 1–4 players, legs to win (1 / 2 / 3 / 5), throw order with swap
- Per-dart input (Single / Double / Triple, 25, Bull, Miss)
- Bust detection, checkout suggestions, 3-dart average, best visit, 180s
- Winner screen with match stats (highest checkout, averages, total darts)
- Responsive: phones (portrait + landscape), tablets and desktop; the keypad fills the screen height so no scrolling mid-game
- Installable PWA (Add to Home Screen), works offline, keeps the screen awake during a match
- Match history: finished matches are saved on the device (last 50) with stats and a visit-by-visit log
- Undo (also after the winning dart); match state is stored in the browser

Fonts are self-hosted (no Google Fonts request, GDPR-friendly): Anton and Inter, both SIL OFL – see `fonts/`.

Open `index.html` or host it with GitHub Pages (Settings → Pages → main / root).
