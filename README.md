# Traffic Safety Website

A responsive single-page website for a **Traffic Safety Monitoring System** —
the public-facing web design companion to the
[traffic-safety](https://github.com/rpoluri9/traffic-safety) full-stack Python project.

## What it shows

- **Traffic rules explained** — speeding, red-light / signal crossing,
  wrong-way driving, mobile phone use while driving, drunk driving,
  and seatbelt safety for passengers
- **Interactive telemetry simulator** — adjust speed, heading, signal state,
  phone use, alcohol level, and seatbelt status; the page evaluates the
  built-in rules engine and shows which violations fire
- **Vehicle registration checker** — enter a registration number and check
  whether its format is correct (green = correct, red = not correct)
- **Pickup-to-drop navigation** section and project architecture overview

## Tech

Pure HTML + CSS + JavaScript in a single self-contained file (`index.html`) —
no build step, no backend. Fully responsive: mobile, tablet, laptop, desktop.

## Run it

Just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Note

This is a static design demo / portfolio piece. The simulator runs entirely in
the browser and saves nothing; vehicle registration checking validates the
number format only.
