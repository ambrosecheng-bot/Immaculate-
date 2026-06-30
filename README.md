# Immaculate Conception Church — Homepage Redesign (Mockup)

A mobile-first homepage concept for **Immaculate Conception Catholic Church**, Portswood, Southampton — built to be warmer for seekers, easier to navigate, and ready for an online parish shop. Created as a proposal for **Fr. Anthony Chiatu** and the parish council.

> _“Whatever your hand finds to do, do it with all your might.”_ — Ecclesiastes 9:10

🔗 **Live demo:** _add your GitHub Pages URL here_
📄 **Status:** Static visual mockup — not yet connected to a backend.

https://ambrosecheng-bot.github.io/Immaculate-/

---

## What this is

A single self-contained `index.html` (no build step, no dependencies beyond Google Fonts) that reimagines the current parish website around one question every visitor asks first:

> _“How do I come, and how do I join?”_

It is a **design proposal**, not the finished site. Buttons for the shop, donations, and newsletter are illustrative placeholders.

---

## Design goals

| # | Goal | How the mockup addresses it |
|---|------|------------------------------|
| 1 | Seeker / visitor friendly | Hero with **“Plan your first visit”** + **“What to expect”** cards |
| 2 | Free sign-up | Prominent **“Join free · 2 minutes”** card (links to the existing PAMIS registration) |
| 3 | Online shop | Parish **Shop** section, prepared for **Shopify** integration |
| 4 | Reorganised, attractive layout | Card-based sections replace the original single long page |
| 5 | Mobile-first, then desktop | Sticky bottom navigation; capped content width; responsive layout |
| 6 | Improved colour scheme | Retains Marian **blue + gold**, refined with **platinum** jubilee accents and more whitespace |
| 7 | Celebrate the Platinum Jubilee | Top-of-page **“70 years”** banner and a Jubilee shop item |

---

## Tech

- **Plain HTML + CSS** — no framework, no JavaScript build
- **Google Fonts:** Cormorant (display) + Inter (body)
- **Signature motif:** the twelve-star crown (Revelation 12 — a Marian symbol)

Colour tokens (defined as CSS variables in `index.html`):

| Token | Hex | Use |
|-------|-----|-----|
| Marian navy | `#15233f` | Base / headings |
| Sacred gold | `#c8a45c` | Accent / calls to action |
| Platinum | `#c2c7d0` | Jubilee accent |
| Cream | `#faf8f3` | Page background |

---

## View it locally

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
# open index.html in any browser, or serve it:
python3 -m http.server 8000
# then visit http://localhost:8000
```

To preview the mobile layout, open your browser's device toolbar and set the width to ~390px.

---

## Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select branch **`main`** and folder **`/ (root)`**, then **Save**.
5. Your site goes live at `https://<your-username>.github.io/<repo-name>/`.

---

## Repository structure

```
.
├── index.html      # the homepage mockup (everything lives here)
└── README.md       # this file
```

---

## Roadmap

- [ ] Replace placeholder product blocks with **real photography**
- [ ] Connect the **Shopify Buy Button** for books, cards and gifts
- [ ] Wire **donations** (Gift Aid) and the **newsletter** sign-up
- [ ] Add inner pages: Sacraments, Parish Groups, Hall Hire, Contact
- [ ] Build the dedicated **Platinum Jubilee** page (timeline + photo gallery)
- [ ] Accessibility pass (contrast, focus states, alt text) and SEO clean-up

---

## Notes & disclaimers

- This is an **independent design proposal**; it is not an official parish publication.
- Product images and prices are **illustrative samples** only.
- The registration button links to the parish's existing **PAMIS** online form.
- The parish is part of the **Diocese of Portsmouth** (registered charity 1199568).

---

## Credits

Mockup prepared for the parish of Immaculate Conception, Portswood, Southampton.
Built with care, in service of a welcoming community.
