# Ecommerce Backend

Backend for the ecommerce React app. Express + Sequelize API on port 3000.

Serves products, cart, orders, delivery options and static images. Works with the frontend at [ecommerce-project-on-React](https://github.com/Throughthenev3r/ecommerce-project-on-React).

## Setup

```bash
npm install
npm run dev
```

Server runs at http://localhost:3000

On first start it creates a SQLite database and loads default data.

## Scripts

- `npm run dev` — dev server with nodemon
- `npm start` — production server
- `npm run lint` — eslint

## API

- `GET /api/products`
- `GET /api/cart-items?expand=product`
- `POST /api/cart-items`
- `GET /api/delivery-options`
- `GET /api/orders`
- `POST /api/orders`
- `GET /api/payment-summary`
- `POST /api/reset`

Images are served from `/images`.
