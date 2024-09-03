React Shopping Cart App
This is a simple React shopping cart application that pulls data from a Strapi API. The app displays items in stock along with their cost, allowing users to add and delete items from their shopping cart and see the total cost.


Features
Fetch Products: The app fetches product data from a Strapi API, displaying available items, their country of origin, and their cost.
Add to Cart: Users can add items to their shopping cart.
Delete from Cart: Users can remove items from their shopping cart.
View Total Cost: The total cost of items in the cart is calculated and displayed.
Real-Time Updates: The cart updates dynamically as items are added or removed.
Technologies Used
React: For building the user interface.
React-Bootstrap: For responsive UI components.
Axios: For making HTTP requests to the Strapi API.
Strapi: A headless CMS used for managing and serving product data.

Usage
View Products: The app fetches and displays a list of products from the Strapi API. Each product shows its name, country, cost, and available stock.
Add to Cart: Click the "Add to Cart" button next to a product to add it to your shopping cart.
Remove from Cart: In the cart section, click on an item to remove it from the cart.
Checkout: View the total cost of all items in your cart.
Code Overview
Main Components
Products: The main component that displays the product list and handles interactions like adding to cart and removing items.
Cart: A component that displays items currently in the cart and calculates the total cost.

License
This project is licensed under the MIT License. See the LICENSE file for details.
