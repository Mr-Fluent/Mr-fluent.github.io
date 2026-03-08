<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Estate & Exclusive Cars</title>

<style>

body{
    font-family: Arial, sans-serif;
    margin:0;
    background:#f4f4f4;
}

header{
    background:black;
    color:white;
    text-align:center;
    padding:20px;
}

nav{
    background:#222;
    text-align:center;
    padding:10px;
}

nav a{
    color:white;
    margin:15px;
    text-decoration:none;
    font-weight:bold;
}

section{
    padding:40px;
}

h2{
    text-align:center;
    margin-bottom:30px;
}

.container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 5px 10px rgba(0,0,0,0.2);
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.card-content{
    padding:15px;
    text-align:center;
}

.price{
    color:green;
    font-weight:bold;
    font-size:18px;
}

footer{
    background:black;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}

</style>
</head>

<body>

<header>
<h1>Luxury Estates & Motors</h1>
<p>Premium Cars and Dream Homes</p>
</header>

<nav>
<a href="#cars">Automobiles</a>
<a href="#houses">Real Estate</a>
</nav>

<!-- AUTOMOBILES -->

<section id="cars">
<h2>Luxury Automobiles</h2>

<div class="container">

<div class="card">
<img src="https://images.unsplash.com/photo-1621135802920-133df287f89c">
<div class="card-content">
<h3>Lamborghini Aventador</h3>
<p class="price">$507,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1552519507-da3b142c6e3d">
<div class="card-content">
<h3>1960 Ford Mustang</h3>
<p class="price">$85,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1617814076668-7d0c4dfe8b8c">
<div class="card-content">
<h3>Ferrari SF90</h3>
<p class="price">$625,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1542362567-b07e54358753">
<div class="card-content">
<h3>Rolls Royce Phantom</h3>
<p class="price">$460,000</p>
</div>
</div>

</div>
</section>

<!-- REAL ESTATE -->

<section id="houses">
<h2>Luxury Homes</h2>

<div class="container">

<div class="card">
<img src="https://images.unsplash.com/photo-1502672260266-1c1ef2d93688">
<div class="card-content">
<h3>New York City Penthouse</h3>
<p class="price">$12,500,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1505691938895-1758d7feb511">
<div class="card-content">
<h3>Beach House with Volleyball Court</h3>
<p class="price">$4,200,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c">
<div class="card-content">
<h3>Modern House with Basketball Court</h3>
<p class="price">$3,800,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1572120360610-d971b9d7767c">
<div class="card-content">
<h3>Model House with Large Garage</h3>
<p class="price">$2,600,000</p>
</div>
</div>

</div>
</section>

<footer>
<p>© 2026 Luxury Estates & Exclusive Cars</p>
</footer>

</body>
</html>
