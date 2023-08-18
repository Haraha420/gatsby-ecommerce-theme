<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Dream Next Africa Ltd</title>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  
  <section id="home">
    <div class="hero">
      <h1>Welcome to Dream Next Africa Ltd</h1>
      <p>Your Vision, Our Expertise</p>
      <a href="#services" class="cta-button">Explore Our Services</a>
    </div>
  </section>

  <!-- Other sections would go here -->

  <footer>
    <div class="footer-content">
      <p>&copy; 2023 Dream Next Africa Ltd. All rights reserved.</p>
      <ul>
        <li><a href="#">Privacy Policy</a></li>
        <li><a href="#">Terms of Use</a></li>
      </ul>
    </div>
  </footer>
</body>
</html>
/* Reset some default styling */
body, h1, h2, h3, p, ul, li {
  margin: 0;
  padding: 0;
}

/* Basic styling */
body {
  font-family: Arial, sans-serif;
}

header {
  background-color: #333;
  color: #fff;
  padding: 10px 0;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
}

nav ul li {
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #fff;
}

#home {
  background-image: url('path-to-your-hero-image.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.hero {
  background-color: rgba(0, 0, 0, 0.7);
  padding: 20px;
  border-radius: 5px;
  color: #fff;
}

.cta-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #f39c12;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 20px;
}
