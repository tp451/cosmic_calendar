# The Cosmic Calendar

An interactive web game that compresses the 13.8-billion-year history of the universe into a single year. Place events from the Big Bang to today on the cosmic calendar and see just how late we arrived.

Inspired by Carl Sagan's *Cosmos*.

🌐 **Live deployment:** <https://cosmic-calendar-mu.vercel.app/>

## How to play

- The Big Bang is given as the orientation.
- You guess the timing of 12 sampled events, in chronological order, from the Big Bang to ChatGPT.
- As the cosmos closes in on the present, the slider and clock zoom into the final hour, the final minute, and finally the final second of the cosmic year.
- Score = how close to the truth you place each event.

## Project layout

- `index.html` — the whole game (single file, no build step)
- `vercel.json` — Vercel hosting config (security headers + cache-control)
- `.vercelignore` — files to keep out of the deployment

## Credits

- Built by [Thorben Pelzer](https://pelzer.blog) via Claude Opus 4.7
- Event images and summaries: Wikipedia / Wikimedia Commons (each image is attributed and licensed in-game)
- Quote: Terence McKenna
- Inspiration: Josie Kins
