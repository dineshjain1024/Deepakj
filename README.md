<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Query | Deepak Goyal Glass World</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f0f0;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    .header {
      background: #000;
      color: #fff;
      padding: 40px 20px;
      font-size: 2.5rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: #fff;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      border-radius: 8px;
    }
    .card h3 {
      margin: 10px 0 5px 0;
    }
    .card p {
      color: #333;
      margin: 0;
    }
    .footer {
      background: #000;
      color: #fff;
      padding: 15px;
      margin-top: 30px;
      font-size: 1.2rem;
    }
  </style>
</head>
<body>

<div class="header">
  Welcome to <span style="color:#00e5ff">Query!</span><br>
  Deepak Goyal Glass World
</div>

<div class="products">

  <div class="card">
    <img src="https://images.pexels.com/photos/1738996/pexels-photo-1738996.jpeg" alt="Clear Glass">
    <h3>Clear Glass</h3>
    <p>Price: ₹200/pcs</p>
  </div>

  <div class="card">
    <img src="https://images.pexels.com/photos/1661471/pexels-photo-1661471.jpeg" alt="Tinted Glass">
    <h3>Tinted Glass</h3>
    <p>Price: ₹350/pcs</p>
  </div>

  <div class="card">
    <img src="https://images.pexels.com/photos/186077/pexels-photo-186077.jpeg" alt="Mirrored Glass">
    <h3>Mirrored Glass</h3>
    <p>Price: ₹500/pcs</p>
  </div>

  <div class="card">
    <img src="https://images.pexels.com/photos/209842/pexels-photo-209842.jpeg" alt="Patterned Glass">
    <h3>Patterned Glass</h3>
    <p>Price: ₹450/pcs</p>
  </div>

</div>

<div class="footer">
  Contact Us :- 9315831029
</div>

</body>
</html>
