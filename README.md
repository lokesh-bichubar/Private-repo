# Sweet-Bday — Happy Birthday Rachu 🎂

Extracted and split from the single-file `index.html` into a clean folder structure.

## Files
- `index.html` — page markup (was inline `<style>` + `<script>`)
- `style.css`  — all the CSS (was inside `<style>`)
- `script.js`  — all the JavaScript (both inline `<script>` blocks merged, in original order)
- `assets/`    — put your media files here (see list below)

## Assets the page expects (inside `assets/`)
| File | Used for |
|---|---|
| `shinchan-birthday.png` | lock screen "ask" state |
| `shinchan-wrong.png` | wrong passcode state |
| `Chasmish.gif` | gallery |
| `Khubsurat-Racchu.gif` | gallery |
| `Smily-Racchu.gif` | gallery |
| `Us.gif` | gallery |
| `birthday-cat.gif` | decorations |
| `celebration-cake.gif` | cake section |
| `kawaii-cake.gif` | cake section |
| `Happy Birthday Song 🎂.mp3` | audio player |

The images/audio were not part of the uploaded HTML (they live in the site's `assets/` folder), so copy them in to make the page render fully.

## Notes
- The Cloudflare bot-protection script injected at the bottom of the original file was removed (it is added by Cloudflare at serve time, not part of your source).
- Lock-screen passcode stays `2513`.
- Google Fonts are loaded from the CDN in `index.html`; without internet the page falls back to system fonts.
- Just open `index.html` in a browser — no build step needed.
