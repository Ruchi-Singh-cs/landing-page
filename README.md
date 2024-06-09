#html
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


#css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: #f4f4f4;
    padding: 2rem 0;
    text-align: center;
}

.hero h1 {
    margin: 0 0 1rem;
}

.hero p {
    margin: 0 0 2rem;
}

.cta-button {
    background: #007BFF;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 2rem 0;
}

.feature {
    margin-bottom: 1.5rem;
}

.pricing-plan {
    border: 1px solid #ddd;
    padding: 1rem;
    margin-bottom: 1rem;
}

.pricing-plan h3 {
    margin-top: 0;
}

form label, form input {
    display: block;
    margin-bottom: 10px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}
