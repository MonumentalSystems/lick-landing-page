# LICK — Monumental Systems Landing Page

Open `index.html` in a modern browser. All imagery is local in the `assets/` folder. The Monumental pyramid section uses a lightweight Three.js logo model when the CDN is available, with the CSS pyramid fallback still present.

## V3 tune-up

- Removed the bottom JOIN-panel `LICK` text overlay so the artwork can breathe.
- Rebuilt the Power On loop into a more dynamic future-80s rock browser band: distorted guitars, bass, kick/snare/hat drums, lead synth-guitar phrases, tom fills, future sweeps, and doom stabs.
- Tuned performance loops: lower canvas DPR, capped particles/bolts, throttled cursor/model pointer work, lighter storm cadence, a smoother Ignite Pyramid burst, and slower/lighter continuous CSS effects.
- Added visible member-card sparks on hover and stronger sparks on click.
- Improved image framing across member cards, join art, relics, and the prophecy panel.
- Added lazy/async image decoding where appropriate.
- Only the site mute preference is saved in localStorage. The page also works when storage is unavailable.

## Discography and sound controls

- The released-music grid links to Science Rap Battles v1, Solvay Smackdown, Steve Net, Mathematics, and AI and Friends on Suno.
- Agora Smackdown links to the Theseus to Turing video collection. The collection currently identifies Captain Theseus as final and the other videos as draft renders.
- These links open in a new tab and mute the landing page so the background music does not compete with the album or video player. The site's mute control cannot control audio in another tab.
- Mute/Unmute is available in the sticky navigation and in the featured-single dialog. It silences the idle track, reactor, featured audio/video, and generated effects, including after switching tracks or closing the player. Power On/Off still selects the background soundtrack.
- The existing fictional research concept catalog remains below the released music.

The current album integration uses the supplied playlist links, rather than an unverified playlist iframe or undocumented streaming API. To add full on-site album playback, supply MP3s with the album name and track order, plus cover art if available. Keep video files separate from the MP3s; remote video links or final MP4s can be added alongside each track. Large video collections should use media hosting rather than the Git repository. No new album audio or video files are included in this change.

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
