## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Muhammad Faizan | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    /* Reset & Base Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background-color: #f5f7fa;
      color: #333;
      line-height: 1.6;
    }
    a {
      color: #007bff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    /* Container */
    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
    }

    /* Header */
    header {
      text-align: center;
      margin-bottom: 30px;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
      color: #555;
    }

    /* Sections */
    section {
      margin-bottom: 30px;
    }
    section h2 {
      font-size: 1.8rem;
      margin-bottom: 15px;
      color: #222;
      border-bottom: 2px solid #007bff;
      display: inline-block;
      padding-bottom: 5px;
    }

    /* Skills List */
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .skills span {
      background: #007bff;
      color: #fff;
      padding: 6px 12px;
      border-radius: 8px;
      font-size: 0.9rem;
    }

    /* Projects */
    .projects .project {
      background: #f0f4ff;
      padding: 15px;
      margin-bottom: 15px;
      border-left: 4px solid #007bff;
      border-radius: 8px;
    }
    .projects .project h3 {
      margin-bottom: 8px;
      font-size: 1.2rem;
    }

    /* Contact Links */
    .contact a {
      display: inline-block;
      margin-right: 15px;
      margin-bottom: 10px;
      font-weight: 600;
    }

    /* Footer */
    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.9rem;
      color: #555;
    }
  </style>
</head>
<body>

  <div class="container">
    <header>
      <h1>Muhammad Faizan</h1>
      <p>Web Developer | Football Lover | Tech Enthusiast</p>
    </header>

    <section>
      <h2>About Me</h2>
      <p>I'm a passionate Web Developer building modern and responsive web applications. I love learning new technologies and turning ideas into reality. Outside of coding, I'm a football lover and always exploring the latest tech trends.</p>
    </section>

    <section>
      <h2>Skills</h2>
      <div class="skills">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>React</span>
        <span>Node.js</span>
        <span>PHP</span>
        <span>MySQL</span>
        <span>MongoDB</span>
        <span>Git</span>
      </div>
    </section>

    <section>
      <h2>Projects</h2>
      <div class="projects">
        <div class="project">
          <h3>Fusion E-commerce Website</h3>
          <p>Built with PHP, HTML/CSS, MySQL. Features smooth browsing and reliable backend for products & orders.</p>
          <a href="#">View Project</a>
        </div>
        <div class="project">
          <h3>Fluffy Bird Console Game (Python)</h3>
          <p>Beginner-friendly console-based game.</p>
          <a href="#">View Project</a>
        </div>
        <div class="project">
          <h3>MERN Stack Real-Time Chat App</h3>
          <p>Real-time messaging app built with React, Node.js, Express, and MongoDB. (Under development)</p>
          <a href="#">View Project</a>
        </div>
      </div>
    </section>

    <section>
      <h2>Contact</h2>
      <div class="contact">
        <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
        <a href="https://github.com/yourusername" target="_blank">GitHub</a>
        <a href="mailto:youremail@example.com">Email</a>
      </div>
    </section>

    <footer>
      &copy; 2025 Muhammad Faizan. All rights reserved.
    </footer>
  </div>

</body>
</html>
