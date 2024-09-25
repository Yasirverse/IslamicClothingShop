<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Shop Name</title>
</head>
<body>
    <header>
        <h1>Welcome to Your Shop Name!</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="shop">
            <h2>Shop Our Collection</h2>
            <div class="product-container">
                <div class="product" data-name="Product 1" data-price="25">
                    <h3>Product 1</h3>
                    <p>$25.00</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
                <div class="product" data-name="Product 2" data-price="30">
                    <h3>Product 2</h3>
                    <p>$30.00</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
                <!-- Add more products as needed -->
            </div>
        </section>
    </main>

    <footer>
        <p>© 2024 Your Shop Name. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
