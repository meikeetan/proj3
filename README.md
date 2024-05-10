# Ecommerce Site 🕺
Welcome to "ecommerce site" – your go-to for shopping enthusiasts and money-spenders who like to keep it real (and stylish)! 👗 
Get ready to dive into a world of trendy threads with "ecommerce site." We're not your average online store – because we're here to wipe out your wallet (in the most fashionable way, of course).
<br/>
Why "ecommerce site"? Well, we figured, why not make shopping online as easy as scrolling up and down? And "site"? It's just simple and straightforward like our website.
<br/>
Now, you might be thinking, "Why choose 'ecommerce site'?" Honestly, we asked ourselves the same question after a few too many late-night shopping sprees.
So, if you're up for some guilt-free shopping and a few laughs along the way, hop on board the "ecommerce site" train. Let's make fashion fun again! 💸🚀

## Code Explanation 💬
The code consist of the following elements:

### 1. Ecommerce Site
*pages*
- `Cart.js` & `Checkout.js` & `Payment.js` & `OrderStatus.js` : handle a series of actions from user clicking on item of interest then proceed to add to cart, followed by checkout then payment. `OrderStatus.js` should display the shipping status of item.
- `Favourite.js` & `Home.js`: to display home as well as clothes of interest
- `Login.js` & `Signup` & `Profile`: for authentication and editing of user password 

*components*
- `FavouriteList.js`: fetches the clothes of interest and displays it
- `Header.js`: essentially the navbar
- `ProductDetail.js` & `ProductList.js` : fetches the products and list it in its respective categories 

### 2. Order
*components*
- `OrderStatus.js`: fetches order from backend, and onClick it registers orders being shipped

### 3. Backend
- Contains the models for `AdminUsers` `Cart` `Favourite` `Order` `Product` `User`
- Contains controllers and routes: controllers to handle business logic, routes for the frontend to access these logics. 
  
## Start Shopping!! 🛍️
CLICK ME >> *https://webstore-rosy.vercel.app/*

## Future Enhancements 💡
- add a slider so that we don't display all the product listings in one page (e.g. one page only display 9 items)
- add filter function (e.g. so that users are able to filter items according to price, colour, size)
- add a search bar function
