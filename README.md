# profquantomanca

A classroom timer for interactive whiteboards ("quanto manca?" is Italian for "how much time is left?").

The screen shows, from top to bottom: start time, current time, time remaining (with a progress bar), total duration and end time. Changing any value updates the others. It also has a notes panel you can write on by hand (finger or stylus) or with the keyboard, and a custom message shown when time is up (default: "Consegnare").

The interface is in Italian.

## How it works

- A single static file, `index.html`: no build step, no dependencies, no network requests.
- Runs offline too: copy the file to a USB stick and open it in the whiteboard's browser.
- Settings, notes and the end message are kept in the browser's `localStorage`, so reloading the page does not lose a running timer.
- Designed to work on older Android browsers built into whiteboards.
- Five colour palettes (Aurora, Ocean, Sunset, Forest, Black and white) and an on/off switch for the animated gradient background (palette button, bottom right).
- Languages: Italian, English, French, Spanish, German and the Fano dialect (globe button, bottom right).

## Download

The download button (bottom right) links to the versioned copy in `dist/`, e.g. `dist/profquantomanca_v1.6.html`, which is identical to `index.html`.

## Deployment

Hosted on Vercel as a static site (Framework preset: Other, no build command). Every push to `main` deploys automatically.

## Version

1.6
