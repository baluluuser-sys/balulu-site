<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BALULU</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600&family=Inter:wght@300;400&display=swap" rel="stylesheet">

<style>

html {
scroll-behavior: smooth;
}

body {
margin: 0;
background: #050505;
color: white;
font-family: 'Inter', sans-serif;
overflow-x: hidden;
}

/* NAVBAR */
nav {
position: fixed;
width: 100%;
display: flex;
justify-content: space-between;
padding: 20px 50px;
background: rgba(0,0,0,0.7);
backdrop-filter: blur(10px);
border-bottom: 2px solid #ff6a00;
z-index: 1000;
}

nav h1 {
font-family: 'Cinzel', serif;
letter-spacing: 3px;
}

nav a {
color: #ccc;
margin-left: 30px;
text-decoration: none;
transition: 0.3s;
}

nav a:hover {
color: #ff6a00;
}

/* HERO */
.hero {
height: 100vh;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
background: radial-gradient(circle, #111, #000);
}

.hero h1 {
font-size: 90px;
font-family: 'Cinzel', serif;
letter-spacing: 8px;
animation: fade 1.5s ease;
}

.hero p {
font-size: 22px;
color: #aaa;
margin-top: 10px;
animation: fade 2s ease;
}

.btn {
margin-top: 30px;
padding: 15px 35px;
border: 1px solid #ff6a00;
color: #ff6a00;
text-decoration: none;
transition: 0.3s;
}

.btn:hover {
background: #ff6a00;
color: black;
}

/* SECTION */
.section {
padding: 120px 60px;
border-top: 1px solid #111;
}

/* PRODUCTS */
.products {
display: flex;
justify-content: center;
gap: 40px;
flex-wrap: wrap;
}

.card {
width: 300px;
transition: 0.4s;
border: 1px solid #222;
padding: 10px;
}

.card:hover {
transform: translateY(-10px) scale(1.03);
border-color: #ff6a00;
}

.card img {
width: 100%;
}

.card h3 {
margin-top: 10px;
}

.price {
color: #ff6a00;
}

/* ABOUT */
.about {
max-width: 800px;
margin: auto;
text-align: center;
line-height: 1.8;
}

/* CONTACT */
.contact {
text-align: center;
}

.contact a {
color: #ff6a00;
text-decoration: none;
font-size: 18px;
}

/* FOOTER */
footer {
text-align: center;
padding: 40px;
color: #777;
border-top: 1px solid #222;
}

/* ANIMATION */
@keyframes fade {
from {opacity:0; transform:translateY(20px);}
to {opacity:1; transform:translateY(0);}
}

</style>
</head>

<body>

<nav>
<h1>BALULU</h1>
<div>
<a href="#">Home</a>
<a href="#collection">Collection</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</div>
</nav>

<section class="hero">
<h1>BALULU</h1>
<p>Between reality and imagination</p>
<a href="#collection" class="btn">Enter the world</a>
</section>

<section id="collection" class="section">
<h2>Collection</h2>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/400x500">
<h3>Genesis</h3>
<p class="price">$1200</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/400x500">
<h3>Phantom</h3>
<p class="price">$1450</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/400x500">
<h3>Eclipse</h3>
<p class="price">$1600</p>
</div>

</div>
</section>

<section id="about" class="section">
<h2>About BALULU</h2>

<p class="about">
Leather is real. It comes from life — raw and untamed.  
Art is silent, yet filled with soul.  

BALULU was created where these worlds collide.  

A brand that transforms contrast into identity.  
A vision that refuses to be ordinary.  

BALULU is not here to follow trends —  
it is here to conquer the market.  

This is only the beginning.
</p>

</section>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BALULU</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600&family=Inter:wght@300;400&display=swap" rel="stylesheet">

<style>

html {
scroll-behavior: smooth;
}

body {
margin: 0;
background: #050505;
color: white;
font-family: 'Inter', sans-serif;
overflow-x: hidden;
}

/* NAVBAR */
nav {
position: fixed;
width: 100%;
display: flex;
justify-content: space-between;
padding: 20px 50px;
background: rgba(0,0,0,0.7);
backdrop-filter: blur(10px);
border-bottom: 2px solid #ff6a00;
z-index: 1000;
}

nav h1 {
font-family: 'Cinzel', serif;
letter-spacing: 3px;
}

nav a {
color: #ccc;
margin-left: 30px;
text-decoration: none;
transition: 0.3s;
}

nav a:hover {
color: #ff6a00;
}

/* HERO */
.hero {
height: 100vh;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
background: radial-gradient(circle, #111, #000);
}

.hero h1 {
font-size: 90px;
font-family: 'Cinzel', serif;
letter-spacing: 8px;
animation: fade 1.5s ease;
}

.hero p {
font-size: 22px;
color: #aaa;
margin-top: 10px;
animation: fade 2s ease;
}

.btn {
margin-top: 30px;
padding: 15px 35px;
border: 1px solid #ff6a00;
color: #ff6a00;
text-decoration: none;
transition: 0.3s;
}

.btn:hover {
background: #ff6a00;
color: black;
}

/* SECTION */
.section {
padding: 120px 60px;
border-top: 1px solid #111;
}

/* PRODUCTS */
.products {
display: flex;
justify-content: center;
gap: 40px;
flex-wrap: wrap;
}

.card {
width: 300px;
transition: 0.4s;
border: 1px solid #222;
padding: 10px;
}

.card:hover {
transform: translateY(-10px) scale(1.03);
border-color: #ff6a00;
}

.card img {
width: 100%;
}

.card h3 {
margin-top: 10px;
}

.price {
color: #ff6a00;
}

/* ABOUT */
.about {
max-width: 800px;
margin: auto;
text-align: center;
line-height: 1.8;
}

/* CONTACT */
.contact {
text-align: center;
}

.contact a {
color: #ff6a00;
text-decoration: none;
font-size: 18px;
}

/* FOOTER */
footer {
text-align: center;
padding: 40px;
color: #777;
border-top: 1px solid #222;
}

/* ANIMATION */
@keyframes fade {
from {opacity:0; transform:translateY(20px);}
to {opacity:1; transform:translateY(0);}
}

</style>
</head>

<body>

<nav>
<h1>BALULU</h1>
<div>
<a href="#">Home</a>
<a href="#collection">Collection</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</div>
</nav>

<section class="hero">
<h1>BALULU</h1>
<p>Between reality and imagination</p>
<a href="#collection" class="btn">Enter the world</a>
</section>

<section id="collection" class="section">
<h2>Collection</h2>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/400x500">
<h3>Genesis</h3>
<p class="price">$1200</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/400x500">
<h3>Phantom</h3>
<p class="price">$1450</p>
</div>

<div class="card">
<img src="https://via.placeholder.com/400x500">
<h3>Eclipse</h3>
<p class="price">$1600</p>
</div>

</div>
</section>

<section id="about" class="section">
<h2>About BALULU</h2>

<p class="about">
Leather is real. It comes from life — raw and untamed.  
Art is silent, yet filled with soul.  

BALULU was created where these worlds collide.  

A brand that transforms contrast into identity.  
A vision that refuses to be ordinary.  

BALULU is not here to follow trends —  
it is here to conquer the market.  

This is only the beginning.
</p>

</section>

<section id="contact" class="section contact">
<h2>Contact</h2>

<p>For business inquiries:</p>

<a href="mailto:baluluuser@gmail.com">baluluuser@gmail.com</a>

</section>

<footer>
© BALULU — Future of Luxury
</footer>

</body>
</html>

<section id="contact" class="section contact">
<h2>Contact</h2>

<p>For business inquiries:</p>

<a href="mailto:baluluuser@gmail.com">baluluuser@gmail.com</a>

</section>

<footer>
© BALULU — Future of Luxury
</footer>

</body>
</html>
