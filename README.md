# Trevor Beuth — tribute page

A single-file, mobile-first memorial page, linked from the QR code on Trevor's plaque.

## Photos

| File | What |
|---|---|
| `images/trevor.jpg` | Web-sized portrait (900px) shown in the oval. |
| `images/mountain.jpg` | Web-sized mountain photo (1400px) behind the header. |
| `images/originals/` | The full-resolution originals (portrait, mountain, invitation, plaque). Not used by the page; kept for reference. |

To swap a photo, replace the web-sized file with the same name. Keep it under ~300 KB so the page loads fast on a phone at the cemetery.

## Preview locally

```bash
python3 -m http.server 8765
```

then open http://localhost:8765 on your phone (same Wi-Fi) or in a browser.

## Publish (free options)

- **Netlify Drop** — drag this folder onto https://app.netlify.com/drop. Instant URL, free custom domain support.
- **GitHub Pages** — push this folder to a repo, enable Pages on the `main` branch.
- **Cloudflare Pages** — same idea, also free.

Once it has a URL, generate the QR code from that URL (e.g. https://www.qrcode-monkey.com) and give the *final* QR to the plaque maker. Use a short, memorable domain if you can — a plaque is permanent, so choose a host you can keep paying for or a free one that won't disappear.
