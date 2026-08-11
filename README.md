# Eagra Labs public website

This directory contains the static company website for
[`eagralabs.com`](https://eagralabs.com). It presents Eagra Labs as the product
studio and links product-specific visitors to the separate Root website.

Root product content, module pages, pricing, contact and the disposable browser
demonstration now live in `../root-website`, intended for
[`root.eagralabs.com`](https://root.eagralabs.com).

Both sites are deliberately independent from the Root application API. The
interactive demonstration stores fictional data in browser `sessionStorage` and
deletes it on sign-out or reset.

Run `node scripts/build-marketing-sites.mjs` from the repository root to rebuild
the static HTML, shared styles, metadata and sitemaps.
