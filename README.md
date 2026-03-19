<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BALULU</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600&family=Inter:wght@300;400&display=swap" rel="stylesheet">

<style>

html { scroll-behavior: smooth; }

body {
margin: 0;
background: radial-gradient(circle at top, #0a0a0a, #000);
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
align-items: center;
padding: 20px 60px;
background: rgba(0,0,0,0.8);
backdrop-filter: blur(10px);
border-bottom: 1px solid rgba(255,106,0,0.3);
z-index: 1000;
}

nav h1 {
font-family: 'Cinzel', serif;
letter-spacing: 4px;
font-size: 22px;
}

nav div {
display: flex;
gap: 30px;
}

nav a {
color: #ccc;
text-decoration: none;
position: relative;
}

nav a::after {
content: "";
position: absolute;
width: 0%;
height: 2px;
background: #ff6a00;
left: 0;
bottom: -5px;
transition: 0.3s;
}

nav a:hover::after { width: 100%; }

/* HERO */
.hero {
height: 100vh;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
animation: fadeIn 2s ease;
}

.hero h1 {
font-size: 90px;
font-family: 'Cinzel', serif;
letter-spacing: 10px;
text-shadow: 0 0 20px rgba(255,106,0,0.4);
}

.hero p {
color: #aaa;
font-size: 20px;
}

.btn {
margin-top: 30px;
padding: 14px 35px;
border: 1px solid #ff6a00;
color: #ff6a00;
text-decoration: none;
transition: 0.3s;
}

.btn:hover {
background: #ff6a00;
color: black;
box-shadow: 0 0 20px #ff6a00;
}

/* SECTION */
.section {
padding: 120px 60px;
}

/* PRODUCTS */
.products {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 50px;
}

.card {
width: 280px;
border: 1px solid rgba(255,255,255,0.1);
padding: 15px;
transition: 0.4s;
background: rgba(255,255,255,0.02);
}

.card:hover {
transform: translateY(-15px) scale(1.03);
box-shadow: 0 0 25px rgba(255,106,0,0.3);
}

.card img {
width: 100%;
}

.price {
color: #ff6a00;
}

/* ABOUT */
.about {
max-width: 800px;
margin: auto;
text-align: center;
line-height: 1.9;
font-size: 18px;
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
border-top: 1px solid rgba(255,255,255,0.1);
}

/* ANIMATIONS */
@keyframes fadeIn {
from {opacity:0;}
to {opacity:1;}
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
<a href="#collection" class="btn">Enter</a>
</section>

<section id="collection" class="section">
<h2>Signature Collection</h2>

<div class="products">

<div class="card">
<img src="https://picsum.photos/400/500?1">
<h3>Genesis</h3>
<p class="price">$1,200</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/500?2">
<h3>Phantom</h3>
<p class="price">$1,450</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/500?3">
<h3>Eclipse</h3>
<p class="price">$1,600</p>
</div>

<div class="card">
<img src="https://picsum.photos/400/500?4">
<h3>Obsidian</h3>
<p class="price">$1,350</p>
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
