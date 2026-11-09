# RoK Personal Tracker (screenshot upload)

Single-file, browser-only site. No backend or account; data is saved in your browser (localStorage).

- Tracker: upload (or paste with Ctrl+V) a profile screenshot; kill points are read by OCR and gains are tracked.
- Showcase: upload gear/armament screenshots; stat lines are read, sorted by section and summed into total stats; export as PNG.
- Accuracy: default OCR is Tesseract.js (free, runs in the browser). Optionally add an Anthropic API key under Reading accuracy for much better reading. The key stays in your browser and calls go straight to Anthropic; use it only on your own device.

Deploy: push `index.html` and `.gitlab-ci.yml` to GitLab; the URL appears under Deploy > Pages.
