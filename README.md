# Tooshort
Weight loss
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TooShort - Landing Page</title>
  <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
  <!-- Header Section -->
  <header class="header">
    <div class="container">
      <img src="assets/images/logo.png" alt="TooShort Logo" class="logo">
      <nav>
        <ul class="nav-links">
          <li><a href="#about">About</a></li>
          <li><a href="#features">Features</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1>Welcome to TooShort</h1>
      <p>Your perfect platform for [describe your service].</p>
      <a href="#features" class="btn">Explore Features</a>
      <a href="#contact" class="btn btn-secondary">Contact Us</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <div class="container">
      <h2>About TooShort</h2>
      <p>TooShort is a [short description about your platform or service]. We provide [benefits, goals, or why someone should use it].</p>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features" class="features">
    <div class="container">
      <h2>Features</h2>
      <div class="feature-item">
        <h3>Feature 1</h3>
        <p>Description of the feature.</p>
      </div>
      <div class="feature-item">
        <h3>Feature 2</h3>
        <p>Description of the feature.</p>
      </div>
      <div class="feature-item">
        <h3>Feature 3</h3>
        <p>Description of the feature.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p>Email us at: <a href="mailto:support@tooshort.com">support@tooshort.com</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2025 TooShort. All Rights Reserved.</p>
    </div>
  </footer>
</body>
</html>/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

/* Header */
.header {
  background: #007bff;
  color: white;
  padding: 20px 0;
}

.header .logo {
  max-width: 150px;
}

.nav-links {
  list-style: none;
  display: flex;
  justify-content: flex-end;
}

.nav-links li {
  margin-left: 20px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

/* Hero Section */
.hero {
  background: #f4f4f4;
  text-align: center;
  padding: 50px 20px;
}

.hero h1 {
  font-size: 2.5em;
  margin-bottom: 20px;
}

.hero p {
  margin-bottom: 20px;
}

.hero .btn {
  display: inline-block;
  background: #007bff;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
  margin: 10px;
}

.hero .btn-secondary {
  background: #555;
}

/* About Section */
.about, .features, .contact {
  padding: 50px 20px;
  text-align: center;
}

.about h2, .features h2, .contact h2 {
  margin-bottom: 20px;
}

/* Features Section */
.features .feature-item {
  margin-bottom: 20px;
}

/* Footer */
.footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 20px 0;
}
// Example: Alert when button is clicked
document.querySelectorAll('.btn').forEach(button => {
  button.addEventListener('click', () => {
    alert('Button Clicked!');
  });
});
