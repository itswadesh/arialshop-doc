---
title: Client Directory Structure
date: 2017-08-20 06:40:12
---

# ArialShop - Vue2.0 + Node + Mongo

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
|   |   |   AddressList.vue
|   |   |   Alert.vue
|   |   |   Breadcrumb.vue
|   |   |   Busy.vue
|   |   |   Cart.vue
|   |   |   CartButtons.vue
|   |   |   Coupon.vue
|   |   |   CreditCard.vue
|   |   |   Edit.vue
|   |   |   Footer.vue
|   |   |   ImageInput.vue
|   |   |   List.vue
|   |   |   ListImage.vue
|   |   |   Loading.vue
|   |   |   Logo.vue
|   |   |   Megamenu.vue
|   |   |   OauthButtons.vue
|   |   |   OrderContent.vue
|   |   |   ProductCard.vue
|   |   |   ProductFeatures.vue
|   |   |   ProductKeyFeatures.vue
|   |   |   ProductList.vue
|   |   |   ProductVariants.vue
|   |   |   README.md
|   |   |   Reviews.vue
|   |   |   Search.vue
|   |   |   ShopHeader.vue
|   |   |   Submit.vue
|   |   |   Toast.vue
|   |   |   WishButton.vue
|   |   |   
|   |   \---modal
|   |           CancelOrder.vue
|   |           Confirm.vue
|   |           ImageModal.vue
|   |           LoginModal.vue
|   |           Review.vue
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
|   |   |   checkout.vue
|   |   |   index.vue
|   |   |   NotFound.vue
|   |   |   README.md
|   |   |   success.vue
|   |   |   
|   |   +---account
|   |   |       change-password.vue
|   |   |       forgot.vue
|   |   |       index.vue
|   |   |       login.vue
|   |   |       profile.vue
|   |   |       reset.vue
|   |   |       signup.vue
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
|   |   +---auth
|   |   |       forgot.vue
|   |   |       signup.vue
|   |   |       
|   |   \---_slug
|   |           _id.vue
|   |           
|   +---router
|   |       index.js
|   |       
|   \---store
|           cart.js
|           crud.js
|           index.js
|           user.js
|           
\---static
    |   manifest.json
    |   product-placeholder.png
    +---icons
    \---uploads
        \---thumb
```
<br/>
  <br/>