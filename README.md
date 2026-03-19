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
background: #050505;
color: white;
font-family: 'Inter', sans-serif;
}

/* NAVBAR FIXED */
nav {
position: fixed;
width: 100%;
display: flex;
justify-content: space-between;
align-items: center;
padding: 20px 60px;
background: rgba(0,0,0,0.85);
border-bottom: 2px solid #ff6a00;
z-index: 1000;
}

nav h1 {
font-family: 'Cinzel', serif;
letter-spacing: 4px;
font-size: 22px;
}

nav div {
display: flex;
gap: 25px;
}

nav a {
color: #ccc;
text-decoration: none;
transition: 0.3s;
}

nav a:hover { color: #ff6a00; }

/* HERO */
.hero {
height: 100vh;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
padding-top: 80px;
}

.hero h1 {
font-size: 80px;
font-family: 'Cinzel', serif;
letter-spacing: 8px;
}

.hero p { color: #aaa; }

.btn {
margin-top: 25px;
padding: 14px 30px;
border: 1px solid #ff6a00;
color: #ff6a00;
text-decoration: none;
}

.btn:hover {
background: #ff6a00;
color: black;
}

/* SECTION */
.section {
padding: 100px 60px;
}

/* PRODUCTS */
.products {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 40px;
}

.card {
width: 280px;
border: 1px solid #222;
padding: 15px;
transition: 0.4s;
}

.card:hover {
transform: translateY(-10px);
border-color: #ff6a00;
}

.card img {
width: 100%;
border-bottom: 1px solid #333;
margin-bottom: 10px;
}

.price { color: #ff6a00; }

/* ABOUT */
.about {
max-width: 750px;
margin: auto;
text-align: center;
line-height: 1.8;
}

/* CONTACT */
.contact { text-align: center; }

.contact a {
color: #ff6a00;
text-decoration: none;
}

/* FOOTER */
footer {
text-align: center;
padding: 30px;
color: #777;
border-top: 1px solid #222;
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
<a href="#contact">Contact</a
