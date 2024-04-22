# E-commerce-project
project
This Java program simulates an online shopping system where users can interact with a variety of products, add them to their cart, and place orders. It includes functionality for managing customers, carts, orders, and different types of products.

Features
Customer Management: Users can input their ID, name, and address to create a customer profile.
Product Selection: Customers can choose from a selection of electronic products, clothing items, and books to add to their cart.
Cart Functionality: Customers can add multiple products to their cart, view the total price, and place orders.
Order Placement: Users have the option to place an order or clear the cart.
Usage
Running the Program: Compile and run the Main.java file.
Customer Information: Input your ID, name, and address when prompted.
Product Selection: Choose the products you want to add to your cart from the options provided.
Cart Management: View the total price of your selected products and decide whether to place an order or clear the cart.
Order Confirmation: If you choose to place an order, you will receive an order summary including the order ID, customer ID, ordered products, and total price.
Classes
Main: Entry point of the program, handles user interaction using JOptionPane and manages product selection, cart, and order placement.
Customer: Represents a customer with attributes such as ID, name, and address.
Cart: Represents a shopping cart with functionalities for adding products, calculating total price, and placing orders.
Product: Abstract class representing a generic product with common attributes like ID, name, and price.
ElectronicProduct: Subclass of Product representing electronic products with additional attributes like brand and warranty period.
ClothingProduct: Subclass of Product representing clothing items with additional attributes like size and fabric.
BookProduct: Subclass of Product representing books with additional attributes like author and publisher.
Order: Represents an order placed by a customer, including information such as order ID, customer ID, ordered products, and total price.
