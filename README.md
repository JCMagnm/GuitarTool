# GuitarTool

A personal guitar learning tool I built for myself – because I needed exactly this and couldn't find anything that had it all in one place without ads, costs, or data tracking.

## Features

- **Metronome** – with time signature, subdivisions and tap tempo
- **Guitar tuner** – chromatic tuner using the device microphone; select a tuning to lock to its strings, or use free mode for nearest semitone; displays note, cents deviation and tuning meter
- **Scales** – interactive fretboard with pentatonic, blues, minor and major
- **Chords** – fingering diagrams with finger numbers, filterable by category
- **Circle of fifths** – interactive, shows chords and relative minor per key
- **English/German notation toggle** – for note names (B/Bb vs H/B)

## Who this is for

Probably just me. It is tailored to my personal needs. But if it's useful to anyone else – feel free.

## Technical

A single HTML file plus a service worker (`sw.js`). No framework, no build system, no dependencies, no server. Just open it in a browser – or add it to your home screen on iOS/Android for a full offline-capable PWA experience. After the first load, the app works without an internet connection. Microphone access has to be granted for using the tuner.

## Known Issues

- **Visual Bug**: On the scales tab are some minor visual bugs.

## Credits

- App icon: <a href="https://www.flaticon.com/free-icons/electric-guitar" title="electric guitar icons">Electric guitar icons created by Freepik - Flaticon</a>
- Developed in collaboration with [Claude](https://claude.ai) (Anthropic) as AI coding assistant.
