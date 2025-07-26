<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Simple Online Shopping</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      margin: 0;
      padding: 20px;
    }

    header {
      text-align: center;
      margin-bottom: 30px;
    }

    header h1 {
      color: #333;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .product-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      width: 220px;
      padding: 15px;
      text-align: center;
    }

    .product-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 6px;
      margin-bottom: 12px;
    }

    .product-name {
      font-size: 1.1rem;
      margin-bottom: 8px;
      color: #333;
    }

    .product-price {
      color: #2a9d8f;
      font-weight: bold;
      margin-bottom: 15px;
      font-size: 1.1rem;
    }

    button {
      background-color: #e76f51;
      border: none;
      padding: 10px 15px;
      color: white;
      font-size: 1rem;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #d45c3f;
    }
  </style>
</head>
<body>
  <header>
    <h1>Online Shopping</h1>
  </header>

  <div class="products">
    <div class="product-card">
      <img src="https://via.placeholder.com/220x150?text=Product+1" alt="Product 1" />
      <div class="product-name">Classic Sneakers</div>
      <div class="product-price">$59.99</div>
      <button>Add to Cart</button>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/220x150?text=Product+2" alt="Product 2" />
      <div class="product-name">Stylish Backpack</div>
      <div class="product-price">$45.00</div>
      <button>Add to Cart</button>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/220x150?text=Product+3" alt="Product 3" />
      <div class="product-name">Wireless Headphones</div>
      <div class="product-price">$79.50</div>
      <button>Add to Cart</button>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/220x150?text=Product+4" alt="Product 4" />
      <div class="product-name">Smart Watch</div>
      <div class="product-price">$120.00</div>
      <button>Add to Cart</button>
    </div>
  </div>
</body>
</html>
