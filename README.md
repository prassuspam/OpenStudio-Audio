# OpenStudio Audio

An open-source, browser-based multitrack audio editor. Import audio, arrange tracks, trim regions, control gain and fades, preview the mix, and export WAV or MP3.

## Features
- Multitrack import using the browser's audio decoder (WAV, MP3, M4A, OGG and other supported formats)
- Waveform previews and session overview
- Track positioning, trim-in / trim-out, gain, fades, speed, mute and solo
- Playback preview and master controls
- WAV export; MP3 export using the open-source LAME encoder (loaded on demand)
- Optional normalization and selectable export sample rate
- Local browser processing: audio files are not uploaded to a server

## Run locally
Open `index.html` in a modern browser, or serve this folder with any static web server.

## GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main**, folder **/(root)**, then save.
4. When deployment completes, visit https://prassuspam.github.io/OpenStudio-Audio/

## Notes
- Supported import formats depend on the browser's built-in audio decoder.
- MP3 export loads LAME.js on demand and needs an internet connection. WAV export does not.
- Rendering long sessions can use substantial device memory.
- This lightweight editor exports the complete session mix rather than separate stems.

## License
MIT. See [LICENSE](LICENSE).
