# Ex.07 Restaurant Website
## Date: 24.12.2025
# Ref No: 25018782

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

~~~

Home.html
----------

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SAVEETHA RESTAURANT</title>
<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f7f7f2;
}
header {
  background: #2f5d50;
  color: white;
  padding: 25px;
  text-align: center;
}
nav {
  background: #6fb98f;
  display: flex;
  justify-content: center;
}
nav a {
  color: #083d2b;
  padding: 14px 20px;
  text-decoration: none;
  font-weight: bold;
}
nav a:hover {
  background: #2f5d50;
  color: white;
}
section {
  padding: 60px;
  text-align: center;
}
footer {
  background: #2f5d50;
  color: white;
  text-align: center;
  padding: 15px;
}
</style>
</head>
<body>

<header>
  <h1>🍽 SAVEETHA RESTAURANT</h1>
  <p>Fresh • Tasty • Hygienic</p>
</header>

<nav>
  <a href="offers.html">Offers</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact</a>
</nav>

<section>
  <h2>Welcome to Saveetha Restaurant</h2>
  <p>Enjoy delicious food prepared by expert chefs with love and care.</p>
</section>

<footer>
  <p>&copy; 2025 Saveetha Restaurant</p>
</footer>

</body>
</html>

menu.html
---------

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Menu</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f7f7f2;
}

header {
  background: #2f5d50;
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  background: #6fb98f;
  display: flex;
  justify-content: center;
}

nav a {
  color: #083d2b;
  padding: 14px 20px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  background: #2f5d50;
  color: white;
}

.menu {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  padding: 40px;
}

.card {
  background: white;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 3px 5px rgba(0,0,0,0.1);
}

.card img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 8px;
}

.card h3 {
  color: #2f5d50;
}
</style>
</head>

<body>

<header>
  <h1>Our Menu</h1>
</header>

<nav>
  <a href="home.html">Home</a>
  <a href="offers.html">Offers</a>
  <a href="admin.html">Administration</a>
  <a href="contact.html">Contact</a>
</nav>

<div class="menu">

  <div class="card">
    <img src="images/burger.jpg" alt="Burger">
    <h3>Burger</h3>
  </div>

  <div class="card">
    <img src="images/pizza.jpg" alt="Pizza">
    <h3>Pizza</h3>
  </div>

  <div class="card">
    <img src="images/pasta.jpg" alt="Pasta">
    <h3>Pasta</h3>
  </div>

  <div class="card">
    <img src="images/dessert.jpg" alt="Dessert">
    <h3>Dessert</h3>
  </div>

  <div class="card">
    <img src="images/sandwich.jpg" alt="Sandwich">
    <h3>Sandwich</h3>
  </div>

  <div class="card">
    <img src="images/noodles.jpg" alt="Noodles">
    <h3>Noodles</h3>
  </div>

</div>

</body>
</html>

offers.html
-----------

<div class="offers">

  <div class="card">
    <img src="images/offer1.jpg" alt="Pizza Offer" style="width:100%;border-radius:8px;">
    <h3>50% Off Pizza</h3>
    <p>Every Monday</p>
  </div>

  <div class="card">
    <img src="images/offer2.jpg" alt="Burger Offer" style="width:100%;border-radius:8px;">
    <h3>Buy 1 Get 1 Burger</h3>
    <p>Every Friday</p>
  </div>

  <div class="card">
    <img src="images/offer3.jpg" alt="Dessert Offer" style="width:100%;border-radius:8px;">
    <h3>Free Dessert</h3>
    <p>Orders above ₹500</p>
  </div>

</div>


admin.html
----------

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Administration</title>
<style>
body { margin: 0; font-family: Arial; background: #f7f7f2; }
header { background: #2f5d50; color: white; padding: 20px; text-align: center; }
nav { background: #6fb98f; display: flex; justify-content: center; }
nav a { padding: 14px 20px; color: #083d2b; text-decoration: none; font-weight: bold; }
nav a:hover { background: #2f5d50; color: white; }

.team {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 40px;
}
.member {
  background: white;
  padding: 15px;
  border-radius: 8px;
  width: 150px;
  text-align: center;
}
</style>
</head>

<body>
<header>
  <h1>Our Team</h1>
</header>

<nav>
  <a href="home.html">Home</a>
  <a href="offers.html">Offers</a>
  <a href="menu.html">Menu</a>
  <a href="contact.html">Contact</a>
</nav>

<div class="team">
  <div class="member"><b>Chef Shajive Kumar</b></div>
  <div class="member"><b>Chef Bhavan Kumar</b></div>
  <div class="member"><b>Chef Rahul</b></div>
  <div class="member"><b>Chef Monish</b></div>
  <div class="member"><b>Manager Sabii</b></div>
</div>

</body>
</html>

contact.html
------------

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact</title>
<style>
body { margin: 0; font-family: Arial; background: #f7f7f2; }
header { background: #2f5d50; color: white; padding: 20px; text-align: center; }
nav { background: #6fb98f; display: flex; justify-content: center; }
nav a { padding: 14px 20px; color: #083d2b; text-decoration: none; font-weight: bold; }
nav a:hover { background: #2f5d50; color: white; }
section { padding: 40px; text-align: center; }
</style>
</head>

<body>
<header>
  <h1>Contact Us</h1>
</header>

<nav>
  <a href="home.html">Home</a>
  <a href="offers.html">Offers</a>
  <a href="menu.html">Menu</a>
  <a href="admin.html">Administration</a>
</nav>

<section>
  <p>📍 Thandalam, Kancheepuram-Chennai rd</p>
  <p>📞 +91 98765 43210</p>
  <p>📧 contact@saveetha.com</p>
</section>

</body>
</html>


~~~


## OUTPUT:

![alt text](<Screenshot 2025-12-24 191229.png>)
![alt text](<Screenshot 2025-12-24 191308.png>)
![alt text](<Screenshot 2025-12-24 191316.png>)
![alt text](<Screenshot 2025-12-24 191331.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
