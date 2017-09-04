---
title: Client Directory Structure
date: 2017-08-20 06:40:12
---

``` bash
+---src
|   |   App.vue
|   |   config.js
|   |   main.js
|   |   
|   +---assets
|   |       .gitkeep
|   |       
|   +---components
|   |   |   
|   |   \---modal
|   |           
|   +---filters
|   |       index.js
|   |       
|   +---i18n
|   |       fr.js
|   |       
|   +---mixins
|   |       basic.js
|   |       
|   +---pages
|   |   |   
|   |   +---account
|   |   |       
|   |   +---admin
|   |   |   |   index.vue
|   |   |   |   
|   |   |   +---address
|   |   |   |       index.vue
|   |   |   |       _id.vue
|   |   |   |       
|   |   |   +---brands
|   |   |   |       index.vue
|   |   |   |       _id.vue
|   |   |   |       
|   |   |   +---categories
|   |   |   |       index.vue
|   |   |   |       
|   |   |   +---coupons
|   |   |   |       index.vue
|   |   |   |       _id.vue
|   |   |   |       
|   |   |   +---features
|   |   |   |       index.vue
|   |   |   |       _id.vue
|   |   |   |       
|   |   |   +---media
|   |   |   |       index.vue
|   |   |   |       
|   |   |   +---orders
|   |   |   |       index.vue
|   |   |   |       manage.vue
|   |   |   |       
|   |   |   +---products
|   |   |   |       index.vue
|   |   |   |       
|   |   |   +---reviews
|   |   |   |       index.vue
|   |   |   |       manage.vue
|   |   |   |       
|   |   |   +---shippings
|   |   |   |       index.vue
|   |   |   |       _id.vue
|   |   |   |       
|   |   |   +---users
|   |   |   |       index.vue
|   |   |   |       _id.vue
|   |   |   |       
|   |   |   \---wishlist
|   |   |           index.vue
|   |   |           
|   |   |       
|   |   \---_slug
|   |           _id.vue
|   |           
|   +---router
|   |       index.js
|   |       
|   \---store
|           
\---static
    |   manifest.json
    |   product-placeholder.png
    +---icons
    \---uploads
        \---thumb
```