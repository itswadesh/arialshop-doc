---
title: Server Directory Structure
date: 2017-08-19 06:40:12
---

# ArialShop - Vue2.0 + Node + Mongo

``` bash
+---server
|   |   app.ts
|   |   config.ts
|   |   routes.ts
|   |   seed.ts
|   |   tsconfig.json
|   |   
|   +---api
|   |   |   base.ts
|   |   +---address
|   |   +---brand
|   |   +---category
|   |   +---contact
|   |   +---coupon
|   |   +---customer
|   |   +---feature
|   |   +---media
|   |   +---order
|   |   +---orderHistory
|   |   +---pay
|   |   +---payment-method
|   |   +---product
|   |   +---review
|   |   +---sendmail
|   |   +---shipping
|   |   +---upload
|   |   +---user
|   |   \---wishlist
|   |           
|   +---auth
|   |   |   auth.service.ts
|   |   |   index.ts
|   |   |   
|   |   +---facebook
|   |   |       index.ts
|   |   |       passport.ts
|   |   |       
|   |   +---google
|   |   |       index.ts
|   |   |       passport.ts
|   |   |       
|   |   +---local
|   |   |       index.ts
|   |   |       passport.ts
|   |   |       
|   |   \---twitter
|   |           index.ts
|   |           passport.ts
|   |           
|               
```