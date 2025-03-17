# Ex02 Commercial Website
## Date: 15-03-2025

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
## HTML CODE
# index.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mobile Store</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <div class="container">
        <h1>Mobile Store</h1>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="shop.html">Shop</a></li>
            <li><a href="brands.html">Brands</a></li>
            <li><a href="offers.html">Offers</a></li>
            <li><a href="contact.html">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>
    <section class="hero">
      <div class="hero-text">
        <h2>Latest Smartphones at Best Prices</h2>
        <p>
          Find the perfect mobile phone with unbeatable deals and discounts.
        </p>
        <a href="#" class="btn">Shop Now</a>
      </div>
    </section>
    <section class="products container">
      <div class="product">
        <img src="Redmi.jpg" width="100" height="100" alt="Smartphone 1" />
        <h3>Redmi A3</h3>
        <p>High performance and sleek design.</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
      <div class="product">
        <img src="Samsung.jpg" width="100" height="100" alt="Smartphone 2" />
        <h3>Samsung Galaxy A04S</h3>
        <p>Affordable and feature-packed.</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
      <div class="product">
        <img src="oneplus.jpg" width="100" height="100" alt="Smartphone 3" />
        <h3>OnePlus 12</h3>
        <p>Best battery life and camera quality.</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
      <div class="product">
        <img src="oppo.jpg" width="100" height="100" alt="Smartphone 4" />
        <h3>Oppo Reno 13 Pro</h3>
        <p>Flagship experience at a great price.</p>
        <a href="#" class="btn">Buy Now</a>
      </div>
    </section>
    <footer>
      <p>© 2025 Mobile Store. All Rights Reserved .Deepika S</p>
    </footer>
  </body>
</html>
```
# shop.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Shop - Mobile Store</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <div class="container">
        <h1>Mobile Store</h1>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="shop.html" class="active">Shop</a></li>
            <li><a href="brands.html">Brands</a></li>
            <li><a href="offers.html">Offers</a></li>
            <li><a href="contact.html">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <section class="products container">
      <h2>Shop Smartphones</h2>
      <div class="product">
        <img src="Redmi.jpg" alt="Redmi A3" />
        <h3>Redmi A3</h3>
        <p>Affordable and powerful.</p>
        <a href="buy.html?product=redmi-a3" class="btn">Buy Now</a>
      </div>
      <div class="product">
        <img src="Samsung.jpg" alt="Samsung A04S" />
        <h3>Samsung Galaxy A04S</h3>
        <p>Premium feel at a great price.</p>
        <a href="buy.html?product=samsung-a04s" class="btn">Buy Now</a>
      </div>
    </section>

    <footer>
      <p>© 2025 Mobile Store. All Rights Reserved.Deepika S</p>
    </footer>
  </body>
</html>
```
# brands.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Brands - Mobile Store</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <div class="container">
        <h1>Mobile Brands</h1>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="shop.html">Shop</a></li>
            <li><a href="brands.html">Brands</a></li>
            <li><a href="offers.html">Offers</a></li>
            <li><a href="contact.html">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <section class="brands container">
      <h2>Popular Mobile Brands</h2>
      <div class="brand-gallery">
        <div class="brand">
          <img src="apple.jpg" width="100" height="100" alt="Apple" />
          <h3>Apple</h3>
        </div>
        <div class="brand">
          <img src="Samsung.jpg" width="100" height="100" alt="Samsung" />
          <h3>Samsung</h3>
        </div>
        <div class="brand">
          <img src="oneplus.jpg" width="100" height="100" alt="OnePlus" />
          <h3>OnePlus</h3>
        </div>
        <div class="brand">
          <img src="oppo.jpg" width="100" height="100" alt="Oppo" />
          <h3>Oppo</h3>
        </div>
        <div class="brand">
          <img src="vivo.jpg" width="100" height="100" alt="Vivo" />
          <h3>Vivo</h3>
        </div>
        <div class="brand">
          <img src="Redmi.jpg" width="100" height="100" alt="Redmi" />
          <h3>Xiaomi</h3>
        </div>
      </div>
    </section>

    <footer>
      <p>© 2025 Mobile Store. All Rights Reserved.Deepika S</p>
    </footer>
  </body>
</html>

```
# offers.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Offers - Mobile Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <div class="container">
        <h1>Mobile Store</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="shop.html">Shop</a></li>
                <li><a href="brands.html">Brands</a></li>
                <li><a href="offers.html" class="active">Offers</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </div>
</header>

<section class="offers">
    <h2>🔥 Exclusive Deals & Offers 🔥</h2>
    
    <div class="offer">
        <h3>Flat 10% Off on All Smartphones! 📱</h3>
        <p>Use code: <strong>MOBILE10</strong> at checkout.</p>
    </div>
    
    <div class="offer">
        <h3>Exchange Your Old Phone & Get ₹3000 Extra Discount! 🔄</h3>
        <p>Limited time offer. Hurry up!</p>
    </div>

    <div class="offer">
        <h3>Buy 1 Get 1 Free on Accessories! 🎧</h3>
        <p>Applicable on selected models. Offer valid till stock lasts.</p>
    </div>

    <div class="offer">
        <h3>EMI Starting at ₹999/month! 💳</h3>
        <p>Zero down payment on top brands.</p>
    </div>

    <div class="offer">
        <h3>Free Screen Replacement for 6 Months! 🔧</h3>
        <p>Available for select models purchased before March 31st.</p>
    </div>
</section>

<footer>
    <p>© 2025 Mobile Store. All Rights Reserved. Deepika S</p>
</footer>

</body>
</html>
```
# contact.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Us - Mobile Store</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <div class="container">
        <h1>Mobile Store</h1>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="shop.html">Shop</a></li>
            <li><a href="brands.html">Brands</a></li>
            <li><a href="offers.html">Offers</a></li>
            <li><a href="contact.html" class="active">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <section class="contact container">
      <h2>Contact Us</h2>
      <form action="submit_contact.php" method="POST">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Your Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit" class="btn">Send Message</button>
      </form>
    </section>

    <footer>
      <p>© 2025 Mobile Store. All Rights Reserved.Deepika S</p>
    </footer>
  </body>
</html>

```
# style.css
```
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    background: #f8f8f8;
}

/* Header */
header {
    background: #222;
    color: #d7cbcb;
    padding: 15px 0;
}

.container {
    width: 90%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

h1 {
    font-size: 24px;
}

/* Navigation */
nav ul {
    list-style: none;
    display: flex;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #bc4343;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ff9800;
}

/* Hero Section */
.hero {
    background: url('mobile banner.jpg') no-repeat center center/cover;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #fff;
    padding: 20px;
}

.hero-text h2 {
    font-size: 2.5rem;
    color: #ff5733; /* Updated color for "Latest Smartphones at Best Prices" */
}

.hero .btn {
    display: inline-block;
    background: #ff9800;
    padding: 12px 25px;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    margin-top: 15px;
    border-radius: 5px;
    transition: 0.3s;
}

.hero .btn:hover {
    background: #e68900;
}

/* Products Section */
.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 50px 0;
}

.product {
    background: #fff;
    margin: 15px;
    padding: 20px;
    width: 250px;
    text-align: center;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

.product img {
    width: 100px;
    height: 100px;
}

.product h3 {
    font-size: 1.2rem;
    margin: 10px 0;
}

.product p {
    font-size: 0.9rem;
    color: #666;
}

.product .btn {
    display: inline-block;
    background: #28a745;
    padding: 10px 20px;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    margin-top: 10px;
    border-radius: 5px;
    transition: 0.3s;
}

.product .btn:hover {
    background: #218838;
}

/* Footer */
footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

```
## OUTPUT
![cm1](https://github.com/user-attachments/assets/95c55257-702c-400d-baa6-f7d9c9d92a8e)
![cm2](https://github.com/user-attachments/assets/6d91b2cf-2e1f-4461-a785-727655c3c597)
![cm3](https://github.com/user-attachments/assets/517e3218-1a09-421f-9a63-383bfdff0d3a)
![cm4](https://github.com/user-attachments/assets/73c6f225-2492-4dab-931d-ca199b6ca05a)
![cm5](https://github.com/user-attachments/assets/e1961776-90af-42cd-9cd6-6be845bbd979)
![cmoffer](https://github.com/user-attachments/assets/535d2ab1-554c-4ad4-80ba-9a48da3d0820)
![cm7](https://github.com/user-attachments/assets/48f28f90-d410-412b-b022-1b4974b65412)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
