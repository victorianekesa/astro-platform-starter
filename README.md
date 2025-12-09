<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>OdoGwu Express Delivery Limited</title>
<style>
    * { margin:0; padding:0; box-sizing:border-box; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body { line-height:1.6; color:#333; }
    a { text-decoration:none; color:inherit; }
    header { background:#4CAF50; color:white; padding:30px 20px; text-align:center; }
    header h1 { font-size:48px; }
    header p { font-size:20px; margin-top:10px; }
    nav { display:flex; justify-content:center; background:#333; flex-wrap:wrap; }
    nav a { color:white; padding:15px 25px; transition:background 0.3s; }
    nav a:hover { background:#575757; }
    section { padding:60px 20px; }
    .hero { background:url('https://via.placeholder.com/1920x600?text=OdoGwu+Express+Delivery') no-repeat center center/cover; height:600px; display:flex; align-items:center; justify-content:center; color:white; font-size:50px; font-weight:bold; text-shadow:2px 2px 10px rgba(0,0,0,0.7); text-align:center; }
    .services { background:#f4f4f4; text-align:center; }
    .services h2 { margin-bottom:40px; font-size:36px; color:#4CAF50; }
    .service-container { display:flex; flex-wrap:wrap; justify-content:center; gap:30px; }
    .service { background:white; padding:20px; flex:1 1 300px; max-width:300px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.1); transition: transform 0.3s; }
    .service:hover { transform:translateY(-10px); }
    .service img { max-width:100%; height:200px; object-fit:cover; border-radius:10px; margin-bottom:20px; }
    .service h3 { margin-bottom:10px; color:#333; }
    .service p { color:#666; }
    .about { text-align:center; }
    .about h2 { font-size:36px; color:#4CAF50; margin-bottom:20px; }
    .about p { max-width:800px; margin:auto; font-size:18px; color:#555; }
    .contact { background:#f4f4f4; text-align:center; }
    .contact h2 { font-size:36px; color:#4CAF50; margin-bottom:30px; }
    .contact p { font-size:18px; margin-bottom:10px; }
    .contact img { max-width:400px; margin-top:20px; border-radius:10px; }
    form { max-width:500px; margin:auto; display:flex; flex-direction:column; gap:15px; }
    input, textarea { padding:10px; border-radius:5px; border:1px solid #ccc; font-size:16px; }
    button { padding:15px; border:none; border-radius:5px; background:#4CAF50; color:white; font-size:18px; cursor:pointer; transition:0.3s; }
    button:hover { background:#45a049; }
    footer { background:#333; color:white; text-align:center; padding:20px 0; }
    @media(max-width:768px){ .service-container { flex-direction:column; align-items:center; } nav { flex-direction:column; } }
</style>
</head>
<body>

<header>
<h1>OdoGwu Express Delivery Limited</h1>
<p>Reliable Delivery, Every Time</p>
</header>

<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
Fast, Secure, and Reliable Delivery Across Uganda
</section>

<section class="services" id="services">
<h2>Our Services</h2>
<div class="service-container">
<div class="service">
<img src="https://via.placeholder.com/300x200?text=Motorcycle+Delivery" alt="Motorcycle Delivery">
<h3>Motorcycle Delivery</h3>
<p>Quick and reliable small package delivery within cities using motorcycles.</p>
</div>
<div class="service">
<img src="https://via.placeholder.com/300x200?text=Car+Delivery" alt="Car Delivery">
<h3>Car Delivery</h3>
<p>Medium to large packages delivered safely across longer distances using cars.</p>
</div>
<div class="service">
<img src="https://via.placeholder.com/300x200?text=Bicycle+Delivery" alt="Bicycle Delivery">
<h3>Bicycle Delivery</h3>
<p>Eco-friendly, fast deliveries for small parcels within short distances.</p>
</div>
<div class="service">
<img src="https://via.placeholder.com/300x200?text=Truck+Delivery" alt="Truck Delivery">
<h3>Truck Delivery</h3>
<p>Heavy cargo and bulk deliveries anywhere in Uganda with trucks.</p>
</div>
</div>
</section>

<section class="about" id="about">
<h2>About Us</h2>
<p>
OdoGwu Express Delivery Limited is committed to providing fast, secure, and reliable delivery services across Uganda.  
Whether it's a small package or heavy cargo, we ensure your items reach their destination on time.  
Our fleet of motorcycles, cars, bicycles, and trucks allows us to serve both urban and rural areas efficiently.  
Trust OdoGwu Express Delivery for all your courier needs.
</p>
</section>

<section class="contact" id="contact">
<h2>Contact Us</h2>
<p>Email: <a href="mailto:btugmaker@gmail.com">btugmaker@gmail.com</a></p>
<p>Phone: <a href="tel:+256701095470">+256 701 095 470</a></p>
<p>Address: Kampala, Uganda</p>

<img src="https://via.placeholder.com/400x300?text=Contact+Us" alt="Contact Image">

<h3>Send Us a Message</h3>
<form action="https://formspree.io/f/mnqylzbp" method="POST">
<input type="text" name="name" placeholder="Your Name" required>
<input type="email" name="email" placeholder="Your Email" required>
<textarea name="message" rows="5" placeholder="Your Message" required></textarea>
<button type="submit">Send Message</button>
</form>
</section>

<footer>
<p>&copy; 2025 OdoGwu Express Delivery Limited. All Rights Reserved.</p>
</footer>

</body>
</html>
