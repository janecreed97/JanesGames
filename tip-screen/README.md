# Tip Screen (joke)

A fake "Add a tip" screen, like the iPad that gets turned around at the counter.
Open `index.html` on an iPad (or use Share → Add to Home Screen to get it full-screen).

- Tapping a button shows a short "Processing…" spinner, then the button's image.
- Tap the image to go back.
- Set the order total in the URL: `index.html?total=23.40`
- The pictures are built into `index.html`, so that one file works by itself (you can AirDrop or email just that file).
  The originals are kept in `images/` for reference. To change a picture, send it to Claude, or put it in `images/` and point the `CONFIG` block at the top of `index.html` at it (but then the `images` folder has to stay next to `index.html`).
