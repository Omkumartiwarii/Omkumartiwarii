<div align="center">

<!-- SVG Banner - No upload needed! -->
<svg width="100%" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0f1c3f;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#1a2f5e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0d1b3e;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#4f8ef7;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#00c6ff;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="400" fill="url(#bg)" rx="12"/>

  <!-- Circuit lines left -->
  <g stroke="#4f8ef7" stroke-width="1" opacity="0.3">
    <line x1="0" y1="80" x2="120" y2="80"/><circle cx="120" cy="80" r="3" fill="#4f8ef7"/>
    <line x1="120" y1="80" x2="120" y2="140"/><circle cx="120" cy="140" r="3" fill="#4f8ef7"/>
    <line x1="120" y1="140" x2="60" y2="140"/>
    <line x1="40" y1="200" x2="160" y2="200"/><circle cx="160" cy="200" r="3" fill="#4f8ef7"/>
    <line x1="160" y1="200" x2="160" y2="260"/><circle cx="160" cy="260" r="3" fill="#4f8ef7"/>
    <line x1="160" y1="260" x2="80" y2="260"/>
    <line x1="0" y1="320" x2="100" y2="320"/><circle cx="100" cy="320" r="3" fill="#4f8ef7"/>
    <line x1="100" y1="320" x2="100" y2="360"/>
  </g>

  <!-- Circuit lines right -->
  <g stroke="#4f8ef7" stroke-width="1" opacity="0.3">
    <line x1="1200" y1="80" x2="1080" y2="80"/><circle cx="1080" cy="80" r="3" fill="#4f8ef7"/>
    <line x1="1080" y1="80" x2="1080" y2="140"/><circle cx="1080" cy="140" r="3" fill="#4f8ef7"/>
    <line x1="1080" y1="140" x2="1140" y2="140"/>
    <line x1="1160" y1="200" x2="1040" y2="200"/><circle cx="1040" cy="200" r="3" fill="#4f8ef7"/>
    <line x1="1040" y1="200" x2="1040" y2="260"/><circle cx="1040" cy="260" r="3" fill="#4f8ef7"/>
    <line x1="1040" y1="260" x2="1120" y2="260"/>
    <line x1="1200" y1="320" x2="1100" y2="320"/><circle cx="1100" cy="320" r="3" fill="#4f8ef7"/>
  </g>

  <!-- Dot grid left -->
  <g fill="#4f8ef7" opacity="0.25">
    <circle cx="200" cy="60" r="2"/><circle cx="220" cy="60" r="2"/><circle cx="240" cy="60" r="2"/>
    <circle cx="200" cy="80" r="2"/><circle cx="220" cy="80" r="2"/><circle cx="240" cy="80" r="2"/>
    <circle cx="200" cy="100" r="2"/><circle cx="220" cy="100" r="2"/><circle cx="240" cy="100" r="2"/>
    <circle cx="200" cy="120" r="2"/><circle cx="220" cy="120" r="2"/><circle cx="240" cy="120" r="2"/>
  </g>

  <!-- Dot grid right -->
  <g fill="#4f8ef7" opacity="0.25">
    <circle cx="960" cy="280" r="2"/><circle cx="980" cy="280" r="2"/><circle cx="1000" cy="280" r="2"/>
    <circle cx="960" cy="300" r="2"/><circle cx="980" cy="300" r="2"/><circle cx="1000" cy="300" r="2"/>
    <circle cx="960" cy="320" r="2"/><circle cx="980" cy="320" r="2"/><circle cx="1000" cy="320" r="2"/>
  </g>

  <!-- Triangle decorations -->
  <polygon points="180,300 210,260 240,300" fill="#4f8ef7" opacity="0.15"/>
  <polygon points="950,80 975,45 1000,80" fill="#4f8ef7" opacity="0.15"/>
  <polygon points="130,340 150,315 170,340" fill="#4f8ef7" opacity="0.1"/>

  <!-- Bar chart right side -->
  <g opacity="0.15" fill="#4f8ef7">
    <rect x="1000" y="280" width="18" height="80" rx="2"/>
    <rect x="1025" y="240" width="18" height="120" rx="2"/>
    <rect x="1050" y="260" width="18" height="100" rx="2"/>
    <rect x="1075" y="200" width="18" height="160" rx="2"/>
    <rect x="1100" y="230" width="18" height="130" rx="2"/>
  </g>
  <!-- Chart line -->
  <polyline points="1009,280 1034,240 1059,255 1084,198 1109,228" stroke="#00c6ff" stroke-width="2" fill="none" opacity="0.3"/>

  <!-- Code tag top center -->
  <text x="600" y="75" font-family="Courier New, monospace" font-size="22" fill="url(#accent)" text-anchor="middle" filter="url(#glow)" opacity="0.9">&lt;/&gt;</text>
  <!-- Horizontal lines beside code tag -->
  <line x1="430" y1="65" x2="545" y2="65" stroke="url(#accent)" stroke-width="1.5" opacity="0.5"/>
  <line x1="655" y1="65" x2="770" y2="65" stroke="url(#accent)" stroke-width="1.5" opacity="0.5"/>

  <!-- Main Name -->
  <text x="600" y="175" font-family="Arial Black, sans-serif" font-size="88" font-weight="900" fill="#0f1c3f" text-anchor="middle" opacity="0.15">Om Kumar</text>
  <text x="600" y="172" font-family="Arial Black, sans-serif" font-size="88" font-weight="900" fill="#e8f0ff" text-anchor="middle">Om Kumar</text>

  <!-- Divider line -->
  <line x1="300" y1="190" x2="900" y2="190" stroke="url(#accent)" stroke-width="1" opacity="0.4"/>

  <!-- Role icons row -->
  <!-- Python icon circle -->
  <circle cx="350" cy="240" r="22" fill="#3776AB" opacity="0.9"/>
  <text x="350" y="246" font-family="Arial" font-size="20" fill="white" text-anchor="middle">🐍</text>
  <text x="390" y="237" font-family="Arial, sans-serif" font-size="18" fill="#c8d8f0" font-weight="600">Python Developer</text>

  <!-- Divider -->
  <line x1="560" y1="220" x2="560" y2="260" stroke="#4f8ef7" stroke-width="1" opacity="0.4"/>

  <!-- Support icon -->
  <circle cx="590" cy="240" r="22" fill="#1a3a6e" opacity="0.9"/>
  <text x="590" y="246" font-family="Arial" font-size="20" fill="white" text-anchor="middle">🎧</text>
  <text x="630" y="233" font-family="Arial, sans-serif" font-size="18" fill="#c8d8f0" font-weight="600">Technical Support</text>
  <text x="630" y="253" font-family="Arial, sans-serif" font-size="18" fill="#c8d8f0" font-weight="600">Engineer</text>

  <!-- Divider -->
  <line x1="810" y1="220" x2="810" y2="260" stroke="#4f8ef7" stroke-width="1" opacity="0.4"/>

  <!-- Analytics icon -->
  <circle cx="840" cy="240" r="22" fill="#1a3a6e" opacity="0.9"/>
  <text x="840" y="246" font-family="Arial" font-size="20" fill="white" text-anchor="middle">📊</text>
  <text x="880" y="246" font-family="Arial, sans-serif" font-size="18" fill="#4f8ef7" font-weight="700">Data Analytics</text>

  <!-- Open to Work button -->
  <rect x="450" y="295" width="300" height="46" rx="23" fill="#0f1c3f" stroke="#4f8ef7" stroke-width="1.5"/>
  <circle cx="480" cy="318" r="7" fill="#00C853"/>
  <text x="600" y="324" font-family="Arial Black, sans-serif" font-size="16" fill="white" text-anchor="middle" font-weight="900" letter-spacing="2">OPEN TO WORK</text>

  <!-- Bottom tagline -->
  <text x="600" y="372" font-family="Courier New, monospace" font-size="15" fill="#7a9fd4" text-anchor="middle">Turning <tspan fill="#4f8ef7" font-weight="bold">Code</tspan> into Solutions. Transforming <tspan fill="#4f8ef7" font-weight="bold">Data</tspan> into Insights.</text>
</svg>

<br/><br/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Technical+Support+Engineer;Python+%2B+Django+Developer;Data+Analytics+Enthusiast;Backend+Builder+%F0%9F%94%A7;Open+to+Work+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Om_Kumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omkumar00116)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Now-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://omkumartiwarii.github.io/portfoliowebsite/)
[![Email](https://img.shields.io/badge/Gmail-omkumar00116@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omkumar00116@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/Omkumartiwarii?style=for-the-badge&logo=github&color=181717)](https://github.com/Omkumartiwarii?tab=followers)

</div>

---

## 🧑‍💻 About Me

```python
class OmKumar:
    def __init__(self):
        self.name       = "Om Kumar"
        self.role       = "Python Developer | Technical Support | Data Analyst"
        self.college    = "Govt. Engineering College Sheohar (2022–2026)"
        self.location   = "Bihar, India 🇮🇳 | Open to Relocation"
        self.email      = "omkumar00116@gmail.com"
        self.status     = "🟢 Open to Work"

    def skills(self):
        return {
            "Languages"  : ["Python", "SQL", "C"],
            "Frameworks" : ["Django", "Django REST Framework"],
            "Databases"  : ["PostgreSQL", "MySQL"],
            "Data"       : ["Pandas", "NumPy", "EDA", "Data Visualization"],
            "Tools"      : ["Git", "GitHub", "REST APIs", "Salesforce CRM"],
            "Interests"  : ["Backend Dev", "Automation", "Technical Support"]
        }

    def currently(self):
        return "Building projects, learning everyday, open to opportunities 🚀"

me = OmKumar()
print(me.currently())
```

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-ff1709?style=for-the-badge&logo=django&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 🚀 Featured Project

### 🗓️ Clash-Free Timetable Management System
> Automates timetable generation & eliminates scheduling conflicts

- ⚙️ **Tech:** Django + PostgreSQL + Django REST Framework
- ✅ Fully automated — no manual conflict resolution needed
- 🔗 Backend architecture with clean REST APIs
- 📊 Handles complex constraints like faculty availability & room allocation

---

## 💼 Experience Highlights

| 🏢 Organization | 💼 Role | 📅 Duration |
|---|---|---|
| **GRIP Program** | Data Science & Business Analytics | Nov–Dec 2025 |
| **Cisco** | Data Science Virtual Intern | Sep–Oct 2024 |
| **Spoken Tutorial (IIT Bombay)** | Python Developer Intern | Sep–Oct 2024 |
| **Salesforce** | Virtual Intern | Dec 2023–Jan 2024 |

> 🏆 Built predictive models with **~85% accuracy** | Reduced preprocessing time by **50%** | Automated workflows cutting manual effort by **40%**

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Omkumartiwarii&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Omkumartiwarii&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Omkumartiwarii&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🏅 Certifications

- 🥇 **Salesforce Developer** — Virtual Internship Certificate
- 🥇 **NPTEL** — Problem Solving through Programming in C
- 🥇 **Spoken Tutorial (IIT Bombay)** — Python & Data Science
- 🥇 **Cisco** — Data Science Virtual Internship

---

## 📈 Contribution Graph

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Omkumartiwarii&theme=tokyo-night&hide_border=true&area=true" width="100%"/>
</div>

---

<div align="center">

### 💬 Let's Connect!

*"I enjoy solving real-world problems through technology — whether building backends, automating workflows, or analyzing data."*

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/omkumar00116)
[![Portfolio](https://img.shields.io/badge/-Portfolio-FF5722?style=flat-square&logo=firefox)](https://omkumartiwarii.github.io/portfoliowebsite/)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail)](mailto:omkumar00116@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
