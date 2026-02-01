# Allen-Jeong-AI-engineer
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Allen Jeong's portfolio - AI Engineer, software developer, showcasing projects and skills">
  <title>Allen Jeong | AI Engineer & Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    /* Base */
    * { box-sizing: border-box; margin:0; padding:0; }
    html { scroll-behavior: smooth; }
    body { font-family: 'Poppins', sans-serif; background: #f0f4f8; color: #333; line-height:1.6; }

    a { text-decoration: none; color: inherit; }

    /* Header */
    header {
      background: linear-gradient(135deg, #ff7eb3, #ff758c);
      color: #fff;
      text-align: center;
      padding: 80px 20px 50px;
    }
    header h1 { font-size: 3rem; margin-bottom: 10px; }
    header p { font-size: 1.3rem; opacity: 0.9; }

    /* Navigation */
    nav {
      display: flex;
      justify-content: center;
      background: #fff;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav a {
      margin: 15px 25px;
      padding: 8px 15px;
      font-weight: 600;
      border-radius: 6px;
      transition: all 0.3s ease;
    }
    nav a:hover {
      background: linear-gradient(135deg, #ff7eb3, #ff758c);
      color: #fff;
      transform: scale(1.1);
    }

    /* Main */
    main { max-width: 1000px; margin: 40px auto; padding:0 20px; }

    section {
      margin-bottom: 60px;
      padding: 25px;
      border-radius: 15px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    section:hover { transform: translateY(-5px); box-shadow: 0 12px 25px rgba(0,0,0,0.08); }

    /* Colorful Sections */
    #about { background: linear-gradient(135deg, #a1c4fd, #c2e9fb); }
    #skills { background: linear-gradient(135deg, #ffecd2, #fcb69f); }
    #projects { background: linear-gradient(135deg, #f6d365, #fda085); }
    #career { background: linear-gradient(135deg, #d4fc79, #96e6a1); }
    #contact { background: linear-gradient(135deg, #84fab0, #8fd3f4); }

    h2 {
      color: #333;
      font-size: 1.8rem;
      margin-bottom: 15px;
      border-bottom: 3px solid #fff;
      display: inline-block;
      padding-bottom: 5px;
    }
    h3 { margin-top: 20px; color: #333; }

    ul { margin-top: 10px; padding-left: 20px; }
    li { margin-bottom: 8px; }

    figure {
      margin: 20px 0; text-align: center;
      transition: transform 0.3s ease;
    }
    figure:hover { transform: scale(1.03); }
    figure img {
      max-width: 100%; border-radius: 12px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.08);
    }
    figcaption { font-size:0.9rem; color:#555; margin-top:5px; }

    /* Contact */
    #contact p { margin-bottom: 10px; font-weight:600; }
    #contact a { color:#ff758c; transition: color 0.3s ease; }
    #contact a:hover { color:#ff7eb3; }

    /* Footer */
    footer {
      text-align: center; padding:30px 20px;
      background: #333; color:#fff; margin-top:40px; border-top-left-radius:15px; border-top-right-radius:15px;
    }

    /* Responsive */
    @media(max-width:768px){
      header h1{ font-size:2.2rem; }
      header p{ font-size:1rem; }
      nav a{ margin:10px 15px; }
    }
    @media(max-width:480px){
      h2{ font-size:1.5rem; }
      section{ padding:15px; }
    }
  </style>
</head>
<body>

<header>
  <h1>Allen Jeong</h1>
  <p>Senior High School Student | Computing & AI</p>
</header>

<nav>
  <a href="#about">About Me</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
  <a href="#career">Career</a>
  <a href="#contact">Contact</a>
</nav>

<main>

  <!-- About Me -->
  <section id="about">
    <h2>About Me</h2>
    <p>I am a senior high school student with a strong interest in computing, software development, and artificial intelligence. I enjoy designing and coding applications that solve practical problems, especially those related to communication and accessibility. My long-term goal is to study computer science and contribute to technology that connects people across cultures and languages.</p>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills & Tools</h2>
    <ul>
      <li>Python, JavaScript, HTML, CSS</li>
      <li>Figma, Canva</li>
      <li>VS Code, GitHub, APIs</li>
      <li>Algorithmic thinking, event-driven programming, client–server model, data validation, UI/UX principles, iterative development</li>
    </ul>
  </section>

  <!-- Project 1 -->
  <section id="projects">
    <h2>Project Showcase: Multilingual Translation App</h2>
    <p>This project is a prototype translation application that demonstrates translation logic, API integration, and interface design. It solves real-world communication challenges caused by language barriers.</p>
    <h3>Key Features</h3>
    <ul>
      <li>Text input box for source language</li>
      <li>Dropdown menu to select target language</li>
      <li>Translate button to trigger processing</li>
      <li>Output area displaying translated text</li>
      <li>Clean, minimal interface focused on usability</li>
    </ul>
    <h3>Interface Screenshots</h3>
    <figure>
      <img src="projects/translation-app/screenshots/app-interface.png" alt="Translation App Interface">
      <figcaption>Translation App Interface</figcaption>
    </figure>
    <h3>Wireframes</h3>
    <figure>
      <img src="projects/translation-app/design/wireframe1.png" alt="Translation App Wireframe 1">
    </figure>
    <figure>
      <img src="projects/translation-app/design/wireframe2.png" alt="Translation App Wireframe 2">
    </figure>
    <p><a href="https://github.com/yourusername/multilingual-translation-app" target="_blank">View Project on GitHub</a></p>

    <h2>Project Showcase: bons.ai UI/UX Design</h2>
    <p>Designed a modern UI/UX concept for bons.ai, transforming it from a command-line tool into a graphical application. Developed a cohesive visual identity including logo, color palette, typography, and interface mockups.</p>
    <h3>Key Contributions & Skills</h3>
    <ul>
      <li>Designed UI/UX components ready for frontend implementation</li>
      <li>Built a visual design system: layout grids, typography, color palettes</li>
      <li>Created multiple interface prototypes emphasizing accessibility and readability</li>
      <li>Developed a brand identity aligned with user-friendly principles</li>
      <li>Ensured designs were code-ready for responsive development</li>
    </ul>
    <h3>Interface Screenshots</h3>
    <figure>
      <img src="projects/bonsai/screenshots/bonsai_mockup1.png" alt="bons.ai Mockup 1">
    </figure>
    <figure>
      <img src="projects/bonsai/screenshots/bonsai_mockup2.png" alt="bons.ai Mockup 2">
    </figure>
    <h3>Wireframes / Design Steps</h3>
    <figure>
      <img src="projects/bonsai/design/wireframe1.png" alt="bons.ai Wireframe 1">
    </figure>
    <figure>
      <img src="projects/bonsai/design/wireframe2.png" alt="bons.ai Wireframe 2">
    </figure>
  </section>

  <!-- Career -->
  <section id="career">
    <h2>Career Connection</h2>
    <ul>
      <li>Software Developer</li>
      <li>AI Engineer</li>
      <li>Full-Stack Developer</li>
      <li>Mobile App Developer</li>
    </ul>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:3635105404@qq.com">3635105404@qq.com</a></p>
    <p>Phone: +86 181 2710 425</p>
    <p>GitHub: <a href="https://github.com/hyunjun7pp26-hash" target="_blank">github.com/hyunjun7pp26-hash</a></p>
  </section>

</main>

<footer>
  <p>© 2026 Allen Jeong | GitHub Portfolio</p>
</footer>

</body>
</html>
