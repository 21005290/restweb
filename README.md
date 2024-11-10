# Ex.07 Restaurant Website
## Date:11-11-2024

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Restaurant</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Top Elite Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Discover Delicious Meals!</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="download.jpeg" alt="Ramen">
                    <h4>Ramen</h4>
                    <p>A creamy delight with fresh herbs and parmesan cheese.</p>
                </div>
                <div class="food-item">
                    <img src="download (1).jpeg" alt="Chicken Biriyani">
                    <h4>Chicken Biroyani</h4>
                    <p>Biriyani is a specialty and traditional dish in Indian cuisine.</p>
                </div>
                <div class="food-item">
                    <img src="download (2).jpeg" alt="pizza">
                    <h4>pizza</h4>
                    <p>A pizza topped with mozzarella is my first choice.</p>
                </div>
                <div class="food-item">
                    <img src="download (3).jpeg" alt="Dessert">
                    <h4>Chocolate Cakes</h4>
                    <p>Rich and moist chocolate cake with a creamy frosting.</p>
                </div>
            </section>
        </main>
        
        
        <footer>
            <p>D S Mohammad Wasim</p>
            <p>212221040034</p>
        </footer>
    </div>
</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Menu</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Top Elite Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Delicious Food Items</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="download (4).jpeg" alt="Butter Chicken">
                    <h4>Butter Chicken</h4>
                </div>
                <div class="food-item">
                    <img src="download (1).jpeg" alt="Chicken Biriyani">
                    <h4>Chicken Biriyani</h4>
                </div>
                <div class="food-item">
                    <img src="fish.jpeg" alt="Fish Fry">
                    <h4>Fish Fry</h4>
                </div>
                <div class="food-item">
                    <img src="salad.jpeg" alt="Salad">
                    <h4>Salad</h4>
                </div>
                <div class="food-item">
                    <img src="gobi.jpeg" alt="Gobi manchurian">
                    <h4>Gobi manchurian</h4>
                </div>
                <div class="food-item">
                    <img src="burger.jpeg" alt="Burger">
                    <h4>Burger</h4>
                </div>
                <div class="food-item">
                    <img src="mutton.jpeg" alt="Mutton Kadai Gosht">
                    <h4>Mutton Kadai Gosht</h4>
                </div>
                <div class="food-item">
                    <img src="chicken.jpeg" alt="Chicken 65">
                    <h4>Chicken 65</h4>
                </div>
                <div class="food-item">
                    <img src="paneer.jpeg" alt="paneer butter masala">
                    <h4>paneer butter masala</h4>
                </div>
                <div class="food-item">
                    <img src="ramen.jpeg" alt="Miso ramen">
                    <h4>Miso ramen</h4>
                </div>
                <div class="food-item">
                    <img src="pastry.jpeg" alt="White Forest Pastry">
                    <h4>White Forest Pastry</h4>
                </div>
                <div class="food-item">
                    <img src="Mocktail.jpeg" alt="Mocktail">
                    <h4>Mocktail</h4>
                </div>
            </section>
        </main>
        
        <footer>
            <p>D S Mohammad Wasim</p>
            <p>212221040034</p>
        </footer>
    <div>
    
</body>
</html>
```
administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Administration</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Top Elite Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Meet Our Team</h2>
            <div class="team">
                <div class="member">
                    <img src="pic.jpeg" alt="Admin 1">
                    <p>John Doe - Manager</p>
                </div>
                <div class="member">
                    <img src="pic6.jpeg" alt="Admin 2">
                    <p>Jane Smith - Chef</p>
                </div>
                <div class="member">
                    <img src="pic3.jpeg" alt="Admin 3">
                    <p>Emily Johnson - Waiter</p>
                </div>
                <div class="member">
                    <img src="pic2.jpeg" alt="Admin 4">
                    <p>Michael Brown - Bartender</p>
                </div>
                <div class="member">
                    <img src="pic4.jpeg" alt="Admin 5">
                    <p>Jess Wilson - Host</p>
                </div>
                <div class="member">
                    <img src="pic5.jpg" alt="Admin 6">
                    <p>David Lee - Accountant</p>
                </div>
            </div>
        </main>
        <footer>
            <p>D S Mohammad Wasim</p>
            <p>212221040034</p>
        </footer>

    </div>
    
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Contact Us</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Top Elite Restaurent</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Get in Touch</h2>
            <p>Address: 984 Delicious Street, Food City, Chennai</p>
            <p>Phone: 6536-7690</p>
            <p>Email: TopElite@restaurant.com</p>
        </main>
        <footer>
            <p>D S Mohammad Wasim</p>
            <p>212221040034</p>
        </footer>

    </div>
    
</body>
</html>
```
styles.css
```
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html, body {
    height: 100%;
    font-family: 'Arial', sans-serif;
    background-color: #f4f6f8; /* Light background for improved readability */
    color: #333; /* Darker text color for contrast */
}

.container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header {
    background-color: #010509; /* Deep blue */
    color: #fff;
    padding: 20px;
    text-align: center;
    font-size: 1.5em;
    font-weight: bold;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
}

nav ul {
    list-style: none;
    padding: 10px 0;
    display: flex;
    justify-content: center;
    gap: 20px; /* Improved spacing */
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #c8d6e5; /* Lighter shade for hover effect */
}

main {
    flex: 1;
    padding: 20px;
    background-color: #ffffff;
    box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.05); /* Subtle shadow */
}

.team {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    margin-top: 20px;
}

.member {
    width: 25%;
    padding: 20px;
    text-align: center;
    background-color: #f9fbfd;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05); /* Soft shadow */
    transition: transform 0.3s;
}

.member:hover {
    transform: translateY(-5px); /* Lift effect on hover */
}

.member img {
    width: 80%;
    height: auto;
    border-radius: 50%;
    margin-bottom: 15px;
}

h1, h2 {
    margin: 10px 0;
}

footer {
    text-align: center;
    padding: 15px;
    background-color: #070f01;
    color: #fff;
    font-size: 0.9em;
    box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.1); /* Shadow on top */
}

.menu-items {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: space-around;
    margin: 30px 0;
}

.food-item {
    width: 220px;
    text-align: center;
    background-color: #f9fbfd;
    color: #333;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Soft shadow */
    transition: transform 0.3s, box-shadow 0.3s;
}

.food-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15); /* Elevated shadow on hover */
}

.food-item img {
    width: 80%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 10px;
}

```

## OUTPUT:
![alt text](<Screenshot 2024-11-11 001047.png>)
![alt text](<Screenshot 2024-11-11 001112.png>)
![alt text](<Screenshot 2024-11-11 001135.png>)
![alt text](<Screenshot 2024-11-11 001147.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
