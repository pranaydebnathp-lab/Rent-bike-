<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bike Rental</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
body{
font-family:Arial,sans-serif;
background:#f5f5f5;
}

.hero{
height:90vh;
background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
url("https://images.unsplash.com/photo-1558981806-ec527fa84c39?auto=format&fit=crop&w=1600&q=80");
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
}

.card img{
height:220px;
object-fit:cover;
}

footer{
background:#111;
color:white;
padding:20px;
margin-top:40px;
text-align:center;
}
</style>

</head>

<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
<div class="container">

<a class="navbar-brand fw-bold" href="#">
🏍 Bike Rental
</a>

<button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#menu">
<span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="menu">

<ul class="navbar-nav ms-auto">

<li class="nav-item">
<a class="nav-link" href="#">Home</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#">Bikes</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#">Booking</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#">Login</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#">Contact</a>
</li>

</ul>

</div>

</div>
</nav>

<section class="hero">

<div>

<h1 class="display-3 fw-bold">
Rent Your Dream Bike
</h1>

<p class="lead">
Fast • Safe • Affordable
</p>

<a href="#" class="btn btn-warning btn-lg">
Book Now
</a>

</div>

</section>

<div class="container mt-5">

<h2 class="text-center mb-4">
Popular Bikes
</h2>

<div class="row">

<div class="col-md-4">

<div class="card shadow">

<img src="https://images.unsplash.com/photo-1558981806-ec527fa84c39?auto=format&fit=crop&w=700&q=80">

<div class="card-body">

<h4>Royal Enfield</h4>

<p>₹1200 / Day</p>

<button class="btn btn-primary w-100">
Book Now
</button>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card shadow">

<img src="https://images.unsplash.com/photo-1517846693594-1567da72af75?auto=format&fit=crop&w=700&q=80">

<div class="card-body">

<h4>KTM Duke 390</h4>

<p>₹1500 / Day</p>

<button class="btn btn-primary w-100">
Book Now
</button>

</div>

</div>

</div>

<div class="col-md-4">

<div class="card shadow">

<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=700&q=80">

<div class="card-body">

<h4>Yamaha R15</h4>

<p>₹900 / Day</p>

<button class="btn btn-primary w-100">
Book Now
</button>

</div>

</div>

</div>

</div>

</div>

<div class="container mt-5">

<h2 class="text-center mb-4">
Why Choose Us
</h2>

<div class="row text-center">

<div class="col-md-3">
<h4>✔ Verified Bikes</h4>
</div>

<div class="col-md-3">
<h4>✔ Easy Booking</h4>
</div>

<div class="col-md-3">
<h4>✔ 24×7 Support</h4>
</div>

<div class="col-md-3">
<h4>✔ Best Price</h4>
</div>

</div>

</div>

<footer>

<h5>Bike Rental System</h5>

<p>
Email : info@bikerental.com
</p>

<p>
© 2026 All Rights Reserved.
</p>

</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
