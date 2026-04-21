# Byler & Sons Garage — Internal Dev Notes

> This README is for internal development use only, not for client delivery.

---

## Live Site

**URL:** https://bylerandsonsgarage.netlify.app

**Hosting:** Netlify (free tier)
**Repo:** GitHub — auto-deploys on every push to `main`. No build step, Netlify serves straight from the repo root.

To update the site: make changes, commit, push to `main` and Netlify picks it up automatically within ~30 seconds.

---

## Project Structure

```
bylerandsonsgarage/
├── index.html               # Entire site — single page
├── assets/
│   ├── bylerandsons.png     # Logo (1MB PNG — compress when possible)
│   ├── business_cards/      # Canva exports — black/purple and black/white versions
│   ├── logo-chrome.svg      # Unused logo variants
│   ├── logo-hotrod.svg
│   ├── logo.svg
│   └── pinstripe.svg
├── client-questions.md      # Client meeting notes and open questions
├── DEPLOYMENT.md            # Cloudflare Pages deployment notes (superseded by Netlify)
├── .gitignore
└── README.md
```

---

## Stack

- Plain HTML + Tailwind CSS (CDN, no build process)
- Google Fonts: Pacifico (headings), Bebas Neue (body/labels)
- No frameworks, no dependencies

---

## Still To Do

- [ ] Hero photo (American flag mural on side of garage)
- [ ] Gallery photos (bays, interior, equipment)
- [ ] Add lightbox to gallery once photos are in
- [ ] Confirm if texting is ok or call/email only
- [ ] Ask about ramp — client mentioned it but not ready yet
- [ ] Custom domain if client decides he wants one (~$10-15/yr)
- [ ] QR code printed for shop/business cards

---

## Client Info

- **Client:** Daryl Byler
- **Business:** Byler & Sons Garage
- **Phone:** 717-503-5255
- **Email:** bylerandsonsgarage@yahoo.com
- **Address:** 671 Hill Church Road, Hummelstown PA 17036
- **Hours:** Saturday & Sunday, 1:00 PM - 4:00 PM
- **Rate:** $40/hr, 1 hour minimum
