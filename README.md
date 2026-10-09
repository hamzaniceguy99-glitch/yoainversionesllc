# YOA Inversiones — yoa inversiones llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `yoainversionesllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/yoainversionesllc.mjs`).
> To change the content, edit that file and run `node build.mjs yoainversionesllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@yoainversionesllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Direct / $Long term / $No) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
YOA Inversiones LLC, a Florida limited liability company (document number L24000227990), acquires, renovates and holds residential property for its own account: sourcing and analysing properties before making an offer, carrying out inspections and due diligence, renovating through appropriately licensed contractors, and holding the finished homes as long-term rentals. The company purchases for its own portfolio and works with owners and sellers in Spanish and English. It is not a licensed real estate broker, does not represent buyers or sellers, and accepts no investor funds and offers no securities. Site: yoainversionesllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
