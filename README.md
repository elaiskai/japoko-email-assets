# JAPOKO welcome email series

Production files for the three-email JAPOKO welcome automation.

## Emails

- `welcome-email-01/` — welcome, brand introduction, `ARIGATO` discount and category discovery.
- `welcome-email-02/` — education: what is different about the Japanese approach to products.
- `welcome-email-03/` — trust, delivery reassurance, reviews, discount reminder and eight product ideas.

Each directory contains:

- `newsletter.html` — responsive table-based HTML email;
- `newsletter.txt` — plain-text version;
- `BRAND_NOTES.md` — copy, sources and deployment notes;
- `assets/` — local brand, hero, category and product images;
- desktop/mobile previews where available.

Downloadable ZIP packages are available in the repository root.

## Omnisend deployment

The HTML previews use relative local image paths. Before sending, upload the images to Omnisend or another public HTTPS host and replace each local `src` path. Replace `{{ unsubscribe_url }}` with the correct Omnisend unsubscribe tag.

For email 3, configure the advertised 48-hour `ARIGATO` expiry in WooCommerce/Omnisend or remove that expiry line before activation.
