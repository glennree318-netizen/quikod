# ⚡ Quikod — Free QR Code Generator

QR codes for links, text, WiFi, vCards, SMS, email and phone.
**Static, client-side. No signup. No account. Scans never tracked. Codes never expire.**
Free forever.

## ✨ Features

- Templates: URL/text, WiFi, vCard, SMS, email, phone
- Live preview as you type (debounced)
- Custom colors (with scannability guardrail), sizes up to 4096px
- Error-correction levels, adjustable quiet zone
- Logo embed in the safe center zone
- PNG / SVG download, copy to clipboard
- Dark/light mode, installable PWA, works offline

## 🔒 Privacy

QR encoding runs 100% in your browser (vendored public-domain
`qrcodegen` engine - no CDN, no server). Static codes: scans never
phone home, codes work even if this site disappears.

Stated plainly rather than as a slogan: the page loads a small cookieless
analytics script (Umami) on the production hostname only, to count visits.
It sets no cookies, builds no profile, and never sees your QR content,
because the code is generated on your machine. Load the page once and use
it offline and nothing is sent at all.

## 🚀 Run it

Open `index.html` in a browser — or host anywhere static
(Vercel, Netlify, GitHub Pages, Cloudflare Pages).

## 📄 License

MIT (QR engine: public domain, Nayuki — see attribution in `index.html`)
