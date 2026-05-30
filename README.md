<img src="icon.svg" width="80" alt="Redirect Detective icon" />

# Redirect Detective

Ever clicked a YouTube link in a video description and wondered where it actually goes? This tool shows you.

Paste any redirect URL — YouTube, AliExpress affiliate, bit.ly, Facebook share link, whatever — and it traces the full chain down to the real destination.

**[Try it →](https://ngfblog.github.io/redirect-detective)**

---

## What it handles

Resolves these client-side (instant, no API call):

- `youtube.com/redirect?q=...` — the long ugly links from video descriptions
- `youtu.be/` short links
- `google.com/url?q=...` and Google AMP
- `l.facebook.com`, `l.instagram.com`
- `linkedin.com/redir/`, `lnkd.in`
- `s.click.aliexpress.com` affiliate links
- Amazon affiliate links with `?tag=`
- `wa.me`, `t.me`

For everything else (`bit.ly`, `t.co`, `rb.gy`, `tinyurl` and ~20 more shorteners) it calls [unshorten.me](https://unshorten.me) to follow the HTTP redirect, with [unshorten.it](https://unshorten.it) as fallback if the first one fails.

## How to use

Just open the page and paste a URL. That's it.

History of your last 10 lookups is saved locally in the browser. Nothing gets sent anywhere except the unshorten.me API call for short links.

## Run locally

Download `index.html` and open it. No server, no install, no npm.

## Stack

One HTML file. Vanilla JS. Two Google Fonts. That's the whole thing.

## License

MIT

## ❤️ Support

If my projects helped you or saved you time, consider supporting future development:

👉 https://paypal.me/ShopNGF
