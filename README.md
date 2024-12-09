# Ex.07 Restaurant Website
## Date:9.12.24

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
index.html

index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Flavour Loft</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <div class="banner-content">
            <h1>Welcome to Our Restaurant</h1>
            <p>Delicious food,great company,and memories waiting to be made.Book your table today!</p>
        </div>
    </section>

    <footer>
        <p>Designed by [Sandhiya]</p>
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - The Flavour Loft</title>
    <link rel="stylesheet" href="styless.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Our Menu</h1>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="M1.jpeg" alt="Tiramisu">
                <h2>Tiramisu</h2>
                <p>Coffee-soaked ladyfingers layered with mascarpone and cocoa.</p>
                <p class="price">rs.350</p>
            </div>
            <div class="menu-item">
            <img src="M2.jpeg" alt="Teriyaki Chicken">
                <h2>Teriyaki Chicken</h2>
                <p>Chicken is glazed with a sweet and savory teriyaki sauce.</p>
                <p class="price">rs.450</p>
            </div>
            <div class="menu-item">
                <img src="M3.jpeg" alt="Spaghetti Carbonara">
                <h2>Spaghetti Carbonara</h2>
                <p>Spaghetti with eggs,pecorino Romano,pancetta,and black pepper.</p>
                <p class="price">rs.500</p>
            </div>
            <div class="menu-item">
                <img src="M4.jpeg" alt="Panna Cotta">
                <h2>Panna Cotta</h2>
                <p>Creamy dessert topped with berry sauce or caramel.</p>
                <p class="price">rs.350</p>
            </div>
            <div class="menu-item">
                <img src="M5.jpeg" alt="Focaccia">
                <h2>Focaccia</h2>
                <p>Flatbread topped with olive oil,rosemary,or other seasonings.</p>
                <p class="price">rs.250</p>
            </div>
            <div class="menu-item">
                <img src="M6.jpeg" alt="Eggplant Parmigiana">
                <h2>Eggplant Parmigiana</h2>
                <p>Layers of eggplant,tomato sauce,and melted cheese.</p>
                <p class="price">rs.500</p>
            </div>
        <div class="menu-item">
            <img src="M7.jpeg" alt="Barramundi">
            <h2>Barramundi</h2>
            <p>A native fish served grilled,fried,or baked.</p>
            <p class="price">rs.550</p>
        </div>
        <div class="menu-item">
            <img src="M8.jpeg" alt="Lamingtons">
            <h2>Lamingtons</h2>
            <p>Sponge cake squares coated in chocolate and coconut.</p>
            <p class="price">rs.660</p>
        </div>
        <div class="menu-item">
            <img src="M9.jpeg" alt="Limoncello">
            <h2>Limoncello</h2>
            <p>A lemon liqueur typically served as a digestif.</p>
            <p class="price">rs.850</p>
        </div>
        <div class="menu-item">
            <img src="M10.jpeg" alt="Medovik">
            <h2>Medovik</h2>
            <p>A layered honey cake with cream filling.</p>
            <p class="price">rs.250</p>
        </div>
        <div class="menu-item">
            <img src="M11.jpeg" alt="Vareniki">
            <h2>Vareniki</h2>
            <p>Dumplings filled with potatoes,cheeses,or cherries,served with sour cream.</p>
            <p class="price">rs.950</p>
        </div>
        <div class="menu-item">
            <img src="M12.jpeg" alt="Butter Chicken">
            <h2>Butter Chicken</h2>
            <p>Creamy tomato based chicken curry.</p>
            <p class="price">rs.170</p>
        </div>





    </section>

    <footer>
        <p>Designed by [Sandhiya]</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - The Flavour Loft</title>
    <link rel="stylesheet" href="sty.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h1>Meet Our Team</h1>
        <div class="team-grid">
            <div class="team-member">
                <img src="chef.2.jpeg" alt="Admin 1">
                <h2>Aarthi</h2>
                <p>General Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.4.jpeg" alt="Admin 2">
                <h2>Harish</h2>
                <p>Head Chef</p>
            </div>
            <div class="team-member">
                <img src="chef.3.jpeg" alt="Admin 3">
                <h2>Elavazhagan</h2>
                <p>Operations Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.5.jpeg" alt="Admin 4">
                <h2>Pooja</h2>
                <p>Marketing Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.1.jpeg" alt="Admin 5">
                <h2>Anirudh</h2>
                <p>HR Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.6.jpeg" alt="Admin 6">
                <h2>Ramanan</h2>
                <p>Head Waiter</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Designed by [Sandhiya]</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - The Flavour Loft</title>
    <link rel="stylesheet" href="st.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Address: 123 Restaurant St., City, Country</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@restaurant.com</p>
    </section>

    <footer>
        <p>Designed by [Sandhiya]</p>
    </footer>
</body>
</html>

```


## OUTPUT:
![alt text](<bharath/Screenshot 2024-12-09 203719.png>)
![alt text](<bharath/Screenshot 2024-12-09 203902.png>)
![alt text](<bharath/Screenshot 2024-12-09 203936.png>)
![alt text](<bharath/Screenshot 2024-12-09 203813.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
