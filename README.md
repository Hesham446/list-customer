# Happy Birthday, Maloka 🎂

A scroll-driven birthday story — from the first boat trip to today — made by Abada.

Hand-drawn doodle style, neon signs, morphing transitions, particles, stickers, two little games
(you have to win them to keep going), and "Count on Me" playing along.

**Open it:** the GitHub Pages link for this repo, or `index.html` in a browser (needs internet for fonts and GSAP).

## Editing

Everything you'd want to change sits at the top of the script in `index.html`:

- `NAME`, `SIGNATURE`: the names in the finale
- `CHAPTERS`: titles, captions, speech bubbles and photo files for each chapter
- `STICKER_MAP`: which sticker goes on which photo, and in which corner
- `GAME_AFTER` / `SORT_AFTER` / `SORT_PHOTOS`: where the games appear and which photos the sorting game uses
- `MUSIC_START` / `FINALE_AT`: where the song starts, and where it jumps to for the finale

Photos live in `photos/`, the song in `music/`.

Built with [GSAP](https://gsap.com) (ScrollTrigger, ScrollSmoother, SplitText, DrawSVG, MorphSVG, Draggable, Flip).
