<p align="center">
    <img align="center" src="img.jpg" />
</p>

# <h1 align="center">Hi 👋, I'm JAYMEEN VAGHELA</h1>
### 
<p align="center"> 
    <h3 align="center">An aspiring full stack developer and computer engineering student<br><br>
    Behind every great product is a backend that keeps pushing upward.</h3>
</p>

---
### Current Focus :

- 🔭 I’m currently working on **[TRINETRA](https://github.com/jaymeen07-r/TRINETRA)**  
- 🌱 I’m currently learning **Node.js**  
- 📫 How to reach me **jaymeenvaghela07@gmail.com**


---
### About Me :

I'm currently pursuing my Bachelor of Engineering in Computer Engineering, with a strong focus on backend development and AI-driven system design. My academic journey is rooted in the legacy of Vidush Somany Institute of Technology and Research, a constituent of Kadi Sarva Vishwavidyalaya Gandhinagar, which carries over a century of philanthropic excellence in education. This heritage inspires my commitment to innovation, empathy, and purpose-driven computing. Alongside my academics, I am the Founder of TRINETRA which is an AI-driven misinformation detection Android application designed to help users identify fake, misleading, or manipulated content across digital platforms. Built with a vision to ensure digital safety, authenticity, and trust, TRINETRA empowers people to make informed decisions in an era where misinformation spreads faster than truth. 


---
### Languages and Tools:

<p align="center">
    <a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
    <a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>
    <a href="https://www.php.net" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/></a>
    <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/></a>
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/></a>
    <a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/></a>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/></a>
    <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/>            </a>
    <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/></a>
</p>
<p align="center">
    <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
    <a href="https://flutter.dev" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/></a>
    <a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>
    <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/></a>
    <a href="https://www.linux.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/></a>
</p>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Jaymeen Vaghela | Skill Graph</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Chart.js CDN -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

  <style>
    body {
      margin: 0;
      background: #0d1117;
      color: #c9d1d9;
      font-family: "Segoe UI", system-ui, sans-serif;
    }

    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 20px;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
      font-weight: 600;
    }

    canvas {
      background: #161b22;
      border-radius: 12px;
      padding: 20px;
    }

    .legend {
      text-align: center;
      margin-top: 20px;
      font-size: 14px;
      opacity: 0.9;
    }

    .legend span {
      margin: 0 12px;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>🚀 Skills Proficiency Overview</h2>
    <canvas id="skillsChart"></canvas>

    <div class="legend">
      <span>🟢 Advanced (80–100)</span>
      <span>🟡 Intermediate (50–79)</span>
      <span>🔴 Beginner (0–49)</span>
    </div>
  </div>

  <script>
    const ctx = document.getElementById("skillsChart");

    new Chart(ctx, {
      type: "bar",
      data: {
        labels: [
          "Python",
          "Node.js",
          "PHP",
          "HTML",
          "CSS",
          "JavaScript",
          "MongoDB",
          "AWS",
          "Firebase",
          "Docker",
          "Flutter",
          "Git",
          "C",
          "Linux",
          "Figma"
        ],
        datasets: [{
          label: "Skill Level",
          data: [
            85,  // Python
            75,  // Node.js
            65,  // PHP
            90,  // HTML
            85,  // CSS
            80,  // JavaScript
            70,  // MongoDB
            60,  // AWS
            65,  // Firebase
            55,  // Docker
            50,  // Flutter
            80,  // Git
            60,  // C
            70,  // Linux
            75   // Figma
          ],
          backgroundColor: function(context) {
            const value = context.raw;
            if (value >= 80) return "#2ea043";     // Advanced
            if (value >= 50) return "#f1c40f";     // Intermediate
            return "#e74c3c";                      // Beginner
          },
          borderRadius: 6
        }]
      },
      options: {
        responsive: true,
        plugins: {
          legend: { display: false },
          tooltip: {
            callbacks: {
              label: function(ctx) {
                const v = ctx.raw;
                if (v >= 80) return "Advanced";
                if (v >= 50) return "Intermediate";
                return "Beginner";
              }
            }
          }
        },
        scales: {
          y: {
            beginAtZero: true,
            max: 100,
            ticks: {
              color: "#c9d1d9"
            },
            grid: {
              color: "#30363d"
            }
          },
          x: {
            ticks: {
              color: "#c9d1d9"
            },
            grid: {
              display: false
            }
          }
        }
      }
    });
  </script>

</body>
</html>



---
###  Notable Projects :

- **TRINETRA** – INDIA'S First AI Tool for Combate Misinformation.
- **V.A.S.U.** – Virtual Assitant with next level OS integration.
- **P.A.R.T.I.C.L.E.** – Virtual Assitant with next level OS integration.  

- **College Hackathon Projects**<br>
      – **Gen AI Exchange Hackathon 2025** – AI-Based Tool for Combate Misinformation.<br>
      – **SIH Hackathon 2025** – TrueHealth Network - A Digital Bridge Across the Entire Healthcare System.<br>
      – **ImpactThon 2025** – Programmable Atomic Radial Task Interface & Command Logic Engine.


---
### Connect with me :

  <p align="center" style="margin-bottom: 50px;">

  <a href="https://instagram.com/jaymeen_vaghela_264" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-ff0000?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>

  <a href="https://www.linkedin.com/in/jaymeen-vaghela" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

  <a href="mailto:jaymeenvaghela07@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>

  <a href="https://github.com/jaymeen07-r" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" />
  </a>

</p>


---
