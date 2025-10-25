<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lakshmi Designs - Custom Tailoring & Stitching</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    
<style>
/* -------------------------------------------
   CSS (Cascading Style Sheets) for Styling
   ------------------------------------------- */

/* Global Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    color: #333;
    line-height: 1.6;
    background-color: #f4f4f4;
}

/* Header and Navigation */
header {
    background-color: #7b1fa2; /* Deep Purple */
    color: white;
    padding: 15px 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: fixed;
    width: 100%;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

.logo {
    font-size: 1.8em;
    font-weight: bold;
    letter-spacing: 1px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 25px;
    font-weight: 500;
    transition: color 0.3s;
}

nav a:hover {
    color: #ffd700; /* Gold */
}

/* Hero Section (Video Background) */
.hero-section {
    position: relative;
    height: 100vh; /* Full viewport height */
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    overflow: hidden;
}

#video-background {
    position: absolute;
    top: 50%;
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: -1;
    transform: translate(-50%, -50%);
    object-fit: cover;
}

.hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.6); /* Dark semi-transparent overlay */
    z-index: 0;
}

.hero-content {
    position: relative;
    z-index: 1;
    padding: 20px;
    max-width: 800px;
}

.hero-content h1 {
    font-size: 3.5em;
    margin-bottom: 10px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
}

.hero-content p {
    font-size: 1.5em;
    margin-bottom: 30px;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.8);
}

.whatsapp-btn {
    display: inline-block;
    background-color: #25d366; /* WhatsApp Green */
    color: white;
    padding: 15px 30px;
    text-decoration: none;
    font-size: 1.4em;
    font-weight: bold;
    border-radius: 50px;
    transition: background-color 0.3s, transform 0.2s;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
}

.whatsapp-btn:hover {
    background-color: #128c7e;
    transform: scale(1.05);
}

/* General Section Styling */
section {
    padding: 60px 5%;
    text-align: center;
}

.section-title {
    font-size: 2.5em;
    color: #7b1fa2;
    margin-bottom: 40px;
    position: relative;
    display: inline-block;
}

.section-title::after {
    content: '';
    display: block;
    width: 60%;
    height: 3px;
    background-color: #ffd700;
    margin: 8px auto 0;
}

/* Services Section */
#services {
    background-color: white;
}

.service-grid {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    gap: 30px;
}

.service-card {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 30px;
    width: 300px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.service-card h3 {
    color: #7b1fa2;
    margin-bottom: 15px;
    font-size: 1.4em;
}

.icon {
    font-size: 2.5em;
    color: #ffd700;
    margin-bottom: 10px;
    /* Using simple text icons since we don't have font-awesome/icons */
}


/* How It Works Section */
#how-it-works {
    background-color: #f9f9f9;
}

.works-list {
    list-style: none;
    max-width: 800px;
    margin: 0 auto;
    text-align: left;
}

.works-list li {
    background-color: white;
    padding: 20px;
    margin-bottom: 15px;
    border-left: 5px solid #7b1fa2;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
    font-size: 1.1em;
}

.works-list strong {
    color: #7b1fa2;
}

.works-note {
    margin-top: 30px;
    background-color: #fffacd; /* Light yellow for note */
    padding: 15px;
    border-radius: 5px;
    border: 1px dashed #ffd700;
    font-weight: bold;
    font-style: italic;
    color: #8b4513; /* Brown text for contrast */
}

/* Footer */
footer {
    background-color: #5d0f80; /* Darker Purple */
    color: white;
    padding: 30px 5%;
    text-align: center;
}

footer p {
    margin: 5px 0;
}

footer a {
    color: #ffd700;
    text-decoration: none;
}

/* Responsive Design */
@media (max-width: 768px) {
    .logo {
        font-size: 1.5em;
    }

    nav {
        display: none; /* Hide nav for simplicity on mobile, or implement a hamburger menu */
    }

    .hero-content h1 {
        font-size: 2.5em;
    }

    .hero-content p {
        font-size: 1.2em;
    }

    .whatsapp-btn {
        font-size: 1.2em;
        padding: 12px 25px;
    }

    .service-card {
        width: 100%;
    }
}
</style>
</head>
<body>

<header>
    <div class="logo">Lakshmi Designs</div>
    <nav>
        <a href="#services">Services</a>
        <a href="#how-it-works">How It Works</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero-section">
    <video autoplay muted loop id="video-background">
        <source src="video/design_bg.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <div class="hero-overlay"></div>
    <div class="hero-content">
        <h1>Stitch Perfection. Delivered to You.</h1>
        <p>Custom Tailoring for Dresses, Blouses, and Sarees—Right from the comfort of your home in [Your City/Area Name].</p>
        <a href="https://wa.me/918639299665?text=Hello%2C%20I%20would%20like%20to%20get%20a%20quote%20for%20stitching%20from%20Lakshmi%20Designs." class="whatsapp-btn" target="_blank">
            <span class="icon">&#x1F4F1;</span> Contact on WhatsApp: 8639299665
        </a>
    </div>
</section>

<section id="services">
    <h2 class="section-title">Our Expert Stitching Services</h2>
    <div class="service-grid">
        <div class="service-card">
            <div class="icon">&#x1F457;</div>
            <h3>Custom Dresses</h3>
            <p>From simple daily wear to stunning designer gowns, we tailor all types of dresses to your exact measurements and style.</p>
        </div>
        <div class="service-card">
            <div class="icon">&#x1F45A;</div>
            <h3>Designer Blouses</h3>
            <p>Perfect fits for Sarees and Lehengas. Elegant necklines, back designs, and impeccable finishing.</p>
        </div>
        <div class="service-card">
            <div class="icon">&#x1F9BD;</div>
            <h3>Saree Fall & Pico</h3>
            <p>Professional Saree finishing services including Fall stitching and Pico edging for a perfect drape.</p>
        </div>
    </div>
</section>

<section id="how-it-works">
    <h2 class="section-title">The Lakshmi Designs Advantage</h2>
    <ul class="works-list">
        <li>
            <strong>Step 1: Contact Us</strong> - Message us on WhatsApp with your stitching request and preferred time.
        </li>
        <li>
            <strong>Step 2: Free Home Pickup</strong> - <span id="note-1">All dress and blouse material will be picked up from your home.</span> We'll schedule a time to collect the fabric and take your measurements (if needed).
        </li>
        <li>
            <strong>Step 3: Expert Stitching</strong> - Our skilled tailors create your garment with precision, care, and attention to detail.
        </li>
        <li>
            <strong>Step 4: Home Delivery</strong> - Your beautifully stitched garment is delivered back to your doorstep.
        </li>
    </ul>
    <div class="works-note">
        <p>1. **Free First Pickup:** Your first cloth material pick-up is absolutely free!</p>
    </div>
</section>

<footer id="contact">
    <p>&copy; 2025 Lakshmi Designs. All rights reserved.</p>
    <p>Contact us on WhatsApp: <a href="https://wa.me/918639299665" target="_blank">91 8639299665</a></p>
    <p>Email: <a href="mailto:contact@lakshmidesigns.com">contact@lakshmidesigns.com (Placeholder)</a></p>
</footer>

<script>
// Simple JavaScript for smooth scrolling when clicking on navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        // Only apply smooth scroll to internal links, not the WhatsApp link
        if(this.getAttribute('href') !== '#') {
            e.preventDefault();
            document.querySelector(this.getAttribute('href')).scrollIntoView({
                behavior: 'smooth'
            });
        }
    });
});

// You can add more advanced features here, like a gallery carousel or form validation.
</script>

</body>
</html>
