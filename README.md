# dinners.delli.com

A small iOS-style links page for DELLI dinners. Replaces the previous Calendly redirect on `dinners.delli.com`.

## Local

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 4173
```

## Hosting

Static files on Vercel. Point the existing `dinners.delli.com` domain at this project so the Calendly 307 is replaced by this page.
