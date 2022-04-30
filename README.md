# Next.js + Shopify

This is a more fleshed out version of my previous Next.js + Shopify site, which you can see [here](https://github.com/andrews1022/nextjs-shopify-static)

- Next.js
- TypeScript
- styled-components
- Shopify

## Project Goals

- Product Page
  - Different color swatches for variants, clicking on one instantly changes image
- Products
  - Different styles for product card if out of stock
- Checkout
  - Be able to add products to cart, and modify / delete products (cart comes in from the right)
  - When you click checkout, go to checkout page
- Have banner / popup noting this is just a site for development, and you should not actually buy anything
- Pages
  - Home page
  - collections pages
  - individual product page
  - privacy and terms page
  - checkout page (simply display message saying _thank you, but this is a test store, and your cart has been cleared_, and have cta to go back home)
- Number of Collections: 6
- Number of Products: 25

## Page Structure

- Global
  - Nav
    - Links to the left
    - Logo centered
    - Search, account, and cart icons on the right
  - Footer
    - Instagram photo's grid (kiv)
    - Footer (layout like boh)
- Home
  - Hero
  - 3 card grid (icon, heading, text)
  - Collections Grid (4 columns across, no gap)
  - Features Products
  - Single Collection Row (different from the 4 in the above row)
  - 50/50 About Us
- Collection Page
  - Filter menu along top
  - Product Cards Grid
- Individual Product Page
  - Image on left, title, description, price, add to card button, etc. on the right
  - Have "related products" / "customers also bought" section beneath
