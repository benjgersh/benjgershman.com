# benjgershman.com

Personal website for **Benj Gershman** — multi-platinum original bassist of O.A.R., keynote speaker, podcaster, and founder of Healthy Talks LLC.

## Structure

```
.
├── index.html             # Landing page (hero, offerings, talks, connect)
├── faq.html               # Keynote-speaker FAQ page (SEO + FAQPage schema)
├── llms.txt               # AI-crawler summary (ChatGPT, Perplexity, Gemini)
├── images/
│   └── hero-portrait.jpg  # Hero photo (Zoe Rain)
└── README.md
```

Pure static HTML — no build step, no dependencies. Open `index.html` in a browser or deploy any folder-serving host.

## Deployment

The site is hosted on **Netlify**, with DNS managed through **GoDaddy**. To deploy:

- **Netlify (continuous):** connect this GitHub repo to Netlify; pushes to `main` auto-deploy.
- **Netlify (manual):** drag the folder into the Netlify dashboard.
- **Any static host:** upload the files; no server config required.

## Typography

- **Space Grotesk 700** — hero headline (`.hero-name`, `.faq-hero h1`)
- **Syne 800** — brand mark, section titles
- **Inter 300–600** — body, nav, UI

## Palette

| Token      | Hex       | Use                              |
| ---------- | --------- | -------------------------------- |
| `--bg`     | `#EDF7F9` | Page background                  |
| `--primary`| `#164F64` | Headings, dark text, primary CTA |
| `--accent` | `#20BFC8` | Accent color, highlights, hovers |
| `--text`   | `#0F2E3A` | Body text                        |
| `--muted`  | `#5A8090` | Nav links, captions              |

## Contact

- **Email:** whatcouldbebad@gmail.com
- **Site:** https://benjgershman.com
- **Instagram:** [@benjgershman](https://instagram.com/benjgershman) · [@whatcouldbebadofficial](https://instagram.com/whatcouldbebadofficial)
- **LinkedIn:** [benjgershman](https://www.linkedin.com/in/benjgershman)

---

© Healthy Talks LLC. All rights reserved.
