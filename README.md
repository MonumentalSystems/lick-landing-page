# LICK — Monumental Systems Landing Page

Open `index.html` in a modern browser. All imagery is local in the `assets/` folder. The Monumental pyramid section uses a lightweight Three.js logo model when the CDN is available, with the CSS pyramid fallback still present.

## V3 tune-up

- Removed the bottom JOIN-panel `LICK` text overlay so the artwork can breathe.
- Rebuilt the Power On loop into a more dynamic future-80s rock browser band: distorted guitars, bass, kick/snare/hat drums, lead synth-guitar phrases, tom fills, future sweeps, and doom stabs.
- Tuned performance loops: lower canvas DPR, capped particles/bolts, throttled cursor/model pointer work, lighter storm cadence, a smoother Ignite Pyramid burst, and slower/lighter continuous CSS effects.
- Added visible member-card sparks on hover and stronger sparks on click.
- Improved image framing across member cards, join art, relics, and the prophecy panel.
- Added lazy/async image decoding where appropriate.
- No browser storage APIs are used by this static landing page.

## Interactive features

- Mouse-reactive neon plasma field and lightning cursor sparks
- Click-to-cast lightning bolts anywhere on the page
- Member-card hover and click sparks so the voltage visibly answers back
- “Ignite Pyramid” plasma jet blast with screen flash and success reactor meter
- Browser-native WebAudio band loop with guitars, bass, drums, synth lead, fills, and doom stabs
- Theme mutation: magma, acid, and blood chrome palettes
- 3D tilt poster and member cards
- Storm mode, prophecy generator, and keyboard shortcuts
- Front-end-only email demo; no data is sent or stored

## Keyboard shortcuts

- `L` launches the plasma jet
- `S` toggles storm mode
- `M` mutates the theme
- `P` spins a new prophecy
