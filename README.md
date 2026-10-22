# Aivora AI Tools — Stage 1 Client Demo

A premium, responsive and interactive storefront prototype based on the **Aivora AI Tools — Website Designer & Developer Brief** (18 October 2026).

## Run locally or in GitHub Codespaces

No npm dependencies are required. In the project's directory:

```bash
python3 -m http.server 8000
```

Open port 8000 in your browser (in Codespaces, use the **Ports** tab and **Open in Browser**). The demo also opens directly via `index.html` in most browsers.

## Included

- Homepage: editorial hero, browse by task, featured tools, 4-step buying explanation, support CTA.
- Shop: searchable product listing, task filters, sorting, responsive cards.
- Product details modal: plan, access method, illustrative price, eligibility disclaimer.
- Functional **demo** cart: quantities, subtotals, persisted to browser localStorage.
- Qatar (QAR), UAE (AED), Saudi Arabia (SAR) currency selector; illustrative FX conversion only.
- Guides, FAQs, support and policy placeholder pages.
- Keyboard access for search (Ctrl/Cmd + K) and Escape to close overlays.

## Important presentation and launch restrictions

**This is a design/interaction prototype, not a functioning e-commerce backend.**

- All product names, prices, plan information, art, and availability states are illustrative. They are NOT verified commercial offers or proof of vendor affiliation.
- Product quick actions open a detail modal, and adding to cart is for demo purposes only. **No checkout, payments, orders, activation or fulfillment occur.**
- Currency amounts are illustrative conversions based on demo multipliers, not current exchange rates, merchant prices or approved country-specific offers.
- The illustrated wordmark is a **temporary visual placeholder**. Replace it with the original, owner-supplied Aivora logo and tagline unchanged before external publication.
- Replace mock product records with the owner's approved offer sheet, genuine vendor assets, official support details, permitted-use rules, delivery commitments and legal policies.
- Connect a verified commerce backend / payment provider only in Stage 2, with server-side price and eligibility validation, webhook idempotency, secure order access, audits and data protection.

## Code layout

- `index.html` — page shell, navigation, overlays, footer
- `styles.css` — responsive design tokens and styling
- `app.js` — product fixtures, routing and front-end interaction logic

## Suggested next steps

1. Client review of the brand direction and mobile/desktop experience.
2. Obtain official Aivora SVG/PNG logo and approved product list.
3. Confirm exact UI content, product categorization and seller contact details.
4. Choose a production commerce architecture (inspect any existing Shopify store first).
5. Rebuild the accepted prototype into a component-based production application with automated tests and backend integration.

## Version 1.1 — Motion upgrade
- Route-to-route fade and subtle lift transitions (hash routing).
- IntersectionObserver-based section reveal with staggered timing.
- Polished card hover, decorative shine, and interactive button feedback.
- Scroll progress indicator and adaptive sticky header shadow.
- Reduced-motion support and mobile hover safeguards.
- No animation libraries or additional dependencies.
