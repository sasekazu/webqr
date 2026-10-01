# webqr

A simple web page that generates a QR code instantly as you type.

**Live page:** https://sasekazu.github.io/webqr/

## Usage

1. Open the URL above in your browser.
2. Type any text or URL into the input box.
3. The QR code appears below as you type.

- Supports Japanese and other non-ASCII text (encoded as UTF-8).
- Clearing the input box removes the QR code.
- If the text is too long to fit in a QR code, a message is shown instead.

## How it works

- Everything is in a single `index.html` file (HTML + JavaScript).
- QR codes are generated with [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator), loaded from cdnjs.
- An internet connection is required to load the page.
- Your text is processed entirely in the browser and is never sent to a server.

## Running locally

Download `index.html` and open it in your browser.

## Deployment (GitHub Pages)

The page is published with GitHub Pages from the root (`/`) of the `main` branch.
Changes pushed to `main` appear on the live page within a few minutes.
