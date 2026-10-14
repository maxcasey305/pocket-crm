# Pocket CRM

A pocket CRM for commercial real estate brokers, built to live on an iPhone home screen.

Your contacts, properties and deals are stored only on your phone. Nothing is sent to a server, and nothing about your book of business is ever stored in this repository.

## Install it on your iPhone

1. Open the app's link in **Safari** (other browsers on iPhone can't install apps).
2. Tap **Share**, then **Add to Home Screen**.
3. Open Pocket CRM from your home screen. It runs full screen and works offline.

## What's in it

- **Today**: weighted pipeline GCI, critical dates for the next 30 days (DD expirations, closings, 1031 ID deadlines, calls) and a 24-month lease expiration radar.
- **Deals**: the pipeline tower, with one floor per stage, plus commission math for each deal (fee, your split, GCI, weighted GCI).
- **Properties**: asset class, SF, price, $/SF and cap rate, with owner, tenants and deals.
- **People**: owners, tenants, investors, lenders and more, with lease and 1031 flags.
- **Tools**: sale and lease math, the home-screen badge, and backups.

## Backups

Your data lives only on your phone, so back it up. In **Tools**, tap **Save backup file** and save it to Files or iCloud Drive. **Restore from file** brings it back on a new phone. Deleting the app from your home screen deletes its data.

## Files

- `index.html`: the whole app
- `sw.js`: offline support. Bump `VERSION` when you change any file so phones pick up the update.
- `manifest.webmanifest` and `icons/`: the app's name and home-screen icon
- `fonts/`: Archivo, Instrument Sans and IBM Plex Mono, served locally so the app works offline (SIL Open Font License)
