html style 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Stunning Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation -->
    <header>
        <nav>
            <div class="logo">Brand</div>
            <ul>
                <li><a href="#features">Features</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>Welcome to Our Amazing Product</h1>
            <p>Discover how our solution can help you achieve more!</p>
            <a href="#cta" class="cta-button">Get Started</a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
        <h2>Features</h2>
        <div class="feature-item">
            <h3>Feature 1</h3>
            <p>Description of feature 1</p>
        </div>
        <div class="feature-item">
            <h3>Feature 2</h3>
            <p>Description of feature 2</p>
        </div>
        <div class="feature-item">
            <h3>Feature 3</h3>
            <p>Description of feature 3</p>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="pricing">
        <h2>Pricing</h2>
        <div class="pricing-tier">
            <h3>Basic Plan</h3>
            <p>$10/month</p>
            <a href="#cta" class="cta-button">Buy Now</a>
        </div>
        <div class="pricing-tier">
            <h3>Premium Plan</h3>
            <p>$30/month</p>
            <a href="#cta" class="cta-button">Buy Now</a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Have questions? Reach out to us!</p>
        <form action="#" method="POST">
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Your Company. All rights reserved.</p>
    </footer>
</body>
</html>
CSS STYLE 
/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f7f7f7;
    color: #333;
}

/* Header Styles */
header {
    background-color: #333;
    color: white;
    padding: 20px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

nav .logo {
    font-size: 1.5em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

/* Hero Section */
.hero {
    background-image: url('https://via.placeholder.com/1600x800'); /* Replace with your own image */
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}

.hero h1 {
    font-size: 3em;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 20px;
}

.cta-button {
    background-color: #ff5722;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.cta-button:hover {
    background-color: #e64a19;
}

/* Features Section */
.features {
    background-color: #fff;
    padding: 80px 20px;
    text-align: center;
}

.features h2 {
    font-size: 2.5em;
    margin-bottom: 40px;
}

.feature-item {
    margin-bottom: 40px;
}

.feature-item h3 {
    font-size: 1.8em;
    margin-bottom: 15px;
}

/* Pricing Section */
.pricing {
    background-color: #f4f4f4;
    padding: 80px 20px;
    text-align: center;
}

.pricing h2 {
    font-size: 2.5em;
    margin-bottom: 40px;
}

.pricing-tier {
    display: inline-block;
    background-color: white;
    padding: 30px;
    margin: 20px;
    width: 250px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.pricing-tier h3 {
    font-size: 2em;
    margin-bottom: 15px;
}

.pricing-tier p {
    font-size: 1.5em;
    margin-bottom: 20px;
}

/* Contact Section */
.contact {
    background-color: #fff;
    padding: 80px 20px;
    text-align: center;
}

.contact h2 {
    font-size: 2.5em;
    margin-bottom: 40px;
}

.contact form {
    max-width: 600px;
    margin: 0 auto;
}

.contact input,
.contact textarea {
    width: 100%;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 5px;
    border: 1px solid #ddd;
    font-size: 1em;
}

.contact button {
    background-color: #ff5722;
    color: white;
    padding: 15px 30px;
    border: none;
    border-radius: 5px;
    font-size: 1.2em;
    cursor: pointer;
    transition: background-color 0.3s;
}

.contact button:hover {
    background-color: #e64a19;
}

/* Footer Styles */
footer {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}
