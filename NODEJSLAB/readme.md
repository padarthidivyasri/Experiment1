# Shopping Cart Website

This project is a small, static shopping website built with HTML, CSS, and JavaScript. It contains a product catalog, a cart page, a login form, and a registration form. The pages share a navigation bar and use local product images.

## Pages and features

- **Catalog (`Index.html`)** — Displays nine products in a responsive grid: washing machine, belt, fridge, pant, shirt, shoes, sofa, TV, and watch. Selecting **Add to cart** currently shows an alert; it does not add an item to persistent cart data.
- **Cart (`Cart.html`)** — Shows a sample cart containing one sofa and one watch, with a displayed total of Rs. 2,00,000. The **Remove** and **Checkout** buttons are visual controls only and are not wired to cart or payment behavior.
- **Login (`Login.html`)** — Provides email and password fields with required-field browser validation. It does not authenticate users or connect to a server.
- **Registration (`Register.html`)** — Collects a username, email, password, password confirmation, mobile number, and optional age. `validation.js` checks these values in the browser and displays alerts; it does not create or store an account.

## Styling

`Utils.css` provides shared page defaults and the header/navigation styling. Each page also has its own stylesheet:

- `Index.css` styles the product catalog grid and product cards.
- `Cart.css` styles the sample cart and includes a small-screen layout adjustment.
- `Login.css` and `Register.css` style the respective forms.

## Project files

```text
Index.html
Index.css
Cart.html
Cart.css
Login.html
Login.css
Register.html
Register.css
Utils.css
validation.js
images/
```

The `images/` folder contains the product images used by the catalog and cart.

## Run locally

Open `Index.html` in a web browser. No package installation or build step is required. The project is front-end only and does not include a backend, user authentication, persistent cart storage, or checkout integration.
