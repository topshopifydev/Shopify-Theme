# 🛍️ Shopify Theme — Custom Storefront (Dawn 13.0.1)

A production‑ready, highly customized **Shopify Online Store 2.0** theme built on top of Shopify's **Dawn 13.0.1** reference theme. It ships with a custom **bundle builder**, **product reviews**, **smart search navigation**, **SMS marketing**, **metaobject landing pages**, and full **multi‑language support** — everything a modern DTC brand needs to launch and scale.

<p align="left">
  <img alt="Shopify" src="https://img.shields.io/badge/Shopify-Online%20Store%202.0-96BF48?logo=shopify&logoColor=white">
  <img alt="Liquid" src="https://img.shields.io/badge/Liquid-Templating-1A1A1A">
  <img alt="Theme" src="https://img.shields.io/badge/Base-Dawn%2013.0.1-000000">
  <img alt="Languages" src="https://img.shields.io/badge/i18n-50%2B%20locales-blue">
  <img alt="PRs" src="https://img.shields.io/badge/PRs-welcome-brightgreen">
</p>

---

## ✨ Highlights

- 🧩 **Custom Bundle Builder** — a `bundle-builder` section + dedicated `page.bundles` template that lets customers assemble multi‑product bundles and add them to cart in one action.
- ⭐ **Product Reviews** — integrated **Opinew** review stars on product cards, product pages, and a dedicated all‑reviews page.
- 🔍 **Smart Search Navigation** — server‑side rendered predictive search & smart navigation snippets for fast, relevant product discovery.
- 📱 **SMS Subscribe** — a standalone `page.sms-subscribe` template for growing an SMS marketing list.
- 🧱 **Metaobject Landing Pages** — a flexible `page.metaobject` template for content‑driven, CMS‑style pages.
- 🌍 **50+ Locales** — full internationalization with translated storefront and schema strings out of the box.
- ♿ **Accessible & Fast** — inherits Dawn's performance‑first, accessibility‑first architecture (lazy loading, minimal JS, semantic markup).

## 🧭 Built on Dawn

This theme extends Shopify's official **Dawn** reference theme, so it stays fully compatible with the **Online Store 2.0** editor: JSON templates, section groups, app blocks, and drag‑and‑drop customization all work as merchants expect.

| | |
|---|---|
| **Base theme** | Dawn 13.0.1 (Shopify) |
| **Templating** | Liquid + JSON templates |
| **Architecture** | Sections, blocks & section groups (OS 2.0) |
| **Integrations** | Opinew Reviews, Smart Search (ISP), SMS marketing |
| **Internationalization** | 50+ locale + schema files |

## 📂 Project Structure

```
├── assets/        # CSS, JS & media (component + section stylesheets, cart, search, product logic)
├── config/        # settings_schema.json & settings_data.json (theme editor settings)
├── layout/        # theme.liquid & password.liquid (page shells)
├── locales/       # 50+ storefront & schema translation files
├── sections/      # Reusable sections incl. custom bundle-builder, header, footer, product
├── snippets/      # Small reusable Liquid partials (icons, price, reviews, search, media)
└── templates/     # JSON & Liquid templates for every page type
    ├── customers/     # Account, login, register, addresses, orders
    ├── page.bundles.json         # Bundle builder page
    ├── page.metaobject.liquid    # Metaobject-driven landing pages
    ├── page.sms-subscribe.liquid # SMS list signup
    └── page.opinew_all_reviews.json  # All product reviews
```

## 🚀 Getting Started

You'll need the [Shopify CLI](https://shopify.dev/docs/themes/tools/cli) and access to a Shopify store.

```bash
# 1. Clone the repository
git clone https://github.com/topshopifydev/Shopify-Theme.git
cd Shopify-Theme

# 2. Log in and connect to your store
shopify theme dev --store your-store.myshopify.com

# 3. Preview locally with hot reload
#    → opens a live preview at http://127.0.0.1:9292

# 4. Push the theme to your store when ready
shopify theme push
```

> 💡 Prefer no tooling? Zip the theme folder and upload it via **Online Store → Themes → Add theme → Upload zip file** in the Shopify admin.

## 🛠️ Customization

- Edit theme‑wide settings in `config/settings_schema.json`, or visually through the **Theme Editor**.
- Add or rearrange content with **sections** and **blocks** — no code required.
- Translate or add languages by editing files in `locales/`.
- Extend functionality by adding new snippets/sections and referencing them in JSON templates.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request. If this project helps you, consider leaving a ⭐ — it helps others discover it.

## 📄 License

This theme is derived from Shopify's Dawn, which is released under the [MIT License](https://github.com/Shopify/dawn/blob/main/LICENSE.md). Custom sections and integrations in this repository are provided under the same terms unless noted otherwise.

---

<p align="center"><sub>Built with 💚 for the Shopify ecosystem · Powered by Dawn & Liquid</sub></p>
