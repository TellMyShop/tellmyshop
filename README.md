# TellMyShop

**Run your PrestaShop or WooCommerce store from Claude or ChatGPT, in plain words.**

TellMyShop is a module for PrestaShop and a plugin for WordPress and WooCommerce. It connects your store to the chat you already use. You write what you need ("fix the meta descriptions in the Shoes category", "why is this product not in Google?"), the chat reads the store, prepares the change and shows you a preview. Nothing is saved until you approve it, and every change can be undone.

[Website](https://tellmyshop.com/?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Get TellMyShop Free](https://tellmyshop.com/free-audit?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Help](https://tellmyshop.com/docs?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Safety](https://tellmyshop.com/security?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Pricing](https://tellmyshop.com/pricing?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) · [Polski](README.pl.md)

## What you can do with it

- **Check the store**: SEO of products, categories and pages, 404 errors, missing translations, why a product or page is not visible in Google.
- **Write and fix content**: product and category descriptions, titles and meta descriptions, CMS pages and blog posts, image alt texts, translations.
- **Work on the catalogue**: products, combinations and variations, categories, features and filters, brands, prices and promotions, stock.
- **Big jobs in one approval**: change hundreds of products by a rule (a category, a brand, no sales for 60 days), find and replace in content, run several steps as one package. Large jobs run in the background and can be undone in one step.
- **Ready-made tasks**: store review, new collection, products without sales, retiring a product, catalogue clean-up and more, started from the panel or the chat.
- **Product feeds** for Google, Meta, Ceneo and CSV that refresh on their own.
- **Theme and modules or plugins**: small fixes after you turn on a switch for 24 hours.
- **Weekly report** by email, with a ready sentence to paste into the chat for each item.

## How changes are kept under control

- Every write shows a preview first and is saved only after your approval.
- Every change can be undone; the history shows who approved it.
- A backup of the database before the first change of the day, plus backups of theme and module files.
- Riskier areas (theme, modules or plugins, service work) stay off until you switch them on for a limited time.
- Passwords, API keys, payments, taxes and order statuses are always blocked.
- Customer data is not available to the AI until you turn access on yourself.
- Hourly limits for actions and changes, which you set in the panel.

## Requirements

| Platform | Versions |
|---|---|
| PrestaShop | 8.1+ and 9.x (PHP 8.1+); separate package for 1.7.8 to 8.2 (PHP 7.2 to 8.0) |
| WordPress | 6.5+ with PHP 7.4+, with or without WooCommerce 8.0+ |
| Chat | a Claude or ChatGPT account, free ones too |

The module runs inside your own store. The chat connects straight to it, with no middle server between your store and the chat.

## Editions

- **TellMyShop Free**: no time limit. Reads the store and gives ready reports (store review, SEO, 404 errors, product visibility, sales without customer data). Saves nothing.
- **TellMyShop Pro**: one-time licence per domain, the same for PrestaShop and WordPress. Adds saving changes after your approval, undo, big jobs, product feeds and the TellMyShop Consultant. 7-day money-back guarantee.

One package for both: without a Pro licence it works as Free. Current prices: [tellmyshop.com/pricing](https://tellmyshop.com/pricing?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne).

## Get started

1. [Get TellMyShop Free](https://tellmyshop.com/free-audit?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne) and install it like any other module or plugin.
2. Copy the shop address for the chat from the TellMyShop panel.
3. Add it in Claude or ChatGPT and click **Allow** in the window of your store. Details: [docs/connect.md](docs/connect.md).

## What is in this repository

Documentation, the changelog and the place to report bugs. The module and plugin are downloaded from [tellmyshop.com](https://tellmyshop.com/?utm_source=github&utm_medium=referral&utm_campaign=linki-zewnetrzne).

- [Changelog](CHANGELOG.md)
- [Report a bug](../../issues/new/choose) (please never paste a licence key, passwords or customer data)
- [Security issues](SECURITY.md)

## For developers

TellMyShop is a Model Context Protocol (MCP) server that lives in the store:

- PrestaShop: `https://<your-store>/module/tellmyshop/mcp`
- WordPress: `https://<your-site>/wp-json/tellmyshop/v1/mcp`

Transport: Streamable HTTP. Sign-in: OAuth 2.1 with PKCE (client ID metadata documents and dynamic client registration). The store owner approves each chat in a window of the store and chooses read and changes, or read only. The exact address is shown in the panel.

---

Not affiliated with PrestaShop SA, WordPress, WooCommerce, Anthropic or OpenAI. PrestaShop, WordPress, WooCommerce, Claude and ChatGPT are trademarks of their owners. Made by SEMownia, Poland.
