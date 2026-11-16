# Promitei Data — website

Static website for Promitei Data, part of Promitei Ltd.

| Page | File |
|---|---|
| Home | `index.html` |
| Data source partner: Sri Ramakrishna Hospital | `hospital-partner.html` |
| Cybersecurity partner: TechGuard Labs Foundation | `cybersecurity-partner.html` |
| About us: Promitei Ltd. | `about-promitei.html` |
| Business card link page (QR on the printed cards) | `card/index.html` → https://promitei-org.github.io/Promitei-Data/card/ |

Published with GitHub Pages (branch `main`, folder `/`).

The pages carry `<meta name="robots" content="noindex, nofollow">` and `robots.txt` blocks crawlers while partner permissions and open content questions are being confirmed. Remove both to let search engines index the site.

## Business card link page (`card/`)

The QR code on the printed business cards opens `card/`. It has buttons to LinkedIn, promitei.com, Promitei Data, TechGuard Labs and the contact form. To change where a button leads, edit its `href` in `card/index.html`; the printed QR code keeps working because its address does not change. Fonts, the torch images and the logos are local copies from promitei.com in `card/assets/`.
