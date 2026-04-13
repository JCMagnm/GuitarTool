# GuitarTool

A personal guitar learning tool I built for myself – because I needed exactly this and couldn't find anything that had it all in one place without ads, costs, or unnecessary clutter.

## Features

- **Metronome** – with time signature, subdivisions and tap tempo (PWA recommended on iOS)
- **Chords** – fingering diagrams with finger numbers, filterable by category
- **Scales** – interactive fretboard with pentatonic, blues, minor and major
- **Tunings** – overview of common guitar tunings
- **Circle of fifths** – interactive, shows chords and relative minor per key
- **English/German notation toggle** – for note names (B/Bb vs H/B)

## Who this is for

Probably just me. The UI is in German, built for a beginner, and tailored to my personal needs. But if it's useful to anyone else – feel free.

## Technical

A single HTML file plus a service worker (`sw.js`).
No framework, no build system, no dependencies, no server.
Just open it in a browser – or add it to your home screen on iOS/Android for a full offline-capable PWA experience. After the first load, the app works without an internet connection.
Microphone access (for the tuner) is remembered by the browser after the first permission prompt. On iOS, this may reset after long periods of inactivity.

## Known Issues
- **Tap Tempo double-tap zoom on iOS Safari**: The browser version triggers 
  iOS Safari's double-tap zoom when tapping quickly. This is a Safari bug 
  (`touch-action: manipulation` is ignored in browser context). 
  **Workaround: use the PWA** (Add to Home Screen) – the bug does not occur there.

## Credits

App icon: <a href="https://www.flaticon.com/free-icons/electric-guitar" title="electric guitar icons">Electric guitar icons created by Freepik - Flaticon</a>
