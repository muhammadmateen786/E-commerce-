# E-commerce-
E-commerce website 
# E-commerce Website

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-commerce Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our E-commerce Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Featured Products</h2>
        <div class="product-list">
            <div class="product">
                <img src="product1.jpg" alt="Product 1">
                <h3>Product 1</h3>
                <p>$19.99</p>
                <button onclick="addToCart('Product 1', 19.99)">Add to Cart</button>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Product 2">
                <h3>Product 2</h3>
                <p>$29.99</p>
                <button onclick="addToCart('Product 2', 29.99)">Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are dedicated to providing the best products at the best prices.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <input type="submit" value="Submit">
        </form>
    </section>

    <footer>
        <p>&copy; 2023 E-commerce Store. All rights reserved.</p>
    </footer>

    <script>
        function addToCart(productName, price) {
            alert(productName + " has been added to your cart at $" + price);
        }
    </script>
</body>
</html>
