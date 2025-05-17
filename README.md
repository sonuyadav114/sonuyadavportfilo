<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sonu Yadav - Portfolio</title>

  <!-- Font Awesome for social media icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #1d3557, #457b9d);
      color: white;
      overflow-x: hidden;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      padding: 20px;
      text-align: center;
      animation: fadeIn 2s ease-in-out;
      flex-shrink: 0;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    p.subtitle {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    main {
      flex-grow: 1;
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
      animation: slideUp 1.5s ease-out;
      width: 100%;
    }

    section {
      margin-bottom: 60px;
    }

    h2 {
      margin-bottom: 20px;
      text-align: center;
      font-weight: 600;
      font-size: 2rem;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.6;
      opacity: 0.9;
      max-width: 800px;
      margin: 0 auto 20px auto;
      text-align: center;
    }

    .btn {
      display: inline-block;
      margin: 0 auto;
      padding: 12px 24px;
      background-color: #f1faee;
      color: #1d3557;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      text-decoration: none;
      transition: background 0.3s ease;
      cursor: pointer;
      text-align: center;
      display: block;
      width: max-content;
    }

    .btn:hover {
      background-color: #a8dadc;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .project-card {
      background-color: #f1faee;
      color: #1d3557;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      transition: transform 0.3s;
      cursor: default;
    }

    .project-card:hover {
      transform: translateY(-5px);
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      background-color: #1d3557;
      flex-shrink: 0;
    }

    footer p {
      margin-bottom: 15px;
      font-weight: 600;
      font-size: 1.1rem;
    }

    .social-links a {
      margin: 0 12px;
      color: #f1faee;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
      font-size: 1.1rem;
      display: inline-flex;
      align-items: center;
    }

    .social-links a i {
      margin-right: 8px;
      font-size: 1.3rem;
    }

    .social-links a:hover {
      color: #a8dadc;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Responsive */
    @media (max-width: 600px) {
      h1 { font-size: 2rem; }
      p.subtitle, p { font-size: 1rem; }
      .btn { padding: 10px 20px; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Hello, I'm Sonu Yadav</h1>
    <p class="subtitle">Frontend Developer | Designer | Coder</p>
  </header>

  <main>

    <section id="home">
      <h2>Welcome to My Portfolio</h2>
      <p>
        I specialize in creating beautiful, responsive websites with smooth animations.
        This is a simple and elegant portfolio homepage designed with HTML, CSS, and animation.
      </p>
      <a href="#projects" class="btn">See My Projects</a>
    </section>

    <section id="projects">
      <h2>My Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <h3>Project One</h3>
          <p>A responsive landing page built with HTML and CSS.</p>
        </div>
        <div class="project-card">
          <h3>Project Two</h3>
          <p>A weather app using JavaScript and open APIs.</p>
        </div>
        <div class="project-card">
          <h3>Project Three</h3>
          <p>A personal blog template with light/dark mode toggle.</p>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <p>Connect with me:</p>
    <div class="social-links">
      <a href="https://github.com/sonuyadav" target="_blank" rel="noopener"><i class="fab fa-github"></i>GitHub</a>
      <a href="https://linkedin.com/in/sonuyadav" target="_blank" rel="noopener"><i class="fab fa-linkedin"></i>LinkedIn</a>
      <a href="https://twitter.com/sonuyadav" target="_blank" rel="noopener"><i class="fab fa-twitter"></i>Twitter</a>
      <a href="https://www.instagram.com/2osty_?igsh=ZXhuMjRsY3Z2dndu" target="_blank" rel="noopener"><i class="fab fa-instagram"></i>Instagram</a>
      <a href="https://wa.me/918651123055" target="_blank" rel="noopener"><i class="fab fa-whatsapp"></i>WhatsApp</a>
    </div>
  </footer>

</body>
</html>
