# Ex02 Commercial Website
## Date: 03-09-25

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>ShopEase | Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h2 class="logo">ShopEase</h2>
    <nav>
        <a class="active" href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="cart.html">Cart</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="hero">
    <img src="https://img-cdn.inc.com/image/upload/f_webp,c_fit,w_1920,q_auto/images/panoramic/getty_522735456_249841.jpg" class="hero-img">
    <div class="hero">
    <div class="hero-text">
        <h1>Discover Style. Discover Comfort.</h1>
        <p>Your one-stop destination for fashion, electronics, and everyday essentials.</p>
    </div>
</div>

</section>
</body>
</html>
```
## products.html
```
<!DOCTYPE html>
<html>
<head>
    <title>ShopEase | Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h2 class="logo">ShopEase</h2>
    <nav>
        <a href="index.html">Home</a>
        <a class="active" href="products.html">Products</a>
        <a href="cart.html">Cart</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="products-page">
    <h1>All Products</h1>

    <div class="product-grid">

        <div class="product-card">
            <img src="https://img.freepik.com/free-vector/smart-watch-realistic-image-black_1284-11873.jpg?semt=ais_incoming&w=740&q=80">
            <h3>Smart Watch</h3>
            <p>$120</p>
        </div>

        <div class="product-card">
            <img src="data:image/jpeg;base64,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">
            <h3>Headphones</h3>
            <p>$80</p>
        </div>

        <div class="product-card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQt5ZVp8JzSKSC9GGmx0VS6bmQzUi-kGiWaBA&s">
            <h3>Backpack</h3>
            <p>$45</p>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1668069226492-508742b03147?fm=jpg&q=60&w=3000&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8bWVuJTIwc2hvZXN8ZW58MHx8MHx8fDA%3D">
            <h3>Shoes</h3>
            <p>$60</p>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1577803645773-f96470509666?fm=jpg&q=60&w=3000&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8c3VuZ2xhc3Nlc3xlbnwwfHwwfHx8MA%3D%3D">
            <h3>Sunglasses</h3>
            <p>$30</p>
        </div>

        <div class="product-card">
            <img src="https://4.imimg.com/data4/RU/VC/MY-11853389/men-s-jackets.jpg">
            <h3>Jacket</h3>
            <p>$110</p>
        </div>

    </div>
</section>

</body>
</html>
```
## cart.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>ShopEase | Cart</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h2 class="logo">ShopEase</h2>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="about.html">About</a>
        <a class="active" href="cart.html">Cart</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="cart-section">

    <h1>Your Shopping Cart</h1>

    <!-- Item 1 -->
    <div class="cart-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTCiSKk-dWud9TcxLOi3rO0V8B-4ICkJqDuTg&s" alt="Product 1">
        <div class="item-details">
            <h3>Premium Leather Handbag</h3>
            <p class="price">$79.99</p>

            <label>Quantity:</label>
            <input type="number" value="1" min="1">
        </div>
    </div>

    <!-- Item 2 -->
    <div class="cart-item">
        <img src="https://shop.geekria.com/cdn/shop/files/5f9245eb-b6bb-5b48-8f71-7092d3366a8a_580x.jpg?v=1706093033" alt="Product 2">
        <div class="item-details">
            <h3>Wireless Noise-Canceling Headphones</h3>
            <p class="price">$129.99</p>

            <label>Quantity:</label>
            <input type="number" value="1" min="1">
        </div>
    </div>

    <!-- Summary -->
    <div class="cart-summary">
        <h2>Order Summary</h2>
        <p>Subtotal: <strong>$209.98</strong></p>
        <p>Shipping: <strong>$10.00</strong></p>
        <hr>
        <p class="total">Total: <strong>$219.98</strong></p>

        <a href="#" class="checkout-btn">Proceed to Checkout</a>
    </div>

</section>

</body>
</html>
```
## contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>ShopEase | Contact</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h2 class="logo">ShopEase</h2>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        
        <a href="cart.html">Cart</a>
        <a class="active" href="contact.html">Contact</a>
    </nav>
</header>

<section class="contact-section">
    <h1>Contact Us</h1>

    

    <form class="contact-form">
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <textarea placeholder="Your Message"></textarea>
        <button>Send Message</button>
    </form>
</section>

</body>
</html>
```
## styles.css
```
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background: #f8f8f8;
}

/* Header */
header {
    background: #222;
    color: white;
    display: flex;
    justify-content: space-between;
    padding: 15px 40px;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav a {
    color: white;
    margin-left: 20px;
    text-decoration: none;
}

nav a.active {
    border-bottom: 2px solid yellow;
}

/* Hero Section */
.hero {
    width: 100%;
    height: 90vh;
    background-image: url("assets/hero.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    padding-left: 50px;
    margin: 0;
    box-sizing: border-box;
}

.hero-img {
    width: 100%;
    height: 330px;
    object-fit: cover;
}

.hero-text {
    background: rgba(0, 0, 0, 0.6);
    padding: 30px 40px;
    border-radius: 10px;
    color: white;
    max-width: 400px;
}

/* Products Grid */
.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.product-card {
    background: white;
    width: 260px;
    padding: 10px;
    text-align: center;
    border-radius: 10px;
}

.product-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

/* Featured */
.featured, .products-page, .page-section, .cart-section {
    text-align: center;
    padding: 40px;
}

/* Contact Page */


.contact-form {
    display: flex;
    flex-direction: column;
    width: 300px;
    margin: auto;
    gap: 10px;
}

.contact-form input, textarea {
    padding: 10px;
    border-radius: 8px;
    border: 1px solid #ccc;
}

button {
    padding: 10px;
    border: none;
    background: #222;
    color: white;
    border-radius: 8px;
    cursor: pointer;
}



.cart-section {
    padding: 80px 40px;
    max-width: 900px;
    margin: auto;
}

.cart-section h1 {
    font-size: 36px;
    color: #222;
    margin-bottom: 30px;
}

/* Each Cart Item */
.cart-item {
    display: flex;
    background: white;
    padding: 20px;
    border-radius: 15px;
    margin-bottom: 25px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    align-items: center;
}

.cart-item img {
    width: 150px;
    height: 150px;
    border-radius: 12px;
    object-fit: cover;
    margin-right: 20px;
}

.item-details {
    text-align: left;
}

.item-details h3 {
    font-size: 22px;
    margin: 0;
    color: #333;
}

.price {
    color: #e63946;
    font-size: 20px;
    margin: 10px 0;
}

/* Quantity Input */
.item-details input {
    width: 60px;
    padding: 8px;
    border-radius: 5px;
    border: 1px solid #aaa;
    font-size: 16px;
}

/* Order Summary Box */
.cart-summary {
    background: #ffffff;
    padding: 30px;
    border-radius: 15px;
    margin-top: 40px;
    text-align: left;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.cart-summary h2 {
    margin-top: 0;
    font-size: 28px;
}

.cart-summary p {
    font-size: 18px;
    margin: 10px 0;
}

.cart-summary .total {
    font-size: 24px;
    font-weight: bold;
    color: #222;
}

/* Checkout Button */
.checkout-btn {
    display: block;
    background: #ff6600;
    color: white;
    text-align: center;
    padding: 14px;
    border-radius: 10px;
    text-decoration: none;
    margin-top: 20px;
    font-size: 18px;
    font-weight: bold;
}

.checkout-btn:hover {
    background: #e65c00;
}
/* Contact Section Centering */
.contact-section {
    height: 70;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}
```


## OUTPUT

<img width="1905" height="918" alt="image" src="https://github.com/user-attachments/assets/6d533b69-dab9-4df2-bc2b-67a9af483908" />
<img width="1906" height="914" alt="image" src="https://github.com/user-attachments/assets/f2294950-74a0-4b2e-95aa-f54dec0b7423" />
<img width="1919" height="900" alt="image" src="https://github.com/user-attachments/assets/f83efb7f-c2fe-47c2-ba30-34751cb197ce" />
<img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/a49e5a16-a14b-4dd9-998f-cf2b049be723" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
