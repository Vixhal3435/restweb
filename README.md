# Ex.07 Restaurant Website
## Date: 18-05-2025

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
    <title class="sp">
        Moorthy Cafe
    </title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&family=Gloock&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="home.css">
</head>

<body>
    <div class="header">
        <div class="logo1">
            <img src="logo.png" class="img">
            <h1 class="spice">Moorthy Cafe</h1>
        </div>
        <div class="bar">
            <input placeholder="Search">
            <button type="button" id="search">Search
        </div>
    </div>
    <div class="contents">
        <nav class="nav-contents">
            <ul>
                <li><a href="home.html" class="hyper">Home</a></li>
                <li><a href="menu.html" class="hyper">Menu</a></li>
                <li><a href="admin.html" class="hyper">Administration</a></li>
                <li><a href="contact.html" class="hyper">Contact Us</a></li>
            </ul>
        </nav>
    </div>

    <div class="image">
    </div>
    <div class="box">
        <div class="box2">
            <div class="collections">
            </div>
            <div class="words">
                <h2 class="order">Order Online</h2>
                <p class="good">Cravings delivered to your doorstep—order online now!</p>
            </div>
        </div>
        <div class="box2">
            <div class="collections2">
            </div>
            <div class="words">
                <h2 class="order">Dining</h2>
                <p class="good">Experience flavors worth gathering for—dine with us!x</p>
            </div>
        </div>
        <div class="box2">
            <div class="collections3">
            </div>
            <div class="words">
                <h2 class="order">Reserve a table</h2>
                <p class="good">Reserve your spot today and savor unforgettable moments!</p>
            </div>
        </div>
    </div>
    <br><br>

    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2025 MoorthyCafe </h2>
        <h2>Designed and Developed By <span> Vishal V</span></h2>
    </footer>
</body>


</html>

home.css
 * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header {
    background-color: beige;
    padding: 5px 0;
    text-align: center;
    margin-top: -10px;
    display: block;
}

.logo1 {
    display: flex;
    justify-content: center;
    align-items: center;
}

.img {
    top: 20px;
    height: 50px;
    border-radius: 50%;
    width: auto;
    margin-right: 5px;
}

.spice {
    font-size: 40px;
    font-weight: 700;
    color: #3d2a1f;
    font-family: Gloock;
    text-transform: uppercase;
    letter-spacing: 2px;
}

input {
    margin-left: 50px;
    height: 25px;
    width: 300px;
    border-style: dotted;
    border-color: rgb(192, 146, 146);
    background-color: rgb(244, 244, 208);
    border-radius: 5px;
    padding-left: 2px;
}

button {
    margin-right: 3px;

    height: 25px;
    width: 60px;
    border-radius: 4px;
    text-align: center;
    border: none;
    background-color: #387051;
    color: white;
    font-family: Poppins;
    font-weight: 700;
    cursor: pointer;
    letter-spacing: 1px;

}

button:hover {
    color: lavender;
    text-decoration: dashed;
}

.bar {
    margin-bottom: 10px;
    text-align: center;
}

nav {
    color: white;
    background-color: #705138;
}

li,
ul {
    padding: 5px;
    padding-left: 120px;
    padding-right: 100px;
    display: inline-block;
    height: 50px;
    width: auto;
    font-size: 20px;
    font-family: Trirong;
    font-weight: bold;
    letter-spacing: 1px;
    cursor: pointer;
}

.hyper {
    color: white;
    text-decoration: none;
}

a:hover {
    color: burlywood;
}

.image {
    width: auto;
    height: 250px;
    background-image: url(background_image.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 15px;
    margin-top: 40px;
    display: flex;
    border: 4px;
    margin-bottom: 40px;
}

.box2 {
    border-color: rgb(241, 236, 236);
    border-style: solid;
    display: inline-block;
    margin-left: 150px;
    border-radius: 10px;
}

.collections {
    width: 320px;
    height: 200px;
    background-image: url(cake.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.words {
    cursor: pointer;
    padding-top: 10px;
    padding-left: 10px;
    font-family: Trirong;
    padding-bottom: 20px;
    text-align: start;
}

.words p.good {
    max-width: 300px;
    white-space: wrap;
}

.box :hover {
    color: #705138;
}

.order {
    font-size: 20px;
}

.good {
    font-size: 15px;
}

.collections2 {
    width: 320px;
    height: 200px;
    background-image: url(table.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.collections3 {
    width: 320px;
    height: 200px;
    background-image: url(dining.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

footer {

    background-color: #705138;
    text-align: center;
    height: 70px;
    width: auto;
    padding-top: 10px;
    font-size: 13px;
    color: lavender;
    font: small-caps
}

h2 {
    display: inline;
    margin-right: 50px;
}

.terms {
    color: aliceblue;
    text-decoration: none;
}

.terms:hover {
    text-decoration: underline;
}

span {
    color: rgb(0, 195, 255);
    font-family: Dancing Script;
}
```

```
menu.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title class="sp">
        Moorthy Cafe
    </title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&family=Gloock&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Alumni+Sans+Pinstripe:ital@0;1&family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">

    <link rel="stylesheet" href="menu.css">
</head>

<body>
    <div class="header">
        <div class="logo">
            <img src="logo.png" class="img">
            <h1 class="spice">Moorthy Cafe</h1>
        </div>
        <div class="bar">
            <input placeholder="Search">
            <button type="button" id="search">Search
        </div>
    </div>
    <div class="contents">
        <nav class="nav-contents">
            <ul>
                <li><a href="home.html" class="hyper">Home</a></li>
                <li><a href="menu.html" class="hyper">Menu</a></li>
                <li><a href="admin.html" class="hyper">Administration</a></li>
                <li><a href="contact.html" class="hyper">Contact Us</a></li>
            </ul>
        </nav>
    </div>

    <div class="menus">
        <div class="items1">
        </div>
        <div class="words">
            <h2 class="order">Chicken-65</h2>
            <p class="good1">"Golden-brown, crispy, and bursting with spice—Chicken 65 is a fiery delight!
                One bite, and the heat wraps around your taste buds in the best way.
                A true feast for spice lovers!"
            </p>
        </div>
    </div>
    <div class="menus">
        <div class="items2">
        </div>
        <div class="words">
            <h2 class="order">Chicken Briyani</h2>
            <p class="good2">“In every grain of biryani lies a world of flavors, a burst of spices, and a journey into
                culinary bliss.it’s an invitation to savor the essence of tradition with every
                bite.”</p>
        </div>
    </div>
    <div class="menus">
        <div class="items3">
        </div>
        <div class="words">
            <h2 class="order">Chicken Lollipop</h2>
            <p class="good3">"Chicken Lollipop—crispy, juicy, and packed with bold spice!
                The perfect bite-sized delight to keep your cravings in check.
                One crunch, and you're hooked on its fiery magic!"
            </p>
        </div>
    </div>
    <div class="menus">
        <div class="items4">
        </div>
        <div class="words">
            <h2 class="order1">Parotta</h2>
            <p class="good4">"Flaky, crispy, and oh-so-soft—Parotta is a masterpiece of layers!
                Tear, dip, and savor the magic of this South Indian delight.
                Every bite is a buttery, chewy explosion of flavor!"
            </p>
        </div>
    </div>
    <div class="menus">
        <div class="items5">
        </div>
        <div class="words">
            <h2 class="order">Chicken Curry</h2>
            <p class="good5">"Rich, aromatic, and bursting with spice—Chicken Curry is a comforting classic!
                Every spoonful is a warm hug of bold flavors and tender chicken!"
            </p>
        </div>
    </div>
    <div class="menus">
        <div class="items6">
        </div>
        <div class="words">
            <h2 class="order">Mutton Biriyani</h2>
            <p class="good6">"Fragrant,rich,and packed with tender mutton-Mutton Biryani is a royal feast!
                Every grain of rice is infused with aromatic spices and slow-cooked.
            </p>
        </div>
    </div>
    <div class="menus">
        <div class="items7">
        </div>
        <div class="words">
            <h2 class="order">Mojito</h2>
            <p class="good7">"Cool, minty, and refreshingly tangy—Mojito is the ultimate thirst-quencher!
                A perfect blend of lime, mint, and fizz that lifts your spirits instantly.

            </p>
        </div>
    </div>
    <div class="menus">
        <div class="items8">
        </div>
        <div class="words">
            <h2 class="order">Paya Passion</h2>
            <p class="good8">"Sweet, creamy, and oh-so-cool—ice cream is pure happiness in a scoop!
                Every bite melts away worries, leaving behind a swirl of joy.
            </p>
        </div>
    </div>
    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2025 MoorthyCafe </h2>
        <h2>Designed and Developed By <span> Vishal V</span></h2>
    </footer>
</body>

</html>

menu.css
 * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header {
    background-color: beige;
    padding: 5px 0;
    text-align: center;
    margin-top: -10px;
    display: block;
}

.logo {
    display: flex;
    justify-content: center;
    align-items: center;
}

.img {
    top: 20px;
    height: 50px;
    border-radius: 50%;
    width: auto;
    margin-right: 5px;
}


.spice {
    font-size: 40px;
    font-weight: 700;
    color: #3d2a1f;
    font-family: Gloock;
    text-transform: uppercase;
    letter-spacing: 2px;
}

input {
    margin-left: 50px;
    height: 25px;
    width: 300px;
    border-style: dotted;
    border-color: rgb(192, 146, 146);
    background-color: rgb(244, 244, 208);
    border-radius: 5px;
    padding-left: 2px;
}

button {
    margin-right: 3px;
    height: 25px;
    width: 60px;
    border-radius: 4px;
    text-align: center;
    border: none;
    background-color: #387051;
    color: white;
    font-family: Poppins;
    font-weight: 700;
    cursor: pointer;
    letter-spacing: 1px;

}

button:hover {
    color: lavender;
    text-decoration: dashed;
}

.bar {
    margin-bottom: 10px;
    text-align: center;
}

nav {
    color: white;
    background-color: #705138;
    margin-bottom: 40px;
}

li,
ul {
    padding: 5px;
    padding-left: 120px;
    padding-right: 100px;
    display: inline-block;
    height: 50px;
    width: auto;
    font-size: 20px;
    font-family: Trirong;
    font-weight: bold;
    letter-spacing: 1px;
    cursor: pointer;
}

.hyper {
    color: white;
    text-decoration: none;
}

a:hover {
    color: burlywood;
}

.menus {
    border-color: rgb(241, 236, 236);
    border-style: solid;
    display: inline-block;
    margin-left: 50px;
    border-radius: 10px;
    margin-bottom: 20px;
}

.items1 {
    width: 320px;
    height: 200px;
    background-image: url(chicken_65.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.items2 {
    width: 320px;
    height: 200px;
    background-image: url(chicken_biriyani.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
    padding-bottom: 100px;
}

.items3 {
    width: 320px;
    height: 200px;
    background-image: url(chicken_lolipop.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.items4 {
    width: 320px;
    height: 200px;
    background-image: url(parotta.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.items5 {
    width: 320px;
    height: 200px;
    background-image: url(chicken_curry.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.items6 {
    width: 320px;
    height: 200px;
    background-image: url(mutton-biriyani.avif);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.items7 {
    width: 320px;
    height: 200px;
    background-image: url(mojito.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.items8{
    width: 320px;
    height: 200px;
    background-image: url(ice-cream.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.words {
    padding-top: 10px;
    padding-left: 10px;
    font-family: Trirong;
    padding-bottom: 20px;
    text-align: start;
}

.words:hover {
    cursor: pointer;
    color: darkcyan;
}

.order {
    font-size: 20px;
}

.order1 {
    font-size: 20px;
}

.words p.good1 {
    max-width: 310px;
    font-size: 15px;
}

.words p.good2 {
    max-width: 300px;
    font-size: 15px;
}

.words p.good3 {
    max-width: 300px;
    font-size: 15px;
}

.words p.good4 {
    white-space: pre wrap;
    max-width: 300px;
    font-size: 15px;
}

.words p.good5 {
    max-width: 300px;
    font-size: 15px;
}

.words p.good6 {
    max-width: 300px;
    font-size: 15px;
}

.words p.good7 {
    max-width: 300px;
    font-size: 15px;
}
.words p.good8 {
    max-width: 300px;
    font-size: 15px;
}

footer {
    top : 20px;
    background-color: #705138;
    text-align: center;
    height: 70px;
    width: auto;
    padding-top: 10px;
    font-size: 13px;
    color: lavender;
    font: small-caps
}

h2 {
    display: inline;
    margin-right: 50px;
}

.terms {
    color: aliceblue;
    text-decoration: none;
}

.terms:hover {
    text-decoration: underline;
}

span {
    color: rgb(0, 195, 255);
    font-family: Dancing Script;
}
```

```
admin.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title class="sp">
       Moorthy Cafe
    </title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&family=Gloock&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Alumni+Sans+Pinstripe:ital@0;1&family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">

    <link rel="stylesheet" href="admin.css">
</head>

<body>
    <div class="header">
        <div class="logo">
            <img src="logo.png" class="img">
            <h1 class="spice">Moorthy Cafe</h1>
        </div>
        <div class="bar">
            <input placeholder="Search">
            <button type="button" id="search">Search
        </div>
    </div>
    <div class="contents">
        <nav class="nav-contents">
            <ul>
                <li><a href="home.html" class="hyper">Home</a></li>
                <li><a href="menu.html" class="hyper">Menu</a></li>
                <li><a href="admin.html" class="hyper">Administration</a></li>
                <li><a href="contact.html" class="hyper">Contact Us</a></li>
            </ul>
        </nav>
    </div>
    <div class="admins">
        <div class="photo1">
        </div>
        <div class="names">
            <h2 class="order">Founder</h2>
        </div>
    </div>
    <div class="admins">
        <div class="photo2">
        </div>
        <div class="names">
            <h2 class="order">Manager</h2>
        </div>
    </div>
    <div class="admins">
        <div class="photo3">
        </div>
        <div class="names">
            <h2 class="order">Head Chef</h2>
        </div>
    </div>

    <br><br><br><br><br><br>
    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2025 MoorthyCafe </h2>
        <h2>Designed and Developed By <span> Vishal V</span></h2>
    </footer>
</body>

</html>

admin.css
 * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header {
    background-color: beige;
    padding: 5px 0;
    text-align: center;
    margin-top: -10px;
    display: block;
}

.logo {
    display: flex;
    justify-content: center;
    align-items: center;
}

.img {
    top: 20px;
    height: 50px;
    border-radius: 50%;
    width: auto;
    margin-right: 5px;
}


.spice {
    font-size: 40px;
    font-weight: 700;
    color: #3d2a1f;
    font-family: Gloock;
    text-transform: uppercase;
    letter-spacing: 2px;
}

input {
    margin-left: 50px;
    height: 25px;
    width: 300px;
    border-style: dotted;
    border-color: rgb(192, 146, 146);
    background-color: rgb(244, 244, 208);
    border-radius: 5px;
    padding-left: 2px;
}

button {
    margin-right: 3px;
    height: 25px;
    width: 60px;
    border-radius: 4px;
    text-align: center;
    border: none;
    background-color: #387051;
    color: white;
    font-family: Poppins;
    font-weight: 700;
    cursor: pointer;
    letter-spacing: 1px;

}

button:hover {
    color: lavender;
    text-decoration: dashed;
}

.bar {
    margin-bottom: 10px;
    text-align: center;
}

nav {
    color: white;
    background-color: #705138;
    margin-bottom: 40px;
}

li,
ul {
    padding: 5px;
    padding-left: 120px;
    padding-right: 100px;
    display: inline-block;
    height: 50px;
    width: auto;
    font-size: 20px;
    font-family: Trirong;
    font-weight: bold;
    letter-spacing: 1px;
    cursor: pointer;
}

.hyper {
    color: white;
    text-decoration: none;
}

a:hover {
    color: burlywood;
}

.admins {
    margin-left: 11%;
    border-color: rgb(241, 236, 236);
    display: inline-block;
    margin-top: 5%;
    border-radius: 10px;
    margin-bottom: 20px;
}

.photo1 {
    width: 270px;
    height: 300px;
    background-image: url(founder.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.photo2 {
    width: 270px;
    height: 300px;
    background-image: url(manager.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.photo3 {

    width: 270px;
    height: 300px;
    background-image: url(chef_photo.jpg);
    background-size: cover;
    background-position: center;
    border-radius: 10px;
    display: flex;
    border: 4px;
}

.names {
    margin-left: 30px;
    padding-top: 10px;
    padding-left: 10px;
    font-family: Trirong;
    text-align: center;
}

.order {
    font-size: 20px;
}

.words:hover {
    color: red;
}

footer {
    margin-top: 108px;
    background-color: #705138;
    text-align: center;
    height: 70px;
    width: auto;
    padding-top: 10px;
    font-size: 13px;
    color: lavender;
    font: small-caps
}

h2 {
    display: inline;
    margin-right: 50px;
}

.terms {
    color: aliceblue;
    text-decoration: none;
}

.terms:hover {
    text-decoration: underline;
}

.details-ul {
    font-family: Alumni Sans Pinstripe;
    font-size: 25px;
    margin-top: 10px;
    margin-right: 50px;
    display: inline-block;
}

span {
    color: rgb(0, 195, 255);
    font-family: Dancing Script;
}
```

```
contact.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title class="sp">
        Moorthy Cafe
    </title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&family=Gloock&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Alumni+Sans+Pinstripe:ital@0;1&family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">

    <link rel="stylesheet" href="contact.css">
</head>

<body>
    <div class="header">
        <div class="logo">
            <img src="logo.png" class="img">
            <h1 class="spice">Moorthy Cafe
            </h1>
        </div>
        <div class="bar">
            <input placeholder="Search">
            <button type="button" id="search">Search
        </div>
    </div>
    <div class="contents">
        <nav class="nav-contents">
            <ul>
                <li><a href="home.html" class="hyper">Home</a></li>
                <li><a href="menu.html" class="hyper">Menu</a></li>
                <li><a href="admin.html" class="hyper">Administration</a></li>
                <li><a href="contact.html" class="hyper">Contact Us</a></li>
            </ul>
        </nav>
    </div>

    <div class="ender">
        <div class="location">
            <h2 class="tag">Location</h2><br>
            <h3 class="iden">Moorthy Cafe 25,</h3>
            <h3 class="iden">Thekkuveethi,</h3>
            <h3 class="iden">Chidambaram</h3>
            <h3 class="iden">Tamil Nadu - 608001.</h3>
        </div>
        <div class="location2">
            <h2 class="tag">Hours</h2>
            <h3 class="iden">Mon,Tue,Wed,Thur</h3>
            <h3 class="iden"> 10.00 AM - 8.00 PM,</h3>
            <br>
            <h3 class="iden">Fri,Sat</h3>
            <h3 class="iden">10.00 AM - 9.00 PM</h3>
            <br>
            <h3 class="iden">Sun</h3>
            <h3 class="iden">11.00 AM - 4.00 PM</h3>
        </div>
        <div class="location3">
            <h2 class="tag">Find us on</h2>
            <h3 class="iden">Instagram :</h3>
            <h3 class="iden">@moorthyvibes</h3>
            <br>
            <h3 class="iden">X :</h3>
            <h3 class="iden">@Moorthy_cafe </h3>
            <br>
            <h3 class="iden">Facebook :</h3>
            <h3 class="iden">@Moorthy_Cafe_CDM</h3>
        </div>
    </div>
    <div class="details">
        <ul class="details-ul">
            <li class="details-ul"><b> 📞</b> : +91 8825492139,</li>
            <li class="details-ul"></li>
            <li class="details-ul"></li>
            <li class="details-ul"><b> 📧 </b> : moorthycafe@gmail.com</li>
        </ul>
    </div>
    <br><br><br><br><br><br>
    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2025 MoorthyCafe </h2>
        <h2>Designed and Developed By <span> Vishal V</span></h2>
    </footer>
</body>

</html>

contact.css
 * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header {
    background-color: beige;
    padding: 5px 0;
    text-align: center;
    margin-top: -10px;
    display: block;
}

.logo {
    display: flex;
    justify-content: center;
    align-items: center;
}
.img {
    top: 20px;
    height: 50px;
    border-radius: 50%;
    width: auto;
    margin-right: 5px;
}


.spice {
    font-size: 40px;
    font-weight: 700;
    color: #3d2a1f;
    font-family: Gloock;
    text-transform: uppercase;
    letter-spacing: 2px;
}

input {
    margin-left: 50px;
    height: 25px;
    width: 300px;
    border-style: dotted;
    border-color: rgb(192, 146, 146);
    background-color: rgb(244, 244, 208);
    border-radius: 5px;
    padding-left: 2px;
}

button {
    margin-right: 3px;
    height: 25px;
    width: 60px;
    border-radius: 4px;
    text-align: center;
    border: none;
    background-color: #387051;
    color: white;
    font-family: Poppins;
    font-weight: 700;
    cursor: pointer;
    letter-spacing: 1px;

}

button:hover {
    color: lavender;
    text-decoration: dashed;
}

.bar {
    margin-bottom: 10px;
    text-align: center;
}

nav {
    color: white;
    background-color: #705138;
    margin-bottom: 40px;
}

li,
ul {
    padding: 5px;
    padding-left: 120px;
    padding-right: 100px;
    display: inline-block;
    height: 50px;
    width: auto;
    font-size: 20px;
    font-family: Trirong;
    font-weight: bold;
    letter-spacing: 1px;
    cursor: pointer;
}

.hyper {
    color: white;
    text-decoration: none;
}

a:hover {
    color: burlywood;
}

.tag {
    font-family: Trirong;
    text-align: center;
    font-size: 20px;
    margin-bottom: 10px;
    text-transform: uppercase;
}

.location {
    border-radius: 20px;
    display: inline-block;
    color: black;
    margin-top: 60px;
    padding-left: 40px;
}

.iden {
    font-family: Montserrat;
    font-size: 20px;
    padding-top: 5px;
}

.ender {
    display: flex;
    width: 100%;
    height: 400px;
    background-color: #f4f4f4;
}

.location2 {
    border-radius: 20px;
    display: inline-block;
    color: black;
    margin-top: 50px;
    padding-left: 27%;
}

.location3 {
    border-radius: 20px;
    display: inline-block;
    color: black;
    margin-top: 50px;
    padding-left: 20%;
}

footer {
    background-color: #705138;
    text-align: center;
    height: 70px;
    width: auto;
    padding-top: 10px;
    font-size: 13px;
    color: lavender;
    font: small-caps
}

h2 {
    display: inline;
    margin-right: 50px;
}

.terms {
    color: aliceblue;
    text-decoration: none;
}

.terms:hover {
    text-decoration: underline;
}

.details-ul {
    font-family: Alumni Sans Pinstripe;
    font-size: 25px;
    margin-top: 10px;
    margin-right: 50px;
    display: inline-block;
}

span {
    color: rgb(0, 195, 255);
    font-family: Dancing Script;
}
```

## OUTPUT:

![alt text](<Screenshot 2025-05-18 141530.png>)

![alt text](<Screenshot 2025-05-18 141601.png>)

![alt text](<Screenshot 2025-05-18 141620.png>)

![alt text](<Screenshot 2025-05-18 141640.png>)

![alt text](<Screenshot 2025-05-18 141654.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
