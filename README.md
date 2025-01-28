# Zahne-01 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Zee Touch - Lifestyle & Clothing</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>The Zee Touch</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="hero">
            <h2>Welcome to The Zee Touch</h2>
            <p>Discover the latest trends in lifestyle and clothing.</p>
            <a href="#shop" class="btn">Shop Now</a>
        </div>
    </section>

    <section id="shop">
        <h2>Our Collection</h2>
        <div class="products">
            <div class="product">
                <img src="product1.jpg" alt="Product 1">
                <h3>Product 1</h3>
                <p>$50.00</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Product 2">
                <h3>Product 2</h3>
                <p>$60.00</p>
                <button>Add to Cart</button>
            </div>
            <!-- Add more products as needed -->
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>At The Zee Touch, we believe in providing high-quality lifestyle products that reflect your unique style. Our clothing line is designed to make you feel confident and comfortable.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 The Zee Touch. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
