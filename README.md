<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet"href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home" class="hero">
        <h1>Welcome to Our Product</h1>
        <p>Your product's main benefit summarized in a few words.</p>
        <a href="#cta" class="cta-button">Get Started</a>
    </section>

    <section id="features">
        <h2>Features</h2>
        <div class="feature">
            <h3>Feature One</h3>
            <p>Description of the first feature.</p>
        </div>
        <div class="feature">
            <h3>Feature Two</h3>
            <p>Description of the second feature.</p>
        </div>
    </section>

    <section id="pricing">
        <h2>Pricing</h2>
        <div class="pricing-plan">
            <h3>Basic</h3>
            <p>$10/month</p>
            <a href="#cta" class="cta-button">Choose Plan</a>
        </div>
        <div class="pricing-plan">
            <h3>Pro</h3>
            <p>$20/month</p>
            <a href="#cta" class="cta-button">Choose Plan</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="/submit" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <input type="submit" value="Submit">
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Your Company</p>
    </footer>
</body>
</html>

