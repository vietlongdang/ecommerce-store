# Full Stack E-Commerce + Dashboard & CMS: Next.js 13 App Router, React, Tailwind, Prisma, MySQL, 2023

To view the demo, please visit the following link: https://ecommerce-store-three-zeta.vercel.app/

If you'd like to test the purchase functionality, you can use [Stripe Testing Cards](https://stripe.com/docs/testing)

This is a repository for a Full Stack E-Commerce + Dashboard & CMS: Next.js 13 App Router, React, Tailwind, Prisma, MySQL

## MAKE SURE YOU HAVE [ADMIN](https://github.com/vietlongdang/ecommerce-admin/tree/master) SETUP FIRST!

Key Features:

- Used Shadcn UI for the Admin!
- Our admin dashboard is going to serve as both CMS, Admin and API!
- You are be able to control multiple vendors / stores through this single CMS! (For example you can have a "Shoe store" and a "Laptop store" and a "Suit store", and our CMS will generate API routes for all of those individually!)
- You are be able to create, update and delete categories!
- You are be able to create, update and delete products!
- You are be able to upload multiple images for products, and change them whenever you want!
- You are be able to create, update and delete filters such as "Color" and "Size", and then match them in the "Product" creation form.
- You are be able to create, update and delete "Billboards" which are these big texts on top of the page. You will be able to attach them to a single category, or use them standalone (Our Admin generates API for all of those cases!)
- You are be able to Search through all categories, products, sizes, colors, billboards with included pagination!
- You are be able to control which products are "featured" so they show on the homepage!
- You are be able to see your orders, sales, etc.
- You are be able to see graphs of your revenue etc.
- Used Clerk Authentication!
- Order creation
- Stripe checkout
- Stripe webhooks
- MySQL + Prisma + PlanetScale

### Prerequisites

**Node version 18.x**

### Cloning the repository

```shell
git clone https://github.com/vietlongdang/ecommerce-admin.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_API_URL=
```


### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
