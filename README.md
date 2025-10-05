# kumarnc123-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Cool Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Header Section -->
  <header>
    <nav>
      <h2 class="logo">MyPortfolio<span>.</span></h2>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="content">
      <h1>Hi, I'm <span>Kumar</span></h1>
      <p>A Passionate Web Developer & Designer</p>
      <a href="#projects" class="btn">View My Work</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <div class="about-container">
      <img src="https://i.ibb.co/2M5B0k1/profile.png" alt="Profile Picture">
      <div class="text">
        <p>
          I'm a creative developer who loves bringing ideas to life with clean, modern web design. 
          My focus is on creating responsive and visually appealing websites using HTML, CSS, and JavaScript.
        </p>
        <a href="#contact" class="btn">Let's Connect</a>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>My Projects</h2>
    <div class="project-grid">
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>A responsive personal portfolio to showcase my skills and projects.</p>
      </div>
      <div class="card">
        <h3>Smart Hazard Detection</h3>
        <p>IoT-based road hazard detection system using Raspberry Pi and sensors.</p>
      </div>
      <div class="card">
        <h3>Weather App</h3>
        <p>A web app that displays real-time weather updates using an open API.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="4" required></textarea>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Kumar | All Rights Reserved</p>
  </footer>

</body>
</html>
