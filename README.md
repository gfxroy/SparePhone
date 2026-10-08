# Spare Phone

Turn an unused phone into a toolbox. 20 browser tools for camera, sound, movement and everyday tasks, with a clean monochrome card interface.

## GitHub Pages

The website files are in `docs/`. To publish for free, make this repository public, then select **Settings → Pages → Deploy from a branch → main → /docs → Save**.

Expected website address after GitHub finishes publishing: https://gfxroy.github.io/SparePhone/

No build command or dependencies are required. Serve `docs/` over HTTPS for camera, microphone and sensor access. The PWA uses relative installation paths, scoped offline caching and local device storage.

## Tools

Motion camera, time-lapse, noise diary, tamper alarm, spirit level, power watch, sensor explorer, QR scanner, document capture, magnifier, voice recorder, compass, GPS trip, flashlight, light comparison, video recorder, color sampler, audio spectrum, vibration meter and metronome.

Start a tool to grant its required permission. Support varies by phone and browser; unsupported sensors show explanations. Monitoring needs the page visible and the screen unlocked. Captures stay in your browser; export anything you want to keep. More tools are shown as locked Coming soon cards.

The bundled jsQR library and its Apache-2.0 license are included in `docs/vendor/`.
