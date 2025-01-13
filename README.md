# readMe.md
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Dignesh Solanki's portfolio showcasing skills, education, experience, and projects in software engineering.">
    <title>Dignesh Solanki Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
  body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    color: #333;
    background-color: #ffffff;
}

.hero {
    height: 100vh;
    background: linear-gradient(to right, #6a11cb, #2575fc);
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
}

.profile-picture {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 20px;
    border: 4px solid white;
    object-fit: cover;
}

.hero h1 {
    font-size: 4rem;
    margin: 0;
}

.hero p {
    font-size: 1.5rem;
    margin: 0;
}

.hero-content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.hero-nav {
    margin-top: 20px;
    margin-left: 150px;
    margin-right: 150px;
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.hero-nav a {
    color: white;
    text-decoration: none;
    font-size: 1.2rem;
    border: 2px solid white;
    padding: 10px 20px;
    border-radius: 5px;
    transition: all 0.3s ease-in-out;
}

.hero-nav a:hover {
    background: white;
    color: #2575fc;
}

.section {
    padding: 10px 10px;
    text-align: center;
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); /* Maintain flexibility */
    gap: 15px;
    margin-top: 15px;
    margin-left: 150px;
    margin-right: 150px;
    justify-items: center;
  }
  
  .skill-card {
    background: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: trasform 0.3s;
    height: 100px;
    width: 90px; /* Adjust as needed */
    /* ... other styles ... */
  }

.skill-card img {
    width: 50px;
    height: 50px;
    margin-bottom: 10px;
}

.skill-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.project-card {
    background: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.project-card:hover {
    transform: translateY(-10px);
}

.footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
}
    
  </style>
</head>
<body>
    <header class="hero">
        <div class="hero-content">
            <img src="Mypic.png" alt="Dignesh Solanki" class="profile-picture">
            <h1>Dignesh Solanki</h1>
            <p>Software Engineering student | Problem Solver | Innovator</p>
            <section id="about" class="section about">
             <p>I am Dignesh Solanki, a Computer Science student specializing in Software Engineering with a passion for creating innovative solutions to complex problems.</p>
            </section>
            <nav class="hero-nav">
                
                <a href="#skills">Skills</a>
                <a href="#education">Education</a>
                <a href="#experience">Experience</a>
                <a href="#projects">Projects</a>
                <a href="#interests">Interests</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <main>
     

        <section id="skills" class="section skills">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/C_Programming_Language.svg" alt="C Language">
                    <p>C</p>
                </div>
                <div class="skill-card">
                    <img src="https://upload.wikimedia.org/wikipedia/en/3/30/Java_programming_language_logo.svg" alt="Java">
                    <p>Java</p>
                </div>
                <div class="skill-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="Python">
                    <p>Python</p>
                </div>
                <div class="skill-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="JavaScript">
                    <p>JavaScript</p>
                </div>
                <div class="skill-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML & CSS">
                    <p>HTML</p>
                </div>
                <div class="skill-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" alt="HTML ">
                    <p>CSS</p>
                </div>
                <div class="skill-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Git-logo.svg" alt="CSS3_logo_and_wordmark">
                    <p>Git</p>
                </div>
                <div class="skill-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Mysql.svg" alt="MySQL">
                    <p>MySQL</p>
                </div>
            </div>
        </section>

        <section id="education" class="section education">
            <h2>Education</h2>
            <div class="education-item">
                <h3>BSc Honours Computer Science</h3>
                <p>University of Windsor, Jan 2024 - Dec 2027</p>
                <p>Relevant Courses: Algorithms, Object-Oriented Programming, Data Structures, Computer Architecture</p>
            </div>
            <div class="education-item">
                <h3>Diploma in Computer Systems Technician</h3>
                <p>Loyalist College, Sep 2019 - Apr 2021</p>
                <p>Relevant Courses: Database Management, Networking, Python Programming</p>
            </div>
        </section>

        <section id="experience" class="section experience">
            <h2>Experience</h2>
            <div class="experience-item">
                <h3>Production Team Leader</h3>
                <p>Aptyx (Globalmed Inc.), Apr 2021 - Jan 2024</p>
                <ul>
                    Led production team, optimizing workflows and enhancing efficiency.
                    Implemented lean manufacturing principles, resulting in cost savings and improved quality.
                    Developed and implemented quality control measures, reducing defects.
                </ul>
            </div>
        </section>

        <section id="projects" class="section projects">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Command Line Chess Game</h3>
                    <p>Implemented chess rules with C.</p>
                </div>
                <div class="project-card">
                    <h3>Tic Tac Toe</h3>
                    <p>Developed a graphical game using Java Swing, Single and multiplayer modes.</p>
                </div>
            </div>
        </section>

        <section id="interests" class="section interests">
            <h2>Interests</h2>
            <p>I have a deep passion for photography. Capturing moments and creating stunning visuals has always been a creative outlet for me.</p>
        </section>

        <section id="contact" class="section contact">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:solank86@uwindsor.ca">solank86@uwindsor.ca</a></p>
            <p>GitHub: <a href="https://github.com/dignesh1207" target="_blank">github.com/dignesh1207</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/dsolanki127" target="_blank">linkedin.com/in/dsolanki127</a></p>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2024 Dignesh Solanki. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>

```
