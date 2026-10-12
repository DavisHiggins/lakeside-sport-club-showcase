<p align="center">
  <a href="https://lakesidesportclub.com"><img src="assets/hero.svg" width="100%" alt="Lakeside Sport Club: for sport, leisure, and everything after. Animated cover with the pennant logo and headline on ivory beside a dusk lake scene with a drifting sailboat, a waving club pennant, and the Lakeside crest." /></a>
</p>

<h1 align="center">Lakeside Sport Club</h1>

<p align="center"><strong>A custom athletic-lifestyle storefront built around country-club heritage and lake-house calm.</strong></p>

<p align="center">
  <a href="https://lakesidesportclub.com"><img src="assets/btn-open.svg" height="44" alt="Shop Lakeside" /></a>&nbsp;
  <a href="https://www.higginsd.com/work/lakeside-sport-club"><img src="assets/btn-case.svg" height="44" alt="Case study" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="Davis Higgins" /></a>
</p>

<p align="center"><sub>Live storefront · Client project through Higgins Digital · Designed and built by Davis Higgins</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="880" alt="Screen recording of lakesidesportclub.com: choosing size M for the Heritage Crest Hoodie, adding it to the bag, and opening the bag page." />
</p>

<p align="center"><sub>Real capture of the live storefront. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **A brand you can shop.** Large product imagery, collection pages for each drop, and a serif-and-ivory visual language carry the club's identity through every page, not just the homepage.
- **A complete buying path.** Color and size selection, a slide-out bag, shipment protection, discount codes, and secure checkout, all designed for phones first.
- **Orders that can actually be run.** Every paid order lands in a durable order system with customer status links, transactional email, and an admin area for fulfillment, delays, cancellations, refunds, and exports.

## Why it was built

A new apparel label has to look established before anyone will buy from it. Shoppers decide whether a brand is real in the first few seconds, and a default storefront theme with a logo dropped in says the opposite.

So the brand is built into the shopping experience itself: full-width product visuals, drop-style collections for seasonal releases, and a checkout flow designed for the phone, where this audience buys.

## What I built

Lakeside Sport Club is a client project I designed and built end to end through [Higgins Digital](https://www.higginsd.com):

- Brand direction carried through the whole storefront: typography, palette, logo usage, and photography treatment
- Product, collection, bag, and content pages, plus size guide, policies, FAQ, and a journal
- The commerce platform behind it: catalog, payments, orders, and customer email
- Admin tools for running orders, and the launch checklists the business works from

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    B[Shopping bag] --> S[Lakeside commerce platform]
    S --> C[Secure hosted checkout]
    C --> O[(Order system)]
    O --> E[Customer email]
    O --> A[Admin: fulfill · delay ·<br/>cancel · refund · export]
    O --> L[Customer status link]
```

| Decision | Why |
|---|---|
| **Prices are never trusted from the browser** | What a shopper pays is always decided by the store, so a tampered cart can't change the total. |
| **Card data never touches the site** | Payment happens on a secure hosted checkout, and the store only records the confirmed result. |
| **Every order is handled exactly once** | Payments, emails, and status updates are designed so a slow service or a retry can never drop or duplicate an order. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.png" alt="Lakeside Sport Club homepage: a white clubhouse with a Lakeside flag and the headline 'For sport, leisure, and everything after.'" /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.png" width="300" alt="Heritage Crest Hoodie product page on a phone, priced at $68." /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-shop.png" alt="Lakeside shop grid with category filters and products including a pocket tee, quarter-zip, windbreaker, and hoodies." /></td>
  </tr>
</table>

<sub>Homepage · Shop with category filters · Product page on mobile</sub>

## Technology

| Layer | Technology |
|---|---|
| Storefront | Next.js, React, TypeScript, Tailwind CSS |
| Payments | Stripe |
| Motion | GSAP, Framer Motion, Lenis |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://lakesidesportclub.com"><img src="assets/btn-open.svg" height="44" alt="Shop Lakeside" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. The Lakeside Sport Club name, logos, and product photography belong to Lakeside Sport Club.</sub></p>
