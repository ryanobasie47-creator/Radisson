<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Radisson Breeze Hotel</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background: #0b4f6c;
            color: white;
            text-align: center;
            padding: 30px;
        }

        nav {
            background: #08384d;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1566073771259-6a8506099945?w=1200')
                center/cover;
            height: 400px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .hero h2 {
            background: rgba(0,0,0,0.6);
            padding: 15px;
            border-radius: 10px;
        }

        section {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .contact {
            background: #0b4f6c;
            color: white;
            border-radius: 10px;
            padding: 30px;
        }

        footer {
            text-align: center;
            background: #08384d;
            color: white;
            padding: 15px;
            margin-top: 20px;
        }

        .price {
            color: #0b4f6c;
            font-size: 28px;
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <h1>Radisson Breeze Hotel</h1>
    <p>Your Comfort, Our Priority</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#rooms">Rooms</a>
    <a href="#facilities">Facilities</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    <h2>Welcome to Radisson Breeze Hotel - Malaba, Busia</h2>
</div>

<section id="about">
    <h2>About Us</h2>
    <p>
        Radisson Breeze Hotel is a comfortable and affordable destination
        located in Malaba, Busia. We offer quality accommodation, a lively
        bar, family-friendly facilities, free parking, and 24-hour security
        to ensure a pleasant stay for all our guests.
    </p>
</section>

<section id="rooms">
    <h2>Our Rooms</h2>
    <div class="card">
        <h3>Standard Room</h3>
        <p class="price">KSh 1,500 per night</p>
        <p>Clean, comfortable, and affordable accommodation.</p>
    </div>
</section>

<section id="facilities">
    <h2>Facilities & Services</h2>
    <div class="features">
        <div class="card">
            <h3>🍹 Bar</h3>
            <p>Enjoy refreshing drinks and a relaxing atmosphere.</p>
        </div>

        <div class="card">
            <h3>🏞 Playground</h3>
            <p>A fun and safe playground for families and children.</p>
        </div>

        <div class="card">
            <h3>🚗 Free Parking</h3>
            <p>Secure parking available at no extra cost.</p>
        </div>

        <div class="card">
            <h3>🛡 24-Hour Security</h3>
            <p>Professional security services available day and night.</p>
        </div>
    </div>
</section>

<section id="contact">
    <div class="contact">
        <h2>Contact & Orders</h2>
        <p><strong>Location:</strong> Malaba, Busia, Kenya</p>
        <p><strong>Order / Booking Number:</strong> 0724383718</p>
        <p><strong>Instagram:</strong> @tj_ryan_2</p>
        <br>
        <p>Call us today to book your stay at Radisson Breeze Hotel.</p>
    </div>
</section>

<footer>
    <p>&copy; 2026 Radisson Breeze Hotel. All Rights Reserved.</p>
</footer>

</body>
</html>
  
