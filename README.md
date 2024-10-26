# Kelech-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>My Name</h1>
      <button class="nav-toggle" aria-label="Toggle navigation">☰</button>
      <nav class="nav-menu">
        <a href="#hero">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section id="hero">
    <div class="hero-content">
      <h2>Welcome to My World</h2>
      <p>Discover my work, passion, and vision.</p>
      <a href="#about" class="cta-button">Learn More</a>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>I am dedicated to turning ideas into reality. With expertise in various fields, I offer a comprehensive approach to creative problem-solving.</p>
      <img src="https://via.placeholder.com/400x300" alt="About me image">
    </div>
  </section>

  <section id="services">
    <div class="container">
      <h2>My Services</h2>
      <div class="services-container">
        <div class="service-item">
          <img src="https://via.placeholder.com/200x150" alt="Service 1">
          <h3>Consulting</h3>
          <p>Offering expert advice tailored to your unique needs.</p>
        </div>
        <div class="service-item">
          <img src="https://via.placeholder.com/200x150" alt="Service 2">
          <h3>Design</h3>
          <p>Creating impactful designs to enhance your brand.</p>
        </div>
        <div class="service-item">
          <img src="https://via.placeholder.com/200x150" alt="Service 3">
          <h3>Development</h3>
          <p>Building robust solutions that bring your vision to life.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <p>I’d love to connect with you. Reach out for collaborations or inquiries.</p>
      <form action="#">
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 My Name. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
