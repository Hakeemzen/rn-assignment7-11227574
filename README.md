# rn-assignment7-11227574
Project Overview
Building upon assignment 6, this project introduces several enhancements. Instead of static images from Google Drive, it now integrates an external API to dynamically fetch product images, descriptions, and prices.

A new feature is the addition of a detailed product screen, faithfully recreated from the UI mockup. Users can now add products directly from this screen using the "Add To Basket" button.

Additionally, a sidebar has been added, accessible via a menu button on the top left of both the home and product screens. Clicking "Store" in the sidebar from the product details screen navigates back to the home screen.

Navigation has also been refined with the use of a backward icon, replacing the logo as a link back to the homepage.

Detailed Features
Home Screen
The Home Screen includes Header.js, OurStory.js, Products.js, and HomeScreen.js:

Header.js: Includes menu, logo, search, and shopping bag icons.
OurStory.js: Displays "OUR STORY" with ListView and Filter icons.
Products.js: Lists all available products.
HomeScreen.js: Aggregates all components to form the home screen layout.
Cart Screen
The Cart Screen consists of Header.js, Checkout.js, Footer.js, and CartScreen.js:

Header.js: Features a backward navigation icon, logo, search, page title ("CHECKOUT"), and a custom-designed border image.
Checkout.js: Displays items added from the home screen, allows item deletion, and provides feedback when the cart is empty.
Footer.js: Includes a checkout button and shows the total cost of items in the cart.
CartScreen.js: Compiles all components to create the cart screen interface.
Components
The Components folder houses CartContext.js and Sidebar.js:

CartContext.js: Utilizes React's Context API and useReducer hook to manage cart state, ensuring persistent data storage with AsyncStorage.
Sidebar.js: Defines a sidebar component with animations for visibility toggling and navigation to the home screen through the "Store" option.
App Screenshots
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (1).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (2).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (3).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 21.58.12 (4).jpeg>)
![](<Assignment7/WhatsApp Image 2024-07-12 at 22.55.47.jpeg>)