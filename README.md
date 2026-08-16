# JAPOKO email automation assets

Production files for JAPOKO lifecycle email automations.

## Emails

- `welcome-email-01/` — welcome, brand introduction, `ARIGATO` discount and category discovery.
- `welcome-email-02/` — education: what is different about the Japanese approach to products.
- `welcome-email-03/` — trust, delivery reassurance, reviews, discount reminder and eight product ideas.
- `winback-email-01/`–`03/` — three-email customer reactivation sequence.
- `abandoned-cart-email-01/`–`03/` — three-email abandoned cart sequence.
- `abandoned-checkout-email-01/`–`03/` — three-email abandoned checkout sequence with stronger urgency and the approved E3 offer.
- `product-abandon-email-01/`–`02/` — two gentle reminders about a viewed product.
- `browse-abandon-email-01/` — one low-pressure browsing reminder.

Each directory contains:

- `newsletter.html` — responsive table-based HTML email;
- `newsletter.txt` — plain-text version;
- `BRAND_NOTES.md` — copy, sources and deployment notes;
- `assets/` — local brand, hero, category and product images;
- desktop/mobile previews where available.

Existing downloadable welcome ZIP packages remain available in the repository root.

## Omnisend deployment

The HTML previews use relative local image paths. Before sending, upload the images to Omnisend or another public HTTPS host and replace each local `src` path. Replace `{{ unsubscribe_url }}` and the relevant `{{ CART_URL }}`, `{{ CHECKOUT_URL }}`, or `{{ PRODUCT_URL }}` placeholders with Omnisend-native links and dynamic blocks.

For email 3, configure the advertised 48-hour `ARIGATO` expiry in WooCommerce/Omnisend or remove that expiry line before activation.
