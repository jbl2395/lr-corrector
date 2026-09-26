# LR · CORRECTOR

Stereo phono processor (MODEL LR-1) — a single-page web app that digitises a record's playback through a Focusrite Scarlett 2i2,
corrects cartridge-specific L/R differences (level, frequency response, timing) in real time, and sends it back to a Marantz Model 7.

- App: `record-hosei-v01.html` (single HTML, no external libraries; Google Fonts only)
- UI mock (reference for look & layout, no audio): `record-hosei-mock.html`
- Runs on Mac + Chrome, served over https (GitHub Pages) or `http://localhost` (needed for getUserMedia and the File System Access API)
