# Ex.07 Restaurant Website
# Date:6.10.25
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - FRIENDS DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <section class="admin-grid">
    <div class="admin-card">
      <img src="saudh.jpg" alt="MOHAMED SAUDH">
      <h3>MOHAMED SAUDH</h3>
      <p>Manager</p>
    </div>

    <div class="admin-card">
      <img src="mani.jpg" alt="MANIKANDAN">
      <h3>MANIKANDAN</h3>
      <p>Head Chef</p>
    </div>

    <div class="admin-card">
      <img src="mohan.jpg" alt="MOHAN RAJI">
      <h3>MOHAN RAJI</h3>
      <p>Head Chef</p>
    </div>

    <div class="admin-card">
      <img src="sanjay.jpg" alt="SANJAI">
      <h3>SANJAI</h3>
      <p>Assistant Chef</p>
    </div>

    <div class="admin-card">
      <img src="naveen.jpg" alt="NAVEENKUMAR">
      <h3>NAVEENKUMAR</h3>
      <p>Assistant chef</p>
    </div>

    <div class="admin-card">
      <img src="hari.jpg" alt="HARI PRASATH">
      <h3>HARI PRASATH</h3>
      <p>Cashier</p>
    </div>

    <div class="admin-card">
      <img src="bal.jpg" alt="BALAJI B M">
      <h3>BALAJI B M</h3>
      <p>Inventory Manager</p>
    </div>

    <div class="admin-card">
      <img src="vicky.jpg" alt="VIGNESHWAREN">
      <h3>VIGNESHWAREN</h3>
      <p>Customer Service</p>
    </div>
  </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - FRIENDS DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>Get in Touch</h2>
    <p>📍 <strong>Address:</strong> 999 Friends Street , Chennai , Tamil Nadu</p>
    <p>📞 <strong>Phone:</strong> (999) 123-456-7890 </p>
    <p>✉ <strong>Email:</strong> friendsdabha@gmail.com</p>
  </section>
  


 <!-- Optional: Contact Form (if needed) -->
  <!--
  <section class="contact-form">
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5"></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>
  -->

  <footer>
    <p>&copy; 2025. Designed by  MOHAMED SAUDH R</p>
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - FRIENDS DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1> FRIENDS DABHA</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <section class="banner">
    <img src="hotel.jpg"Delicious Food Banner">
  </section>



  <section class="content">
    <h2>Welcome!</h2>
    <p>Discover the best food in town, made with passion and fresh ingredients.</p>
  </section>

  

  <footer>
    <p>&copy; 2025. Designed by MOHAMED SAUDH R</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - FRIENDS DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <!-- Repeat for 09 items -->
    <div class="menu-item">
      <img src="shavarma.jpg" alt="shavarma">
      <h3>Shavarma</h3>
      <p>Shavarma with the taste of Arabia</p>
    </div>
    <div class="menu-item">
      <img src="parota.jpg" alt="Parota with Beef Curry">
      <h3>Parota&Beef</h3>
      <p>Parota&Beef with vegies.</p>
    </div>
    <div class="menu-item">
      <img src="mac.jpg" alt="Mac & Cheese">
      <h3>Creamy Cheese</h3>
      <p>Sooo Cheese.. with bacon.</p>
    </div>
    <div class="menu-item">
      <img src="brownie.jpg" alt="Brownie">
      <h3>Choco Brownie</h3>
      <p>Spoongy Brownie which melts in your mouth</p>
    </div>
    <div class="menu-item">
      <img src="payasam.jpg" alt="Payasam">
      <h3>Creamy Payasam</h3>
      <p>Sweetness with the taste of Payasam.</p>
    </div>
    <div class="menu-item">
      <img src="lobster.jpg" alt="Lobster">
      <h3>Hot Lobster</h3>
      <p>Juicy Lobster with soft bun</p>
    </div>
    <div class="menu-item">
      <img src="prawn.jpg" alt="Prawn">
      <h3>GRILLED PRAWN</h3>
      <p>Juicy prawn with garlic Flavour.</p>
    </div>
    <div class="menu-item">
      <img src="zero.jpg" alt="Coke">
      <h3>Zero Sugar Coke</h3>
      <p>Cold and Refreshing Coke.</p>
    </div>
    <div class="menu-item">
      <img src="crab.jpg" alt="Crab">
      <h3>Smoked Crab</h3>
      <p>Green coloured spicy Crab.</p>
    </div>
    <div class="menu-item">
      <img src="pan.jpg" alt="Pancakes">
      <h3>Pancakes</h3>
      <p>Fluffy pancakes with syrup.</p>
    </div>
    <div class="menu-item">
      <img src="ice.jpg" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>Vanilla, chocolate, and strawberry scoops.</p>
    </div>
    <div class="menu-item">
      <img src="french.jpg" alt="Fries">
      <h3>French Fries</h3>
      <p>Crispy golden fries.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by MOHAMED SAUDH R</p>
  </footer>
</body>
</html>
/* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-06 222425.png>)
![alt text](<Screenshot 2025-10-06 222440.png>)
![alt text](<Screenshot 2025-10-06 222457.png>)
![alt text](<Screenshot 2025-10-06 222517.png>)
![alt text](<Screenshot 2025-10-06 222531.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
