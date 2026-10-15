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

- The released-music grid has on-site Suno song embeds for Science Rap Battles v1, Solvay Smackdown, Steve Net, Mathematics, AI and Friends, and What I Do. Their 92 songs and playlist order are in `assets/suno-albums.js`. Listen here opens one shared player with album selection, a track list, and Previous/Next controls. Select a song, then press play inside Suno's player; Suno tracks do not automatically advance.
- Agora Smackdown links to the Theseus to Turing video collection. The collection currently identifies Captain Theseus as final and the other videos as draft renders.
- Agora Smackdown also plays directly on the site from 12 MP3s in `assets/agora/`, in the video collection's running order. Choose any song, use native audio controls, or move with Previous/Next. Tracks advance automatically; Stop album or the end of the last track returns to the background soundtrack. Pausing a song keeps the background paused.
- The Suno player loads only after choosing an album or song. Switching songs replaces its iframe. The background, Agora, and featured-single players pause while Suno is selected, and starting Agora or a featured single removes the Suno player so the audio cannot overlap. Stop Suno player returns to the background soundtrack.
- Mute removes the Suno iframe to stop its audio, because cross-origin embeds cannot be controlled through the page's native media controls. Unmute and load song reloads the selected track from the beginning. A saved mute preference is respected when choosing an album.
- Secondary Suno playlist links and the video collection link open in a new tab and mute the landing page. The site's mute control cannot control audio in another tab.
- Mute/Unmute is available in the sticky navigation and in the featured-single dialog. It silences the idle track, reactor, album player, featured audio/video, and generated effects, including after switching tracks or closing the player. Power On/Off still selects the background soundtrack.
- The existing fictional research concept catalog remains below the released music.

Suno playback uses its supplied `https://suno.com/embed/<song-id>` iframe format. No third-party download service or undocumented streaming API is used. Playback depends on Suno remaining available and permitting the song to be embedded; secondary playlist links provide a fallback. Keep video files separate from MP3s; large video collections should use media hosting rather than the Git repository.

The Agora MP3s were copied without changing their audio bytes from `/home/ubuntu/Dev/tellus` on wife-ai-ubuntu. The running order and display titles follow the supplied Theseus to Turing video collection; filenames are normalized for web hosting. Original audio files remain unchanged. The seven album covers are original artwork created for this site.

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
