<!-- GitHub Profile README for Ndumiso Ngobese -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ndumiso Ngobese | Full-Stack Architect</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <style>
        :root {
            --primary-blue: #2A5C82;
            --accent-red: #FF6B6B;
            --dark-bg: #1A1A1A;
            --light-bg: #F9F9F9;
        }

        .architecture-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }

        .tech-radar {
            width: 400px;
            height: 400px;
            position: relative;
            margin: 2rem auto;
        }

        .radar-skill {
            position: absolute;
            transform: translate(-50%, -50%);
            padding: 0.5rem;
            border-radius: 4px;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: translate(-50%, -50%) scale(1); }
            50% { transform: translate(-50%, -50%) scale(1.05); }
            100% { transform: translate(-50%, -50%) scale(1); }
        }
    </style>
</head>
<body>

    <!-- Value Proposition Section -->
    <section class="value-proposition">
        <h2>Technical Philosophy in Practice</h2>
        
        <div class="architecture-grid">
            <div class="layer frontend">
                <h3>🖌️ Frontend Craftsmanship</h3>
                <div class="skill-metric">
                    <div class="metric-bar" style="width: 92%">92% Accessibility Score</div>
                    <div class="metric-bar" style="width: 88%">88% Performance</div>
                </div>
                <ul>
                    <li>React Hooks & Context API</li>
                    <li>Figma-to-Code Conversion</li>
                    <li>Jest Testing Library</li>
                </ul>
            </div>

            <div class="layer devops">
                <h3>⚙️ DevOps Automation</h3>
                <div class="skill-metric">
                    <div class="metric-bar" style="width: 95%">95% Pipeline Success</div>
                    <div class="metric-bar" style="width: 85%">85% Test Coverage</div>
                </div>
                <ul>
                    <li>GitLab CI/CD Pipelines</li>
                    <li>Docker Swarm Orchestration</li>
                    <li>SonarQube Integration</li>
                </ul>
            </div>

            <div class="layer backend">
                <h3>🔧 Backend Engineering</h3>
                <div class="skill-metric">
                    <div class="metric-bar" style="width: 90%">90% Uptime</div>
                    <div class="metric-bar" style="width: 80%">80% Query Opt.</div>
                </div>
                <ul>
                    <li>Spring Boot Microservices</li>
                    <li>PostgreSQL Optimization</li>
                    <li>Redis Caching</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Technical Radar -->
    <section class="tech-radar-section">
        <h2>Technology Radar 2024</h2>
        <div class="tech-radar">
            <div class="radar-skill" style="top: 30%; left: 50%; background: var(--primary-blue);">
                React 18
            </div>
            <div class="radar-skill" style="top: 45%; left: 65%; background: var(--accent-red);">
                Python 3.11
            </div>
            <div class="radar-skill" style="top: 60%; left: 35%; background: var(--primary-blue);">
                Docker Swarm
            </div>
        </div>
        <div class="radar-legend">
            <span style="color: var(--primary-blue)">▶ Adopting</span>
            <span style="color: var(--accent-red)">▶ Exploring</span>
        </div>
    </section>

    <!-- Project Case Studies -->
    <section class="project-case-study">
        <article class="case-study">
            <header class="study-header">
                <h3>Robot Worlds API Case Study</h3>
                <div class="study-metrics">
                    <div class="metric">
                        <span class="material-symbols-outlined">speed</span>
                        40% Faster Response
                    </div>
                    <div class="metric">
                        <span class="material-symbols-outlined">bug_report</span>
                        95% Test Coverage
                    </div>
                </div>
            </header>
            
            <div class="study-content">
                <div class="architecture-diagram">
                    <!-- Add your system diagram here -->
                </div>
                
                <div class="challenge-solution">
                    <div class="challenge">
                        <h4>Challenge</h4>
                        <p>Legacy codebase with tight coupling between business logic and API layer</p>
                    </div>
                    <div class="solution">
                        <h4>Solution</h4>
                        <ul>
                            <li>Implemented Clean Architecture</li>
                            <li>Added JUnit 5 Integration Tests</li>
                            <li>Introduced CQRS Pattern</li>
                        </ul>
                    </div>
                </div>
                
                <blockquote class="testimonial">
                    "Ndumiso's refactoring reduced our bug reports by 60% post-deployment"
                    <cite>- Team Lead, Robot Worlds</cite>
                </blockquote>
            </div>
        </article>
    </section>

    <!-- Interactive Coding Demo -->
    <section class="live-code">
        <h2>Component Sandbox</h2>
        <div class="code-playground">
            <div class="editor">
                <div class="editor-tabs">
                    <button class="active">RobotController.java</button>
                    <button>WorldService.py</button>
                </div>
                <pre class="code-content"><code class="language-java">
@RestController
public class RobotController {
    @Autowired
    private CommandService commandService;
    
    @PostMapping("/commands")
    public ResponseEntity<?> executeCommand(
        @RequestBody CommandRequest request
    ) {
        CommandResult result = commandService.execute(request);
        return ResponseEntity.ok(result);
    }
}
                </code></pre>
            </div>
            <div class="api-output">
                <h4>API Response Preview</h4>
                <pre>{
  "status": "EXECUTED",
  "result": "MOVED 5 UNITS",
  "worldState": "UPDATED"
}</pre>
            </div>
        </div>
    </section>

</body>
</html>






<!-- GitHub Profile README for Ndumiso Ngobese -->

<h1 align="center">Hi 👋, I'm Ndumiso Ngobese</h1>
<h3 align="center">Full-Stack Developer | Meta Certified | WeThinkCode_ Graduate</h3>

<p align="center">
  <a href="https://portfolio-web-page-three.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/ndumisongobese/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:ndumisongobeseng@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
</p>

---

### 🧑‍💻 About Me

I'm a full-stack developer passionate about crafting seamless digital experiences. With certifications in both Front-End and Back-End Development through Meta and Coursera, and a graduate of WeThinkCode_, I specialize in:

- **Front-End Development**: Building responsive UIs with React, JavaScript, and modern CSS frameworks.
- **Back-End Development**: Developing scalable server-side solutions using Python and Java.
- **DevOps & Automation**: Implementing CI/CD pipelines with Docker and GitLab.
- **Problem Solving & Quality**: Tackling complex challenges with a test-driven development approach.

---

### 🎓 Certifications

![Meta Front-End Developer](https://img.shields.io/badge/Meta-Front--End_Developer-blue?logo=meta&logoColor=white)
![Meta Back-End Developer](https://img.shields.io/badge/Meta-Back--End_Developer-blue?logo=meta&logoColor=white)
![IBM Agile & Scrum](https://img.shields.io/badge/IBM-Agile_&_Scrum-orange?logo=ibm&logoColor=white)
![WeThinkCode_ Graduate](https://img.shields.io/badge/WeThinkCode_-Graduate-6C33FF?logo=python&logoColor=white)


### 🛠️ Tech Stack

#### Languages

<p align="left">
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

#### Frameworks & Libraries

<p align="left">
  <img src="https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Javalin-%23000000.svg?style=for-the-badge&logo=java&logoColor=white" alt="Javalin" />
</p>

#### Tools & Platforms

<p align="left">
  <img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/VSCode-%23007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode" />
</p>

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ndumisodev&show_icons=true&theme=radical" alt="Ndumiso's GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ndumisodev&layout=compact&theme=radical" alt="Top Languages" />
</p>

---

### 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ndumisodev&theme=radical" alt="GitHub Trophies" />
</p>

---

### 🔥 GitHub Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ndumisodev&theme=radical" alt="GitHub Activity Graph" />
</p>

---

### 🚀 Projects

- **Robot Worlds API**: A complex robot simulation engine with persistent worlds, combat mechanics, and database integration.
  - Technologies: Java, Javalin, MySQL, Docker, CI/CD
  - [Repository](https://github.com/ndumisodev/robot-worlds-api)

- **Little Lemon Restaurant**: Full-stack restaurant management system with booking and menu features.
  - Technologies: React, JavaScript, CSS3
  - [Repository](https://github.com/ndumisodev/little-lemon-restaurant)

- **Mangata & Gallo Jewelry**: Luxury jewelry e-commerce site with responsive design.
  - Technologies: HTML5, CSS3, JavaScript
  - [Repository](https://github.com/ndumisodev/mangata-gallo)

- **Plotta Web App**: Interactive 2D/3D function grapher for mathematical visualization.
  - Technologies: Python, JavaScript, Plotly, WebGL
  - [
