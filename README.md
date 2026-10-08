# Under belt - new site build

This is a **new standalone site** based on the provided Under belt Project Brief and the requested account, checkout, orders, returns, product-detail and journal features.

The previous project is used only as the **source of the 50 main product images and 50 hover/alternate product images**. The previous storefront UI/layout is not reused.

## PDF brief coverage
Home, Shop / Products, Categories, Product Details, Login, Register, About Us, FAQ, Contact Us, Cart, Checkout, User Dashboard, Orders, Wishlist, Return Policy, Terms & Conditions, Privacy Policy, Shipping Policy, Fabric Guide, Journal and a demo Store Admin page are represented.

The brief calls for a modern / minimal / premium / clean direction, neutral colors, large product imagery, subtle animations, a first collection of 50 products, variants, filters, wishlist, discount support, reviews/ratings, cart, quick shopping flow, order tracking, stock, SMS/email-ready structure, responsive mobile behavior and an expandable admin-ready catalog.

## Run
No build step is required. Open `index.html` directly or serve this folder with any static server.

Example:

```bash
python3 -m http.server 5173
```

Then open `http://localhost:5173`.

## Important
Payment is a front-end demo only. Card validation is local and no real transaction is submitted. Final legal text, actual payment gateway, SMS/email provider and production backend credentials should be supplied before production deployment.
