# Encrypt AES Premium: Website

Landing page and legal pages for **Encrypt AES Premium**, a commercial Android app by Modex for encrypting text with AES.

**Live site:** https://rexhinokovaci.github.io/EncryptAESPremium/lookup/

## What's included

| Page | Purpose |
| --- | --- |
| `lookup/index.html` | Full-screen hero with the app name, a Google Play badge, an Instagram and Twitter/X sidebar, and links to the legal pages |
| `lookup/privacy.html` | Privacy policy for the Encrypt AES Premium app, as required for the Google Play listing |
| `lookup/terms.html` | Terms & conditions |

## Tech stack

Static HTML and CSS with no JavaScript and no build step. It's served by **GitHub Pages**.

## Running locally

```bash
cd lookup
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Project structure

```
lookup/
  index.html     # landing page
  privacy.html   # privacy policy
  terms.html     # terms & conditions
  style.css      # hero layout, sidebar, button styles
  images/        # logo, store badge, social icons, background photos (Unsplash)
```

## License

[MIT](LICENSE)

---

Built by [Rexhino Kovaci](https://github.com/rexhinokovaci) — DevOps & AI engineer in Tirana, Albania. Need an app built? [Get in touch](mailto:kovacirexhino@gmail.com).
