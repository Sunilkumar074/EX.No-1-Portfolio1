# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sunil · Backend Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background-color: #ffffff;
      color: #333333;
      line-height: 1.6;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      background-color: #fff;
      border-bottom: 1px solid #f0f0f0;
      z-index: 10;
    }
    nav a {
      text-decoration: none;
      color: #ff6600;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ff3300;
    }
    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 2rem;
    }
    header h1 {
      font-size: 3.5rem;
      font-weight: 700;
      color: #333333;
    }
    header h2 {
      font-size: 1.5rem;
      font-weight: 500;
      margin-top: 0.5rem;
      color: #ff6600;
    }
    header img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      margin-top: 2rem;
      border: 4px solid #ff6600;
    }
    section {
      padding: 5rem 2rem;
      max-width: 900px;
      margin: auto;
    }
    section h2 {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 2rem;
      color: #ff6600;
    }
    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 1rem;
    }
    .skill {
      background-color: #fff5e6;
      padding: 1rem;
      text-align: center;
      border-radius: 10px;
      border: 1px solid #ffcc99;
      font-weight: 500;
      transition: transform 0.3s;
    }
    .skill:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(255,102,0,0.2);
    }
    footer {
      text-align: center;
      padding: 2rem;
      border-top: 1px solid #f0f0f0;
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #666666;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#skills">Skills</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <header id="home">
    <h1>SUNIL</h1>
    <h2>Backend Developer</h2>
    <img src="c:\Users\admin\Downloads\WhatsApp Image 2025-08-29 at 4.13.41 PM.jpeg" alt="Sunil photo">
  </header>

  <section id="skills">
    <h2>My Skills</h2>
    <div class="skills">
      <div class="skill">Python</div>
      <div class="skill">Java</div>
      <div class="skill">Node.js</div>
      <div class="skill">Express</div>
      <div class="skill">Django</div>
      <div class="skill">Flask</div>
      <div class="skill">REST APIs</div>
      <div class="skill">PostgreSQL</div>
      <div class="skill">MySQL</div>
      <div class="skill">MongoDB</div>
      <div class="skill">Docker</div>
      <div class="skill">CI/CD</div>
    </div>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p style="text-align:center; max-width:800px; margin:auto; font-size:1.1rem;">
      I'm <strong>Sunil</strong>, a backend developer focused on building clean, scalable, and reliable systems. I enjoy creating APIs, managing databases, and deploying projects efficiently.
    </p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p style="text-align:center; font-size:1.1rem;">📧 Email: your.email@example.com</p>
    <p style="text-align:center; font-size:1.1rem;">💻 GitHub: github.com/sunil</p>
    <p style="text-align:center; font-size:1.1rem;">🔗 LinkedIn: linkedin.com/in/sunil</p>
  </section>

  <footer>
    © <span id="year"></span> Sunil · Portfolio Website
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
```


## OUTPUT
<img width="1910" height="1011" alt="Screenshot 2025-08-29 161714" src="https://github.com/user-attachments/assets/9e601329-fe56-4425-9afc-22b0444bab4f" />
<img width="1892" height="825" alt="Screenshot 2025-08-29 161756" src="https://github.com/user-attachments/assets/358cf2b9-956d-402a-8aa3-63c026167659" />
<img width="1878" height="639" alt="Screenshot 2025-08-29 161815" src="https://github.com/user-attachments/assets/7a956bf6-c10c-4081-8dcf-4c446347436d" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
