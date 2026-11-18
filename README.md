# onlinefoodorder
Online Food Ordering System – Description An Online Food Ordering System is a web-based application 
Online Food Ordering System – Description
An Online Food Ordering System is a web-based application that allows customers to browse restaurants, view food menus, select food items, and place orders online. It provides a convenient way to order food from anywhere without visiting the restaurant physically.

Customers can register and log in, explore different food categories, add items to their shopping cart, place orders, and make payments online or through cash on delivery. The system also allows customers to track their order status.

The administrator can manage food items, categories, customer details, restaurant information, and orders. Restaurant staff can receive orders, update order status, and manage food availability.

Main Features
User Registration and Login: Customers can create accounts and securely log in.

Food Menu: Displays available food items with prices and descriptions.

Search Food: Allows customers to search for their favourite dishes.

Add to Cart: Customers can add or remove food items from their cart.

Place Order: Customers can confirm and submit their orders.

Online Payment: Supports online payment and cash on delivery.

Order Tracking: Customers can check their order status.

Admin Dashboard: Admin can manage users, food items, and orders.

Order History: Customers can view their previous orders.

Objective
The main objective of the Online Food Ordering System is to make food ordering easier, faster, and more convenient for customers while helping restaurants manage their orders efficiently.

<!DOCTYPE html>
<html>
<head>
    <title>Online Food Ordering</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🍔 Online Food Ordering</h1>
    <p>Order your favourite food online!</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#cart">Cart</a>
</nav>

<section id="home">
    <h2>Welcome to Food Order</h2>
    <p>Fresh food delivered to your doorstep.</p>
</section>

<section id="menu">
    <h2>Our Food Menu</h2>

    <div class="food">
        <h3>Pizza</h3>
        <p>Price: ₹150</p>
        <button onclick="addToCart('Pizza',150)">Add to Cart</button>
    </div>

    <div class="food">
        <h3>Burger</h3>
        <p>Price: ₹100</p>
        <button onclick="addToCart('Burger',100)">Add to Cart</button>
    </div>

    <div class="food">
        <h3>Biryani</h3>
        <p>Price: ₹180</p>
        <button onclick="addToCart('Biryani',180)">Add to Cart</button>
    </div>

    <div class="food">
        <h3>Sandwich</h3>
        <p>Price: ₹80</p>
        <button onclick="addToCart('Sandwich',80)">Add to Cart</button>
    </div>
</section>

<section id="cart">
    <h2>Shopping Cart</h2>
    <div id="cartItems"></div>
    <h3>Total: ₹<span id="total">0</span></h3>
    <button onclick="placeOrder()">Place Order</button>
</section>

<script src="script.js"></script>
</body>
</html>
