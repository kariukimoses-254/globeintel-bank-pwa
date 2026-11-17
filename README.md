# Globeintel Bank — Installable UI Preview

A single installable web app (PWA) that works on phones, tablets, laptops and desktops. It previews the Globeintel Bank landing site, four banking portals and the QuickBooks accounting workspace.

**Live app:** https://kariukimoses-254.github.io/globeintel-bank-pwa/

> Sandbox demo only. Sample data, no real money movement, no provider connections.

## Install

- **Android / Chrome:** open the live URL, then menu → **Install app** or **Add to Home Screen**.
- **iPhone / Safari:** open the live URL, then Share → **Add to Home Screen**.
- **Windows / macOS / Chromebook:** open the live URL in Chrome or Edge and click the install icon in the address bar.

After the first load, the app shell, photos and icons are cached, so it can be reopened offline.

## Contents

- `index.html` — full app, all portals and embedded background photography
- `manifest.webmanifest` — PWA install metadata
- `sw.js` — offline service worker
- `icons/` — 192px and 512px app icons
- `INSTALL.txt` — detailed install notes

## Local preview

```bash
npx serve .
```

Then open `http://localhost:3000`.

## Security note

This is a UI preview. All credentials, balances, journals, cheques and reports are sample data. It does not connect to a bank, ledger, QuickBooks/Intuit or any payment network.
