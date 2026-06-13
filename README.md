# otmanetahri.github.io

Personal GitHub Pages user site for **Otmane Tahri**.

## Purpose

This repository hosts the `app-ads.txt` file required by **Google AdMob** to verify
publisher identity for mobile apps.

Once the site is live, the file is accessible at:

```
https://otmanetahri.github.io/app-ads.txt
```

## Why app-ads.txt?

`app-ads.txt` (Authorized Digital Sellers for Apps) is an IAB Tech Lab standard that
allows mobile app publishers to declare which ad networks are authorized to sell their
inventory. AdMob requires this file to be reachable at the root of a domain associated
with your developer website.

## Files

| File | Description |
|------|-------------|
| `app-ads.txt` | AdMob publisher authorization file |
| `index.html` | Minimal landing page (required for GitHub Pages) |
| `README.md` | This file |

## Setup

1. Replace `pub-XXXXXXXXXXXXXXXX` in `app-ads.txt` with your real AdMob Publisher ID
   (found in AdMob → Account → Publisher ID).
2. Push this repo to GitHub as `otmanetahri/otmanetahri.github.io`.
3. Enable GitHub Pages in **Settings → Pages → Source: main branch, / (root)**.
4. In AdMob, set your app's developer website to `https://otmanetahri.github.io`.

The file will be live at `https://otmanetahri.github.io/app-ads.txt` within minutes
of enabling Pages.
