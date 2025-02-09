<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khowaja Luxury Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4285F4;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            padding: 14px 20px;
            text-align: center;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            background-color: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 0 auto;
            display: block;
        }
        .profile-info {
            text-align: center;
        }
        .profile-info h1 {
            margin: 10px 0;
        }
        .profile-info p {
            color: gray;
        }
        .luxury-products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }
        .product {
            width: 30%;
            background-color: #f4f4f4;
            padding: 10px;
            text-align: center;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #4285F4;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #3367d6;
        }
    </style>
</head>
<body>
    <body style="background-color:aqua;">
    

<header>
    <h1>Khowaja Luxury Store</h1>
</header>

<!-- Navigation Bar -->
<nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Luxury Products</a>
    <a href="#contact">Contact Us</a>
</nav>

<!-- Home Section -->
<section id="home" class="container">
    <div class="profile-info">
        <img src="your-profile-pic.jpg" alt="Profile Picture" class="profile-pic">
        <h1>Khowaja Luxury Store</h1>
        <p>Welcome to Khowaja Luxury Store, your go-to destination for premium and exclusive luxury products.</p>
        <p>Email: <a href="mailto:khowajalyxurystore554@gmail.com">khowajalyxurystore554@gmail.com</a></p>
        <p>Location: Your City, Country</p>
    </div>
</section>

<!-- About Us Section -->
<section id="about" class="container">
    <h2>About Us</h2>
    <p>Khowaja Luxury Store offers a wide range of premium and exquisite luxury products that cater to the most sophisticated tastes. Our carefully curated collection includes everything from fine jewelry, watches, to exclusive home decor, ensuring that every product we offer is a symbol of elegance and class.</p>
</section>

<!-- Luxury Products Section -->
<section id="products" class="container">
    <h2>Our Luxury Products</h2>
    <div class="luxury-products">
        <div class="product">
            <img src="luxury-product-1.jpg" alt="Luxury Product 1">
            <h3>Premium Watch</h3>
            <p>Price: $2500</p>
            <p>Luxury watch with fine craftsmanship.</p>
        </div>
        <div class="product">
            <img src="luxury-product-2.jpg" alt="Luxury Product 2">
            <h3>Smart watch</h3>
            <p>Price: $1500</p>
            <p>Exclusive collection of designer jewelry.</p>
        </div>
        <div class="product">
            <img src="luxury-product-3.jpg" alt="Luxury Product 3">
            <h3>T shirts </h3>
            <p>Price: $399</p>
            <p>Elegant luxury T shirts for your living room.</p>
        </div>
    </div>
</section>

<!-- Contact Us Section -->
<section id="contact" class="container">
    <h2>Contact Us</h2>
    <form action="mailto:khowajalyxurystore554@gmail.com" method="post" enctype="text/plain" class="contact-form">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Your Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Send Message</button>
    </form>
</section>
<form action="/submit-address" method="POST">
    <h1>Shiping address</h1>
  <label for="name">Full Name:</label>
  <input type="text" id="name" name="name" required><br><br>

  <label for="street">Street Address:</label>
  <input type="text" id="street" name="street" required><br><br>
<label for="address line 2">address line 2</label>
<input type="text" id="address line 2"
name="address line 2" required><br>
<br>
  <label for="city">City:</label>
  <input type="text" id="city" name="city" required><br><br>



  <label for="country">Country:</label>
  <input type="text" id="country" name="country" required><br><br>

  <label for="phone">Phone Number:</label>
  <input type="text" id="phone" name="phone"><br><br>

  <input type="submit" value="Submit">
</form>
<meta name="google-site-verification" content="7zoHBQaUBbwFZ_Kx0v160xSo444Si0ys_8LcRwP-WoM" />

</body>
</html>
