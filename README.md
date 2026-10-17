# Rudra Trader Poster Website

This repository contains a responsive public landing page for a car frame poster business with:

- Product showcase cards
- A4 poster pricing
- Order form with customer details
- UPI payment display with QR code
- WhatsApp order message flow for merchant follow-up
- Mobile responsive layout

## Files

- `index.html` — full single-page site

## Update before publishing

Before using the site in production, change the following in `index.html`:

- Merchant WhatsApp number:
  - `const merchantPhone = '919999999999';`
- UPI ID if needed:
  - `const upiId = 'shaileshjasoliya9-2@okaxis';`
- Product images or business text as needed.

## GitHub Pages

If you enable GitHub Pages for this repository, the site can be served publicly at:

`https://<your-github-username>.github.io/rudra-trader-posters/`

Example:

`https://rudratrader111.github.io/rudra-trader-posters/`

## Notes

This is a front-end static website. For automatic order confirmation emails or business automation, you can later connect a backend or WhatsApp Business API.
