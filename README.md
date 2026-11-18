# Sleep Screen Maker

Turns any image into a sleep screen for an e-reader. Drag and resize the image
right on a picture of the screen, check the result, and download a file in the
format your device reads.

Use it here: <https://bleubirddy.github.io/tools/sleep-screen-maker/>

## What it does

- **Devices.** Xteink X3 and X4 (CrossPoint firmware), Supernote, Kobo and
  Kindle. Pick yours from the list and the size and file format are set for
  you.
- **Formats.** Xteink gets an 8-bit BMP in the screen's 4 native grays; the
  others get an 8-bit grayscale PNG.
- **Edit, Preview, Compare.** Fit, zoom and place the image, then see it the
  way the e-ink screen will show it, next to the original.
- **Private.** The image is read and converted in your browser and is never
  uploaded.

Each device has its own steps for copying the file over; the page shows them
after you pick the device.

## How it works

The whole tool is one file, `index.html`, with no libraries and no build step.
It loads the Atkinson Hyperlegible fonts from Google Fonts; nothing else comes
from the network.

## Run it yourself

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

The "Bleubirddy tools" link and the tab icon point at `/tools.html` and
`/favicon.svg` on bleubirddy.github.io. Change or remove them if you host it
somewhere else.

## License

No license has been chosen yet.
