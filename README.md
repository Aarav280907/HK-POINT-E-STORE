# HK POINT E-STORE

## GitHub Pages notes

This is a static storefront. Product data is loaded from `store-data.json` using a repository-relative path, so it works at the project Pages URL.

The admin panel is a browser-only demo: price, discount, stock, availability, and local orders are stored in `localStorage`. It is not authentication and changes are not shared with other visitors. Use a real backend and server-side authentication before accepting production orders or payments.

