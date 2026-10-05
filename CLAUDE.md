# Dino Jungle

A dinosaur exploring game for a 3-year-old, installed as a home-screen app on iPhone/iPad.
Hosted on GitHub Pages from the `main` branch; pushing to `main` publishes it.

## Files
- `index.html` – the whole game (HTML, CSS and JavaScript in one file)
- `sw.js` – offline support
- `manifest.webmanifest`, `icons/` – home-screen app settings and icon

## Rules for every change
1. The player is 3 and can't read: no text-based instructions, big touch targets, no fail states, nothing scary.
2. Keep everything in `index.html`. No external fonts, scripts or images from other sites – the game must work offline.
3. After any change, bump `VERSION` in `sw.js` (v1 → v2 → v3 ...).
4. Test by opening `index.html` in a browser before committing.
5. Commit with a short plain-English message and `git push` to publish.
