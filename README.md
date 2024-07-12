# rn-assignment7-11181591
Project Overview
Building upon the design of assignment 6, this project introduces several enhancements and changes. Instead of static images from the Google Drive assets folder used previously, it now integrates an external API to dynamically populate product images, descriptions, and prices.

An additional feature in this assignment is the inclusion of a product details screen. This screen mirrors the UI mockup and allows users to add products directly from the product details view using the "Add To Basket" button.

A new sidebar has been introduced accessed via a menu button on the top left of either the home screen or product details screen. Selecting "Store" from the sidebar while on the product details screen navigates back to the home screen.

Another navigation enhancement includes using a backward icon, found in the assets folder, as a navigation link to the homepage instead of the logo used previously.

Detailed Features
Home Screen
The Home Screen comprises Header.js, OurStory.js, Products.js, and HomeScreen.js:

Header.js: Contains menu, logo, search, and shopping bag icons.
OurStory.js: Displays the "OUR STORY" text with ListView and Filter icons.
Products.js: Lists all products.
HomeScreen.js: Aggregates all components to form the home screen.
Cart Screen
The Cart Screen includes Header.js, Checkout.js, Footer.js, and CartScreen.js:

Header.js: Features a backward navigation icon, logo, search, page title ("CHECKOUT"), and custom-designed border image.
Checkout.js: Renders items added from the home screen, allows deletion of items, and displays messages when the cart is empty.
Footer.js: Includes a checkout button and shows the total sum of products in the cart.
CartScreen.js: Compiles all components to form the cart screen.
Components
The Components folder houses CartContext.js and Sidebar.js:

CartContext.js: Utilizes React's Context API and useReducer hook to manage the cart screen's state, storing data persistently using AsyncStorage.
Sidebar.js: Defines a sidebar component with animations for showing and hiding, and navigation to the Home screen via the "Store" option.
App Screenshots
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (1).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (2).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (3).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (4).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (5).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (6).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12.jpeg>)