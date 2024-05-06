# CISC3003_2324s2_ProjectAssignmentPart02

## Introduction
- The project is a sample of online shopping website, which is to simulate how an actual online shop works and how to manage the type of website.

## Environment
- In frontend side, this project is mainly developed by vanilla HTML, CSS, and JavaScript.
- In backend side, this project is mainly developed by vanilla PHP, with the PDO extension for securely communicate with MySQL database server. 

## Project Structure
- images/
  - Storing images used by pages.
- css/
  - Storing style sheets named with their purpose.
- js/
  - Storing JavaScript files for general usage.
- component/
  - Storing repeat parts of the pages or the PHP program.
- database/
  - Storing database definition SQL files.
- upload_files/
  - Storing the files uploaded thought the website.

## Function
- ### Add Product
  - Add a new product details to the database thought the website. 
  - The information about the new product are name, price and image uploaded.
- ### View Products
  - All product stored in the database is listed at the website. 
  - Customers can choose the order certain number of specified product. 
  - Customers can add certain number of specified product to their cart. 
- ### Shopping Cart
  - All product in the customers’ cart is listed at the website.
  - Customers can make an order with the specified or all the products in the cart.
  - Customers can clear their cart.
- ### Checkout
  - Customers can make an order with full details at the website.
- ### Order
  - All order customers made is listed at the website.
  - Customers can view the full details of specified order.
  - Customers can cancel their orders.