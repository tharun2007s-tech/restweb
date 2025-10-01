# Ex.07 Restaurant Website
## Name:Tharun S
## Ref No:25007797
## Date:01/10/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ST RESTAURANT</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #111;
      color: white;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
    }

    header .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    header .logo img {
      width: 40px;
      height: 40px;
    }

    header .logo h1 {
      font-size: 20px;
      letter-spacing: 2px;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      color: #f1c40f;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 40px 60px;
    }

    .hero-text {
      max-width: 500px;
    }

    .hero-text h1 {
      font-size: 50px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 16px;
      margin-bottom: 30px;
    }

    .hero-text .btn {
      background: #f1c40f;
      color: black;
      padding: 12px 25px;
      font-weight: bold;
      border: none;
      cursor: pointer;
      text-transform: uppercase;
      text-decoration: none;
    }

    .hero-images {
      display: flex;
      gap: 20px;
    }

    .hero-images img {
      width: 220px;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">
      <img src="c:\Users\acer\OneDrive\Pictures\restaurant.jpg" alt="Logo">
      <h1> ST RESTAURANT color="yellow"</h1> 
    </div>
    <nav>
      <ul>
        <li><a href="about.html">ABOUT US</a></li>
        <li><a href="chefs.html">CHEFS</a></li>
        <li><a href="menu.html">MENU</a></li>
        <li><a href="gallery.html">GALLERY</a></li>
        <li><a href="contacts.html">CONTACTS</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-text">
      <h1>BEST QUALITY FOOD</h1>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestias provident laborum, recusandae delectus corrupti reprehenderit error distinctio eligendi qui consequuntur officia.</p>
      <a href="contacts.html" class="btn">Book a Table</a>
    </div>
    <div class="hero-images">
      <img src="c:\Users\acer\OneDrive\Pictures\food1.jpg" alt="Food 1">
      <img src="c:\Users\acer\OneDrive\Pictures\food2.jpg" alt="Food 2">
      <img src="c:\Users\acer\OneDrive\Pictures\food3.jpg" alt="Food 3">
    </div>
  </section>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us - ST Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
    <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #111;
      color: white;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
    }

    header .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    header .logo img {
      width: 40px;
      height: 40px;
    }

    header .logo h1 {
      font-size: 20px;
      letter-spacing: 2px;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      color: #f1c40f;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 40px 60px;
    }

    .hero-text {
      max-width: 500px;
    }

    .hero-text h1 {
      font-size: 50px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 16px;
      margin-bottom: 30px;
    }

    .hero-text .btn {
      background: #f1c40f;
      color: black;
      padding: 12px 25px;
      font-weight: bold;
      border: none;
      cursor: pointer;
      text-transform: uppercase;
      text-decoration: none;
    }

    .hero-images {
      display: flex;
      gap: 20px;
    }

    .hero-images img {
      width: 220px;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }
  </style>

  <section class="hero">
    <div class="hero-text">
      <h1>About Us</h1>
      <p>  <3 SERVING 50 YEARS OF EXCELLENCE IN MULTICUISINE FOODS ...
        AT ST RESTAURANT , WE BELIEVE FOOD IS MORE THAN A MEAL - ITS AN EXPERIENCE ... 
        FROM FARM-FRESH INGREDIENTS TO MASTERFUL COOKING ... WE BRING YOU DISHES THAT CELEBRATE SPICES AND TRADITION <3 </p>
    </div>
    <div class="hero-images">
      <img src="c:\Users\acer\OneDrive\Pictures\restaurant.jpg" alt="About ST Restaurant">
    </div>
  </section>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - ST Restaurant</title>
  <link rel="stylesheet" href="style.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #111;
      color: white;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
    }

    header .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    header .logo img {
      width: 40px;
      height: 40px;
    }

    header .logo h1 {
      font-size: 20px;
      letter-spacing: 2px;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      color: #f1c40f;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 40px 60px;
    }

    .hero-text {
      max-width: 500px;
    }

    .hero-text h1 {
      font-size: 50px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 16px;
      margin-bottom: 30px;
    }

    .hero-text .btn {
      background: #f1c40f;
      color: black;
      padding: 12px 25px;
      font-weight: bold;
      border: none;
      cursor: pointer;
      text-transform: uppercase;
      text-decoration: none;
    }

    .hero-images {
      display: flex;
      gap: 20px;
    }

    .hero-images img {
      width: 220px;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }
  </style>
  <style>
    .menu-section {
      padding: 60px;
      text-align: center;
    }

    .menu-section h1 {
      font-size: 40px;
      margin-bottom: 20px;
      color: #f1c40f;
    }

    .menu-section p {
      font-size: 16px;
      margin-bottom: 40px;
      color: #ddd;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 30px;
      justify-items: center;
    }

    .menu-card {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.6);
      text-align: center;
      transition: transform 0.3s ease;
    }

    .menu-card:hover {
      transform: translateY(-10px);
    }

    .menu-card img {
      width: 200px;
      height: 150px;
      border-radius: 10px;
      object-fit: cover;
      margin-bottom: 15px;
      border: 2px solid #f1c40f;
    }

    .menu-card h3 {
      margin: 10px 0 5px;
      color: #fff;
    }

    .menu-card p {
      font-size: 14px;
      color: #bbb;
    }
  </style>
</head>
<body>

  <!-- Menu Section -->
  <section class="menu-section">
    <h1>Our Menu</h1>
    <p>Explore our delicious range of International and Indian cuisines.</p>

    <div class="menu-grid">
      <!-- International Cuisine -->
      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\img 1.jpg" alt="Pizza">
        <h3>Italian Pizza</h3>
        <p>Classic wood-fired pizza with mozzarella & basil.</p>
      </div>

      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\image 2.jpg" alt="Pasta">
        <h3>Spaghetti Pasta</h3>
        <p>Authentic spaghetti with creamy Alfredo sauce.</p>
      </div>

      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\image 3.jpg" alt="Burger">
        <h3>Cheese Burger</h3>
        <p>Juicy grilled beef patty with cheddar & lettuce.</p>
      </div>

      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\image 4.jpg" alt="Sushi">
        <h3>Japanese Sushi</h3>
        <p>Fresh sushi rolls with salmon and avocado.</p>
      </div>

      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\image 5.jpg" alt="Steak">
        <h3>Grilled Steak</h3>
        <p>Perfectly grilled steak with garlic butter.</p>
      </div>

      <!-- Indian Cuisine -->
      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\image 6.jpg" alt="Biryani">
        <h3>Hyderabadi Biryani</h3>
        <p>Spiced rice with tender chicken & herbs.</p>
      </div>

      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\image 7.jpg" alt="Butter Chicken">
        <h3>Butter Chicken</h3>
        <p>Creamy tomato gravy with succulent chicken.</p>
      </div>

      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\image 8.jpg" alt="Dosa">
        <h3>Masala Dosa</h3>
        <p>Crispy dosa stuffed with spiced potato filling.</p>
      </div>

      <div class="menu-card">
        <img src="c:\Users\acer\OneDrive\Pictures\image 9.jpg" alt="Paneer">
        <h3>Paneer Tikka</h3>
        <p>Grilled cottage cheese with smoky spices.</p>
      </div
</body>
</html>

chefs.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Chefs - ST Restaurant</title>
  <link rel="stylesheet" href="style.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #111;
      color: white;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
    }

    header .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    header .logo img {
      width: 40px;
      height: 40px;
    }

    header .logo h1 {
      font-size: 20px;
      letter-spacing: 2px;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      color: #f1c40f;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 40px 60px;
    }

    .hero-text {
      max-width: 500px;
    }

    .hero-text h1 {
      font-size: 50px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 16px;
      margin-bottom: 30px;
    }

    .hero-text .btn {
      background: #f1c40f;
      color: black;
      padding: 12px 25px;
      font-weight: bold;
      border: none;
      cursor: pointer;
      text-transform: uppercase;
      text-decoration: none;
    }

    .hero-images {
      display: flex;
      gap: 20px;
    }

    .hero-images img {
      width: 220px;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }
  </style>
  <style>
    .chefs-section {
      padding: 60px;
      text-align: center;
    }

    .chefs-section h1 {
      font-size: 40px;
      margin-bottom: 20px;
      color: #f1c40f;
    }

    .chefs-section p {
      font-size: 16px;
      margin-bottom: 40px;
      color: #ddd;
    }

    .chefs-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 30px;
      justify-items: center;
    }

    .chef-card {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.6);
      text-align: center;
      transition: transform 0.3s ease;
    }

    .chef-card:hover {
      transform: translateY(-10px);
    }

    .chef-card img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 15px;
      border: 3px solid #f1c40f;
    }

    .chef-card h3 {
      margin: 10px 0 5px;
      color: #fff;
    }

    .chef-card p {
      font-size: 14px;
      color: #bbb;
    }
  </style>
</head>
<body>

  <!-- Chefs Section -->
  <section class="chefs-section">
    <h1>Meet Our Chefs</h1>
    <p>Our passionate chefs bring creativity and flavor to every dish they prepare.</p>

    <div class="chefs-grid">
      <div class="chef-card">
        <img src="c:\Users\acer\OneDrive\Pictures\chef 1.webp" alt="Chef John">
        <h3>Chef John Doe</h3>
        <p>Head Chef</p>
      </div>
      <div class="chef-card">
        <img src="c:\Users\acer\OneDrive\Pictures\chef 3.jpg" alt="Chef Sarah">
        <h3>Chef Sarah Lee</h3>
        <p>Pastry Specialist</p>
      </div>
      <div class="chef-card">
        <img src="c:\Users\acer\OneDrive\Pictures\chef 2.jpg" alt="Chef Michael">
        <h3>Chef Michael Tan</h3>
        <p>Italian Cuisine</p>
      </div>
      <div class="chef-card">
        <img src="c:\Users\acer\OneDrive\Pictures\chef 4.jpg" alt="Chef Priya">
        <h3>Chef Priya Sharma</h3>
        <p>Indian Spices</p>
      </div>
    </div>
  </section>
</body>
</html>

gallery.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gallery - ST Restaurant</title>
  <link rel="stylesheet" href="style.css">
  <style>
    .gallery-section {
      padding: 60px;
      text-align: center;
    }

    .gallery-section h2 {
      color: #f1c40f;
      font-size: 32px;
      margin-bottom: 40px;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .gallery-grid img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.5);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .gallery-grid img:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 16px rgba(0,0,0,0.7);
    }
  </style>
</head>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #111;
      color: white;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
    }

    header .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    header .logo img {
      width: 40px;
      height: 40px;
    }

    header .logo h1 {
      font-size: 20px;
      letter-spacing: 2px;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      color: #f1c40f;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 40px 60px;
    }

    .hero-text {
      max-width: 500px;
    }

    .hero-text h1 {
      font-size: 50px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 16px;
      margin-bottom: 30px;
    }

    .hero-text .btn {
      background: #f1c40f;
      color: black;
      padding: 12px 25px;
      font-weight: bold;
      border: none;
      cursor: pointer;
      text-transform: uppercase;
      text-decoration: none;
    }

    .hero-images {
      display: flex;
      gap: 20px;
    }

    .hero-images img {
      width: 220px;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }
  </style>
<body>
  <section class="gallery-section">
    <h2>RESTAURANT GALLERY</h2>
    <div class="gallery-grid">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 1.jpg" alt="Restaurant View 1">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 2.jpg" alt="Restaurant View 2">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 3.jpg" alt="Restaurant View 3">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 4.jpg" alt="Restaurant View 4">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 5.jpg" alt="Restaurant View 5">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 6.jpg" alt="Restaurant View 6">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 7.jpg" alt="Restaurant View 7">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 8.jpg" alt="Restaurant View 8">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 9.jpg" alt="Restaurant View 9">
      <img src="c:\Users\acer\OneDrive\Pictures\rest 10.jpg" alt="Restaurant View 10">
    </div>
  </section>
</body>
</html>

contacts.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - ST Restaurant</title>
  <link rel="stylesheet" href="style.css">
    <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #111;
      color: white;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
    }

    header .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    header .logo img {
      width: 40px;
      height: 40px;
    }

    header .logo h1 {
      font-size: 20px;
      letter-spacing: 2px;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      color: #f1c40f;
    }

    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 40px 60px;
    }

    .hero-text {
      max-width: 500px;
    }

    .hero-text h1 {
      font-size: 50px;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 16px;
      margin-bottom: 30px;
    }

    .hero-text .btn {
      background: #f1c40f;
      color: black;
      padding: 12px 25px;
      font-weight: bold;
      border: none;
      cursor: pointer;
      text-transform: uppercase;
      text-decoration: none;
    }

    .hero-images {
      display: flex;
      gap: 20px;
    }

    .hero-images img {
      width: 220px;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }
  </style>
  <style>
    .contact-section {
      padding: 60px;
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
      justify-content: center;
    }

    .contact-info {
      flex: 1;
      min-width: 280px;
      color: #ddd;
    }

    .contact-info h2 {
      color: #f1c40f;
      margin-bottom: 15px;
    }

    .contact-info p {
      margin: 8px 0;
      font-size: 15px;
    }

    .contact-form {
      flex: 1;
      min-width: 300px;
      background: #1a1a1a;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.6);
    }

    .contact-form h2 {
      margin-bottom: 20px;
      color: #f1c40f;
      text-align: center;
    }

    .contact-form form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .contact-form input,
    .contact-form select,
    .contact-form textarea {
      padding: 12px;
      border: none;
      border-radius: 8px;
      font-size: 15px;
    }

    .contact-form input:focus,
    .contact-form textarea:focus,
    .contact-form select:focus {
      outline: 2px solid #f1c40f;
    }

    .contact-form button {
      padding: 14px;
      background: #f1c40f;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
      font-weight: bold;
      color: #111;
      transition: background 0.3s ease;
    }

    .contact-form button:hover {
      background: #e0b20d;
    }
  </style>
</head>
<body>
    
  <section class="contact-section">
    <div class="contact-info">
      <h2>Contact Details</h2>
      <p><strong>📍 Address:</strong> MG Road, Bangalore, India</p>
      <p><strong>📞 Phone:</strong> +91 98765 43210</p>
      <p><strong>✉ Email:</strong> info@strestaurant.com</p>
      <p>We’re open from <strong>10 AM - 11 PM</strong> daily. Come dine with us or reserve a table below!</p>
    </div>

    <div class="contact-form">
      <h2>Book a Table</h2>
      <form action="#" method="post">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone" required>
        <input type="date" name="date" required>
        <input type="time" name="time" required>
        <select name="guests" required>
          <option value="" disabled selected>Number of Guests</option>
          <option>1 Person</option>
          <option>2 People</option>
          <option>3 People</option>
          <option>4 People</option>
          <option>5+ People</option>
        </select>
        <textarea name="message" rows="4" placeholder="Special Requests (optional)"></textarea>
        <button type="submit">Reserve Now</button>
      </form>
    </div>
  </section>
</body>
</html>

```






## OUTPUT:

![alt text](<Screenshot (32).png>)
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)
![alt text](<Screenshot (37).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
