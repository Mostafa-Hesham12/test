# Storefront

A lightweight, fully customizable Shopify Online Store 2.0 theme. Free to use, modify, and extend.

## Highlights

- Mobile-first, responsive layout
- Section-based architecture (sections, blocks, JSON templates)
- Product comparison, recently viewed, quick view, and bundles
- Mega menu, lookbook, sticky add-to-cart, and predictive search
- Fully editable from the Shopify theme editor — no code required

## Getting started

This theme uses the standard Shopify theme structure. To develop locally with the Shopify CLI:

```bash
shopify theme dev --store your-store.myshopify.com
```

To deploy:

```bash
shopify theme push
```

## Structure

- `assets/` — JS, CSS, SVG, and static assets
- `config/` — theme settings schema and data
- `layout/` — base layout files
- `locales/` — translations
- `sections/` — section and section-group definitions
- `snippets/` — reusable Liquid partials
- `templates/` — JSON and Liquid templates

## License

Released under the MIT License. See [LICENSE](./LICENSE).
