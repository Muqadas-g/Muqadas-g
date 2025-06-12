<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Muqaddas Imtiaz Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet"/>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #3f3f46; /* zinc-800 */
      color: #ffffff;
    }

    nav {
      background-color: #3f3f46;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
    }

    nav a {
      color: #ffffff;
      font-weight: 500;
      text-transform: uppercase;
      font-size: 14px;
      text-decoration: none;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #4f8bf9;
    }

    #home {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 60px 40px;
    }

    #home img {
      max-width: 300px;
      height: 300px;
      border-radius: 50%; /* makes image circle */
      object-fit: cover;
      border: 3px solid #4f8bf9;
    }

    .hero-text h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 18px;
      color: #d1d5db;
    }

    .hero-buttons a {
      padding: 12px 25px;
      margin-right: 15px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: 500;
    }

    .btn-primary {
      background-color: #4f8bf9;
      color: white;
    }

    .btn-outline {
      border: 2px solid #4f8bf9;
      color: #4f8bf9;
      background: transparent;
    }

    section {
      padding: 60px 40px;
    }

    #about {
      display: flex;
      gap: 40px;
      align-items: flex-start;
    }

    #about img {
      width: 100%;
      border-radius: 10px;
    }

    .skills, .projects, .contact, .comments {
      background-color: #52525b; /* matching combo with zinc */
      border-radius: 10px;
      padding: 30px;
      margin-bottom: 40px;
    }

    h2 {
      color: #4f8bf9;
    }

    .skills ul {
      list-style: none;
      padding: 0;
    }

    .skills li {
      display: flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 10px;
    }

    .skills i {
      font-size: 18px;
      color: #4f8bf9;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #3f3f46;
      color: #ccc;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
    <a href="#comments">Comments</a>
  </nav>

  <section id="home">
    <div class="hero-text">
      <h1>I'm <span style="color: #4f8bf9;">Muqaddas Imtiaz a Web Developer</span></h1>
      <p>I’m Muqaddas Imtiaz, a Web Developer Intern at Core Tech Innovations Company.</p>
      <div class="hero-buttons">
        <a href="#contact" class="btn-primary">Hire Me</a>
        <a href="#projects" class="btn-outline">My Work</a>
      </div>
      <div style="margin-top: 20px;">
        <a href="#"><i class="fab fa-linkedin" style="color:white; font-size: 24px; margin-right: 15px;"></i></a>
        <a href="#"><i class="fab fa-github" style="color:white; font-size: 24px; margin-right: 15px;"></i></a>
        <a href="#"><i class="fab fa-instagram" style="color:white; font-size: 24px;"></i></a>
      </div>
    </div>
    <div>
      <img src="companylogo.jpg" alt="Muqaddas Image">
    </div>
  </section>

  <section id="about">
    <div>
      <img src="mypic.jpg" alt="Muqaddas About">
    </div>
    <div>
      <h2>About Me</h2>
      <p>I am Muqaddas Imtiaz, a passionate web developer and designer who loves creating modern, user-friendly websites. I focus on clean design, functionality, and responsive layouts to bring ideas to life on the web.</p>
    </div>
  </section>

  <section id="skills" class="skills">
    <h2>Skills</h2>
    <ul>
      <li><i class="fab fa-html5"></i> HTML5</li>
      <li><i class="fab fa-css3-alt"></i> CSS3</li>
      <li><i class="fab fa-js"></i> JavaScript (Basics)</li>
      <li><i class="fas fa-mobile-alt"></i> Responsive Design</li>
      <li><i class="fas fa-code"></i> Python, Java, C</li>
    </ul>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <p>
      <strong>• Glamour Wardrobe E-commerce Site:</strong> A stylish static e-commerce website featuring modern layout and responsive design.<br>
      <strong>• Muqaddas Portfolio Website:</strong> A personal portfolio showcasing my web development and design skills.<br>
      <strong>• Red Blue Nim Game:</strong> A Python-based terminal game demonstrating basic logic and game programming skills.<br>
      <strong>• Mini Weather App (Coming Soon):</strong> A simple weather application planned for future development.
    </p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: muqaddasimtiaz230@example.com<br>Phone: +92-311-3014709</p>
  </section>

  <section id="comments" class="comments">
    <h2>Comments</h2>
    <p>Feel free to share your feedback with me. Your support motivates me to improve!</p>
  </section>

  <footer>
    &copy; 2025 Core Tech Innovations. All rights reserved.
  </footer>

</body>
</html>