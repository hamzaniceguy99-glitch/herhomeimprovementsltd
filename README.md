# Her Home Improvements — her home improvements ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herhomeimprovementsltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herhomeimprovementsltd.mjs`).
> To change the content, edit that file and run `node build.mjs herhomeimprovementsltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herhomeimprovementsltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Referred) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her Home Improvements Ltd carries out home improvements and building work from Dartford in Kent, trading since 2017. We take on building projects, installation work, finishing and specialist jobs. The thing we put in front of a quote rather than behind it is your cancellation right. When you sign a contract for work in your own home, the law gives you fourteen days to cancel without giving a reason, and the trader has to tell you that in writing. If they do not, your fourteen days becomes twelve months. Home improvement is the sector that rule was written for, and plenty of traders still do not hand over the notice. We do, every time, before any deposit is taken. Notifiable electrical work goes through a registered person, all gas work to a Gas Safe engineer, and pre-2000 buildings get an asbestos survey. Site: herhomeimprovementsltd.shop
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
