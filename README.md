# Eldokan Storefront

Customer-facing e-commerce store for **Eldokan**, built with Next.js and connected to the Eldokan customer API. It covers the full shopping journey: browse, search, compare, add to cart, check out and track the order.

**Live:** https://eldokan-final.vercel.app

<p align="center">
  <a href="https://eldokan-final.vercel.app"><img src="https://image.thum.io/get/width/1200/crop/750/https://eldokan-final.vercel.app" width="85%" alt="Eldokan storefront home page"/></a>
</p>

## Features

- **Home page** with daily offers, category shelves, brand and seller spotlights, and recently viewed products
- **Search, category, brand and seller pages** with loading skeletons
- **Product page** with image gallery, reviews, share button and product comparison
- **Cart and checkout** with payment methods and installment plans
- **Orders:** history, live status, cancel, edit and return requests
- **Invoices** exported as PDF with a QR code
- **Account:** sign in, register, password recovery, address book and wishlist
- **Shopping assistant** chat panel to help customers find products
- **Arabic and English** with localized prices
- **SEO:** sitemap, robots.txt and product structured data (JSON-LD)

## Tech stack

Next.js (App Router) · TypeScript · Tailwind CSS · shadcn/ui · React Hook Form · Embla Carousel · jsPDF · QRCode

## Project structure

```
app/                          Routes: home, product, category, cart, checkout, orders, account, api
components/                   UI grouped by feature (cart, checkout, home, productDetails, i18n...)
services/                     Data fetching for products, categories, brands, sellers, search
eldokan-customer-api-client/  Typed client for the Eldokan customer API
```

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Author

Built by [Mahmoud Amer](https://www.linkedin.com/in/mahmoud-amer~) · [undefine](https://undefine-lilac.vercel.app)
