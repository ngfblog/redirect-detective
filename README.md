# 🔍 Redirect Detective

> Reveal the true destination behind YouTube redirects, AliExpress affiliate links, short links, and more.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg)
![Client side](https://img.shields.io/badge/runs-in%20browser-purple.svg)

## ✨ Features

- **Instant client-side parsing** — no server needed for YouTube, Google, Facebook, Instagram, LinkedIn, AliExpress, Amazon, WhatsApp, Telegram
- **HTTP redirect resolution** — short links like `bit.ly`, `t.co`, `rb.gy` resolved via [unshorten.me](https://unshorten.me)
- **Full redirect chain** — see every hop from source to final destination
- **Trust indicator** — flags suspicious or unusually long chains
- **History** — last 10 lookups saved locally in your browser
- **Dark mode** — always
- **Zero dependencies** — one plain HTML file, no build step, no npm

## 🌐 Supported Platforms

| Platform | Type |
|---|---|
| YouTube `youtube.com/redirect` | Client-side |
| YouTube `youtu.be` short links | Client-side |
| Google `google.com/url?q=` | Client-side |
| Google AMP | Client-side |
| Facebook `l.facebook.com` | Client-side |
| Instagram `l.instagram.com` | Client-side |
| LinkedIn `lnkd.in` / `linkedin.com/redir` | Client-side |
| AliExpress `s.click.aliexpress.com` | Client-side |
| Amazon affiliate links | Client-side |
| WhatsApp `wa.me` | Client-side |
| Telegram `t.me` | Client-side |
| `bit.ly`, `tinyurl`, `t.co`, `rb.gy` + 20 more | Via API |

## 🚀 Usage

Just open `index.html` in any browser — no installation required.

Or visit the live version: **[ngfblog.github.io/redirect-detective](https://ngfblog.github.io/redirect-detective)**

Paste any URL and press **Analyze** (or hit Enter).

## 🛠 Deploy Your Own

### Netlify (30 seconds)
1. Go to [netlify.com](https://netlify.com)
2. Drag `index.html` onto the deploy area
3. Done — you get a free `*.netlify.app` URL

### GitHub Pages
1. Fork or clone this repo
2. Go to **Settings → Pages → Branch: main → Save**
3. Your site is live at `https://username.github.io/redirect-detective`

## 🔒 Privacy

Everything runs in your browser. No data is sent anywhere except:
- Short link resolution uses the public [unshorten.me](https://unshorten.me) API
- History is stored only in your browser's `localStorage`

## 📄 License

MIT — do whatever you want with it.
