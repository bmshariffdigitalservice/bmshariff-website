<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>B.M Shariff Digital Service | Growing Brands Online</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0b1120;
    color:#fff;
}

header{
    position:fixed;
    width:100%;
    top:0;
    background:rgba(0,0,0,0.7);
    backdrop-filter:blur(10px);
    z-index:1000;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
}

.logo{
    font-size:28px;
    font-weight:700;
    color:#2563eb;
}

nav ul{
    display:flex;
    list-style:none;
    gap:30px;
}

nav a{
    color:white;
    text-decoration:none;
}

.hero{
    height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:20px;
    background:
    linear-gradient(rgba(0,0,0,.8),rgba(0,0,0,.8)),
    url('https://images.unsplash.com/photo-1498050108023-c5249f4df085');
    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:900px;
    animation:fadeIn 2s;
}

.hero h1{
    font-size:4rem;
    margin-bottom:20px;
}

.hero h1 span{
    color:#2563eb;
}

.hero p{
    font-size:1.2rem;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:15px 30px;
    background:#2563eb;
    color:white;
    text-decoration:none;
    border-radius:50px;
    margin:10px;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-5px);
    background:#1d4ed8;
}

section{
    padding:100px 8%;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
    font-size:2.5rem;
    color:#2563eb;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#111827;
    padding:30px;
    border-radius:15px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
    box-shadow:0 10px 30px rgba(37,99,235,.3);
}

.card h3{
    margin-bottom:15px;
    color:#2563eb;
}

.about{
    text-align:center;
    max-width:900px;
    margin:auto;
    line-height:1.8;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.feature{
    background:#111827;
    padding:25px;
    text-align:center;
    border-radius:10px;
}

.contact{
    text-align:center;
}

.contact p{
    margin:15px 0;
    font-size:1.1rem;
}

footer{
    background:#050b18;
    text-align:center;
    padding:30px;
}

.whatsapp{
    position:fixed;
    right:20px;
    bottom:20px;
    background:#25d366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(30px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

@media(max-width:768px){
    .hero h1{
        font-size:2.5rem;
    }

    nav ul{
        display:none;
    }
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">B.M SHARIFF</div>

<ul>
<li><a href="#services">Services</a></li>
<li><a href="#about">About</a></li>
<li><a href="#why">Why Us</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<section class="hero">

<div class="hero-content">

<h1>
Growing Brands <span>Online</span>
</h1>

<p>
Professional Graphic Design, Social Media Management,
Brand Growth and Digital Marketing Services.
</p>

<a href="tel:07065728980" class="btn">
Call Now
</a>

<a href="https://wa.me/2348146299540" class="btn">
WhatsApp
</a>

</div>

</section>

<section id="services">

<h2 class="section-title">
Our Services
</h2>

<div class="services">

<div class="card">
<h3>Professional CV</h3>
<p>Modern and professional CV designs.</p>
</div>

<div class="card">
<h3>Business Cards</h3>
<p>Premium business card designs.</p>
</div>

<div class="card">
<h3>Flyers & Posters</h3>
<p>Creative promotional designs.</p>
</div>

<div class="card">
<h3>Letterheads</h3>
<p>Corporate branding materials.</p>
</div>

<div class="card">
<h3>Social Media</h3>
<p>Instagram and Facebook management.</p>
</div>

<div class="card">
<h3>Digital Marketing</h3>
<p>Helping businesses grow online.</p>
</div>

</div>

</section>

<section id="about">

<h2 class="section-title">
About Us
</h2>

<div class="about">

<p>
B.M Shariff Digital Service is a professional digital agency
based in Yola, Adamawa State. We specialize in graphic design,
branding, social media management and digital marketing solutions
that help businesses grow and succeed online.
</p>

</div>

</section>

<section id="why">

<h2 class="section-title">
Why Choose Us
</h2>

<div class="features">

<div class="feature">
Professional Designs
</div>

<div class="feature">
Fast Delivery
</div>

<div class="feature">
Affordable Pricing
</div>

<div class="feature">
Creative Solutions
</div>

<div class="feature">
Customer Satisfaction
</div>

<div class="feature">
24/7 Support
</div>

</div>

</section>

<section id="contact">

<h2 class="section-title">
Contact Us
</h2>

<div class="contact">

<p>
📞 07065728980
</p>

<p>
💬 WhatsApp: 08146299540
</p>

<p>
✉️ b.m.shariff.digital.service@gmail.com
</p>

<p>
📍 10 Waziri Street Karewa, Jimeta Yola, Adamawa State
</p>

</div>

</section>

<footer>

<h3>B.M Shariff Digital Service</h3>

<p>
Growing Brands Online
</p>

<p>
© 2026 All Rights Reserved
</p>

</footer>

<a
class="whatsapp"
href="https://wa.me/2348146299540">
WhatsApp
</a>

</body>
</html>
