# Snapdeal

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SnapDeal</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <head>

       
        <style>
  body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
}

.navbar {
    background-color: #d32f2f;
  padding: 10px 20px;
    display: flex;
    justify-content: right;
}

.nav-item {
    color: white;
    text-decoration: none;
    font-weight: bold;
    padding: 10px;
}


header {
    background-color: #ff5c00;
    color: white;
      padding: 10px 20px;
    display: flex;
      justify-content: space-between;
    align-items: center;
}


header  button {
    padding: 10px 20px;
       background-color: #fff;
    border: none;
       color: #ff5c00;
    border-radius: 5px;
    cursor: pointer;
    
}

header .search-bar input {
    padding: 10px;
   width: 60%;
    height: 80%;
 border: none;
    border-radius: 5px;
}

main {
    padding: 20px;
}

main h2 {
    text-align: center;
    margin-bottom: 20px;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
     gap: 20px;
    margin-top: 20px;
}

.product-card {
    background-color: white;
    padding: 10px;
       border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        text-align: center;
}

.product-card img {
    width: 100%;
    height: auto;
      border-radius: 5px;
}

.product-card h3 {
    margin: 10px 0;
    font-size: 18px;
}

.product-card .price {
       color: #ff5c00;
    font-weight: bold;
    margin: 10px 0;
}

.product-card button {
    padding: 10px;
      background-color: #ff5c00;
      color: white;
    border: none;
      border-radius: 5px;
    cursor: pointer;
}

.product-card button:hover {
    background-color: #e04e00;
}

.product-grid{
    width: 100%;
}

footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

footer .footer-links {
    margin-top: 10px;
}

footer .footer-links a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

footer .footer-links a:hover {
    text-decoration: underline;
}


        </style>
        
    </head>
</head>
<body>
    <div class="navbar">
        <a href="#" class="nav-item">Our Blog</a>
        <a href="#" class="nav-item">Help Center</a>
           <a href="#" class="nav-item">Sell on Snapdeal</a>
        <a href="#" class="nav-item">Download App</a>
    </div>

    <header>
        <div class="logo">
            <img src="" alt="Snapdeal Logo">
        </div>
        <div class="search-bar">
                <input type="text" placeholder="Searchfor products">
            <button type="button">Search</button>
        </div>
        <div class="user-options">
            <button>Sign In</button>
            <button>Cart</button>
        </div>
    </header>

   
    <main>
        <h2>Featured Products</h2>
        <div class="product-grid">
           
            <div class="product-card">
                <img src=https://marketplace.canva.com/EAFy-Kja1dg/1/0/1600w/canva-white-and-black-simple-modern-earbuds-amazon-product-image-kBO8rvpqdlw.jpg alt="Product Image">
                <h3>Product 1</h3>
                <p class="price">₹999</p>
                <button>Buy Now</button>
            </div>
            
            <div class="product-card">
                <img src=https://marketplace.canva.com/EAFeRip4ZdU/2/0/1600w/canva-blue-white-modern-electronic-product-listing-amazon-product-image-L9oGFxjq7T0.jpg alt="Product Image">
                <h3>Product 2</h3>
                <p class="price">₹1499</p>
                <button>Buy Now</button>
            </div>
            
            <div class="product-card">
                <img src=https://vasanthandco.in/images/productimages/1903__product__Mobiles__apple-mobile-iphone-13-blue-128gb-1.png alt="Product Image">
                <h3>Product 3</h3>
                <p class="price">₹89,799</p>
                <button>Buy Now</button>
            </div>
            
            <div class="product-card">
                <img src=https://marketplace.canva.com/EAFeveUDKbg/1/0/1600w/canva-green-and-white-modern-skincare-product-listing-amazon-product-image-czDWJuSI8sg.jpg alt="Product Image">
                <h3>Product 4</h3>
                <p class="price">₹1299</p>
                <button>Buy Now</button>
            </div>
        </div>

        
    </main>

    <footer>
        <p>&copy; 2025 Snapdeal. All rights reserved.</p>
        <div class="footer-links">
            <a href="#">About Us</a>
            <a href="#">Contact</a>
            <a href="#">Terms & Conditions</a>
        </div>
    </footer>
</body>
</html>
