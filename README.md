# Ex.07 Restaurant Website
# Date:08/11/2024
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
index.html
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to NOURISH BISTRO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('back.jpg');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(244, 162, 97, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #264653;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 180px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Welcome to NOURISH BISTRO</h1>
        <p>Experience the taste of excellence!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>About Us</h2>
        <p>At NOURISH BISTRO, we are committed to serving delicious, fresh, and delightful meals to tantalize your taste buds. Join us for an unforgettable dining experience.</p>
    </div>

    <div class="features-section">
        <h2>Why Choose Us?</h2>
        <ul>
            <li>Authentic and fresh ingredients.</li>
            <li>Friendly and professional staff.</li>
            <li>A warm and inviting atmosphere.</li>
        </ul>
    </div>

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="c:\Users\admin\Desktop\ex-7.webp" alt="Delicious Food 1">
        <img src="c:\Users\admin\Desktop\ex-7.jpg" alt="Delicious Food 2">
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: K.Sai Charithanjali</p>
    </footer>
</body>
</html>
```

```
menu

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to NOURISH BISTRO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('back.jpg');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(244, 162, 97, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #264653;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 180px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Welcome to NOURISH BISTRO</h1>
        <p>Experience the taste of excellence!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>About Us</h2>
        <p>At NOURISH BISTRO, we are committed to serving delicious, fresh, and delightful meals to tantalize your taste buds. Join us for an unforgettable dining experience.</p>
    </div>

    <div class="features-section">
        <h2>Why Choose Us?</h2>
        <ul>
            <li>Authentic and fresh ingredients.</li>
            <li>Friendly and professional staff.</li>
            <li>A warm and inviting atmosphere.</li>
        </ul>
    </div>

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="c:\Users\admin\Desktop\ex-7.webp" alt="Delicious Food 1">
        <img src="c:\Users\admin\Desktop\ex-7.jpg" alt="Delicious Food 2">
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: K.Sai Charithanjali</p>
    </footer>
</body>
</html>
```
```
administration

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to NOURISH BISTRO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('back.jpg');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(244, 162, 97, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #264653;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 180px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Welcome to NOURISH BISTRO</h1>
        <p>Experience the taste of excellence!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>About Us</h2>
        <p>At NOURISH BISTRO, we are committed to serving delicious, fresh, and delightful meals to tantalize your taste buds. Join us for an unforgettable dining experience.</p>
    </div>

    <div class="features-section">
        <h2>Why Choose Us?</h2>
        <ul>
            <li>Authentic and fresh ingredients.</li>
            <li>Friendly and professional staff.</li>
            <li>A warm and inviting atmosphere.</li>
        </ul>
    </div>

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="c:\Users\admin\Desktop\ex-7.webp" alt="Delicious Food 1">
        <img src="c:\Users\admin\Desktop\ex-7.jpg" alt="Delicious Food 2">
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: K.Sai Charithanjali</p>
    </footer>
</body>
</html>
```

```
contact

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to NOURISH BISTRO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('back.jpg');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(244, 162, 97, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #264653;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 180px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Welcome to NOURISH BISTRO</h1>
        <p>Experience the taste of excellence!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>About Us</h2>
        <p>At NOURISH BISTRO, we are committed to serving delicious, fresh, and delightful meals to tantalize your taste buds. Join us for an unforgettable dining experience.</p>
    </div>

    <div class="features-section">
        <h2>Why Choose Us?</h2>
        <ul>
            <li>Authentic and fresh ingredients.</li>
            <li>Friendly and professional staff.</li>
            <li>A warm and inviting atmosphere.</li>
        </ul>
    </div>

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="c:\Users\admin\Desktop\ex-7.webp" alt="Delicious Food 1">
        <img src="c:\Users\admin\Desktop\ex-7.jpg" alt="Delicious Food 2">
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: K.Sai Charithanjali</p>
    </footer>
</body>
</html>
```

# OUTPUT:
![ex-7 img1](https://github.com/user-attachments/assets/20286103-db2f-4c3b-8168-ecad7a0f25ed)
![ex-7 img2](https://github.com/user-attachments/assets/6e754d68-b67b-47f8-a732-9e0de7afa7c1)
![ex-7 img3](https://github.com/user-attachments/assets/c1bf65f9-5646-4a89-8ce2-e053571d0361)
![ex-7 img4](https://github.com/user-attachments/assets/ba0aa946-d7c7-42ce-ae8d-36c74bb5d730)
![ex-7 img5](https://github.com/user-attachments/assets/62529193-eafe-4e0b-a7ca-363b6760dd30)





# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
