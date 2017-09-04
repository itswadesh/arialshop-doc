---
title: Client Settings
date: 2017-08-24 06:40:12
---

### Path: `src/config.js`

### Language Settings
```bash
export const lang = 'en' // Change to 'fr' for french version.
```
The language file is inside the `src/i18n` directory (fr.js)

### Timeout settings
```bash
export const typingTimeout = 500 // Used for searching. e.g. search.vue
export const loadingTimeout = 200 // Used for showing the loading indicator for each page
```

### Clear Cart Settings
```bash
export const clearCart = false // Whether to clear the cart after order is placed. Useful while testing
```

### Enable / Disable demo mode

<p>Restricts users from saving data if enabled</p>

```bash
export const demo = false
```

### User Roles

```bash
export const userRoles = ['user', 'vendor', 'manager', 'admin'] // This should be in ascending order of authority. e.g. In this case guest will not have access to any other role, where as admin will have the role of guest+user+vendor+manager+admin
```

### Review Settings

```bash
export const reviewSettings = {
    enabled: true, // Enables review for products
    moderate: false // If enabled, the review will be visible to public after admin approval
}
```

### List of order and payment status for Order Management

``` bash
export const orderStatuses = ['Payment Pending', 'Order Placed', 'Order Accepted', 'Order Executed', 'Shipped', 'Delivered', 'Not in Stock', 'Cancellation Requested', 'Cancelled']
export const paymentStatuses = ['Pending', 'Cancelled', 'Paid']
  ```  

### Enabled Payment Methods for ecommerce
``` bash
export const paymentMethods = ['PayPal', 'COD']
```  
### Regional Settings
``` bash
export const country = { name: 'India', code: 'IN' }
export const currency = {
    symbol: '₹',
    code: 'INR', // Shop currency
    paypal: 'USD',// Paypal currency code *** Please choose from https://developer.paypal.com/docs/classic/api/currency_codes/
    exchange_rate: '0.015' // Paypal currency code(USD) / Shop currency (INR) ***  exchange_rate should not be 0 else it will generate divided by 0 error
}
```  

### Menu for Dashboad and Header

``` bash
export const menuItems = [
  { name: 'Products', url: '/admin/products', icon: 'store', authenticate: 'vendor', color: 'black', dashboard: true },
  { name: 'My Orders', url: '/admin/orders', icon: 'watch_later', authenticate: 'user', color: 'grey', dashboard: true },
  { name: 'Manage Orders', url: '/admin/orders/manage', icon: 'history', authenticate: 'vendor', color: 'orange', dashboard: true },
  { name: 'Address', url: '/admin/address', icon: 'location_city', authenticate: 'user', color: 'yellow', dashboard: true },
  { name: 'Manage Reviews', url: '/admin/reviews/manage', icon: 'stars', authenticate: 'manager', color: 'blue', dashboard: true },
  { name: 'My Reviews', url: '/admin/reviews', icon: 'star_rate', authenticate: 'user', color: 'green', dashboard: true },
  { name: 'My Wishlist', url: '/admin/wishlist', icon: 'favorite', authenticate: 'user', color: 'purple', dashboard: true },
  { name: 'Brands', url: '/admin/brands', icon: 'wb_auto', authenticate: 'manager', color: 'purple', dashboard: true },
  { name: 'Categories', url: '/admin/categories', icon: 'view_comfy', authenticate: 'manager', color: 'light-blue', dashboard: true },
  { name: 'Features', url: '/admin/features', icon: 'check_circle', authenticate: 'manager', color: 'brown', dashboard: true },
  { name: 'Coupons', url: '/admin/coupons', icon: 'style', authenticate: 'manager', color: 'pink', dashboard: true },
  { name: 'Shippings', url: '/admin/shippings', icon: 'local_shipping', authenticate: 'manager', color: 'red', dashboard: true },
  { name: 'Users', url: '/admin/users', icon: 'face', img: 'auth.png', authenticate: 'admin', color: 'lime', dashboard: true },
  { name: 'Media Library', url: '/admin/media', authenticate: 'user', icon: 'perm_media' },
  { name: 'Profile', url: '/account/profile', authenticate: 'user', icon: 'face' },
  { name: 'Change Password', url: '/account/change-password', authenticate: 'user', icon: 'lock' },
]
```  