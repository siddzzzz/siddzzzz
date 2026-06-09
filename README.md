<div align="center">

<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#1f6feb" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#0d1117" stop-opacity="0"/>
    </radialGradient>
    <filter id="blur-glow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="text-glow" x="-20%" y="-60%" width="140%" height="220%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <linearGradient id="name-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#388bfd"/>
      <stop offset="45%" stop-color="#a5d6ff"/>
      <stop offset="100%" stop-color="#388bfd"/>
    </linearGradient>
    <linearGradient id="line-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="30%" stop-color="#1f6feb"/>
      <stop offset="70%" stop-color="#1f6feb"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
  </defs>

  <rect width="800" height="200" fill="#0d1117"/>

  <!-- dot grid -->
  <g opacity="0.18">
    <circle cx="60" cy="30" r="1.2" fill="#58a6ff"/><circle cx="120" cy="30" r="1.2" fill="#58a6ff"/><circle cx="180" cy="30" r="1.2" fill="#58a6ff"/><circle cx="240" cy="30" r="1.2" fill="#58a6ff"/><circle cx="300" cy="30" r="1.2" fill="#58a6ff"/><circle cx="360" cy="30" r="1.2" fill="#58a6ff"/><circle cx="420" cy="30" r="1.2" fill="#58a6ff"/><circle cx="480" cy="30" r="1.2" fill="#58a6ff"/><circle cx="540" cy="30" r="1.2" fill="#58a6ff"/><circle cx="600" cy="30" r="1.2" fill="#58a6ff"/><circle cx="660" cy="30" r="1.2" fill="#58a6ff"/><circle cx="720" cy="30" r="1.2" fill="#58a6ff"/>
    <circle cx="60" cy="70" r="1.2" fill="#58a6ff"/><circle cx="120" cy="70" r="1.2" fill="#58a6ff"/><circle cx="180" cy="70" r="1.2" fill="#58a6ff"/><circle cx="240" cy="70" r="1.2" fill="#58a6ff"/><circle cx="300" cy="70" r="1.2" fill="#58a6ff"/><circle cx="360" cy="70" r="1.2" fill="#58a6ff"/><circle cx="420" cy="70" r="1.2" fill="#58a6ff"/><circle cx="480" cy="70" r="1.2" fill="#58a6ff"/><circle cx="540" cy="70" r="1.2" fill="#58a6ff"/><circle cx="600" cy="70" r="1.2" fill="#58a6ff"/><circle cx="660" cy="70" r="1.2" fill="#58a6ff"/><circle cx="720" cy="70" r="1.2" fill="#58a6ff"/>
    <circle cx="60" cy="110" r="1.2" fill="#58a6ff"/><circle cx="120" cy="110" r="1.2" fill="#58a6ff"/><circle cx="180" cy="110" r="1.2" fill="#58a6ff"/><circle cx="240" cy="110" r="1.2" fill="#58a6ff"/><circle cx="300" cy="110" r="1.2" fill="#58a6ff"/><circle cx="360" cy="110" r="1.2" fill="#58a6ff"/><circle cx="420" cy="110" r="1.2" fill="#58a6ff"/><circle cx="480" cy="110" r="1.2" fill="#58a6ff"/><circle cx="540" cy="110" r="1.2" fill="#58a6ff"/><circle cx="600" cy="110" r="1.2" fill="#58a6ff"/><circle cx="660" cy="110" r="1.2" fill="#58a6ff"/><circle cx="720" cy="110" r="1.2" fill="#58a6ff"/>
    <circle cx="60" cy="150" r="1.2" fill="#58a6ff"/><circle cx="120" cy="150" r="1.2" fill="#58a6ff"/><circle cx="180" cy="150" r="1.2" fill="#58a6ff"/><circle cx="240" cy="150" r="1.2" fill="#58a6ff"/><circle cx="300" cy="150" r="1.2" fill="#58a6ff"/><circle cx="360" cy="150" r="1.2" fill="#58a6ff"/><circle cx="420" cy="150" r="1.2" fill="#58a6ff"/><circle cx="480" cy="150" r="1.2" fill="#58a6ff"/><circle cx="540" cy="150" r="1.2" fill="#58a6ff"/><circle cx="600" cy="150" r="1.2" fill="#58a6ff"/><circle cx="660" cy="150" r="1.2" fill="#58a6ff"/><circle cx="720" cy="150" r="1.2" fill="#58a6ff"/>
    <circle cx="60" cy="185" r="1.2" fill="#58a6ff"/><circle cx="120" cy="185" r="1.2" fill="#58a6ff"/><circle cx="180" cy="185" r="1.2" fill="#58a6ff"/><circle cx="240" cy="185" r="1.2" fill="#58a6ff"/><circle cx="300" cy="185" r="1.2" fill="#58a6ff"/><circle cx="360" cy="185" r="1.2" fill="#58a6ff"/><circle cx="420" cy="185" r="1.2" fill="#58a6ff"/><circle cx="480" cy="185" r="1.2" fill="#58a6ff"/><circle cx="540" cy="185" r="1.2" fill="#58a6ff"/><circle cx="600" cy="185" r="1.2" fill="#58a6ff"/><circle cx="660" cy="185" r="1.2" fill="#58a6ff"/><circle cx="720" cy="185" r="1.2" fill="#58a6ff"/>
  </g>

  <!-- centre glow bloom -->
  <ellipse cx="400" cy="105" rx="300" ry="90" fill="url(#glow)"/>

  <!-- corner accent lines -->
  <line x1="30" y1="18" x2="100" y2="18" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>
  <line x1="30" y1="18" x2="30" y2="70" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>
  <line x1="770" y1="18" x2="700" y2="18" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>
  <line x1="770" y1="18" x2="770" y2="70" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>
  <line x1="30" y1="182" x2="100" y2="182" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>
  <line x1="30" y1="182" x2="30" y2="130" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>
  <line x1="770" y1="182" x2="700" y2="182" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>
  <line x1="770" y1="182" x2="770" y2="130" stroke="#1f6feb" stroke-width="1" opacity="0.6"/>

  <!-- glow copy of name (bloom layer) -->
  <text x="400" y="115" text-anchor="middle"
    font-family="'Trebuchet MS', 'Segoe UI', Georgia, sans-serif"
    font-size="54" font-weight="700" letter-spacing="3"
    fill="#388bfd" opacity="0.25" filter="url(#blur-glow)">Siddharth Sahay</text>

  <!-- main name with gradient -->
  <text x="400" y="115" text-anchor="middle"
    font-family="'Trebuchet MS', 'Segoe UI', Georgia, sans-serif"
    font-size="54" font-weight="700" letter-spacing="3"
    fill="url(#name-grad)" filter="url(#text-glow)">Siddharth Sahay</text>

  <!-- decorative underline -->
  <rect x="200" y="128" width="400" height="1.5" fill="url(#line-grad)" rx="1"/>
  <rect x="320" y="133" width="160" height="0.8" fill="url(#line-grad)" rx="1" opacity="0.5"/>
</svg>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+intelligent+systems+%F0%9F%A4%96;Taming+TensorFlow+%26+OpenCV+every+day+%F0%9F%94%A5;Gamer+by+night%2C+AI+researcher+by+day+%F0%9F%8E%AE;Always+shipping+something+new+%F0%9F%9A%80;I+debug+models+like+I+debug+boss+fights+%E2%9A%A1)](https://git.io/typing-svg)

</div>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=siddzzzz&label=Profile+Views&color=1f6feb&style=flat-square" />
&nbsp;
<img src="https://img.shields.io/github/followers/siddzzzz?label=Followers&style=flat-square&color=1f6feb" />
&nbsp;
<img src="https://img.shields.io/badge/Focus-AI%20%26%20ML-1f6feb?style=flat-square" />
&nbsp;
<img src="https://img.shields.io/badge/Location-India%20%F0%9F%87%AE%F0%9F%87%B3-1f6feb?style=flat-square" />

</div>

---

## 🧑‍💻 About Me

```python
class Siddharth:
    def __init__(self):
        self.name       = "Siddharth Sahay"
        self.alias      = "Sidd 🕹️"
        self.location   = "India 🇮🇳"
        self.fields     = ["Artificial Intelligence", "Machine Learning", "Computer Vision"]
        self.currently  = {
            "learning"  : ["TensorFlow 🔥", "OpenCV 👁️", "Deep Learning architectures"],
            "building"  : "Something cool... stay tuned 👀",
            "reading"   : "Research papers @ 2AM ☕"
        }
        self.ask_me_about = ["Python", "ML pipelines", "CV projects", "AI ideas"]
        self.fun_fact     = "I debug models like I debug boss fights — with patience and spite ⚡"

    def say_hi(self):
        print("Thanks for stopping by! Let's build something awesome 🚀")

me = Siddharth()
me.say_hi()
```

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=3776AB)
![C++](https://img.shields.io/badge/C++-0d1117?style=for-the-badge&logo=c%2B%2B&logoColor=00599C)
![C](https://img.shields.io/badge/C-0d1117?style=for-the-badge&logo=c&logoColor=00599C)
![Java](https://img.shields.io/badge/Java-0d1117?style=for-the-badge&logo=openjdk&logoColor=ED8B00)

**AI / ML**

![TensorFlow](https://img.shields.io/badge/TensorFlow-0d1117?style=for-the-badge&logo=tensorflow&logoColor=FF6F00)
![OpenCV](https://img.shields.io/badge/OpenCV-0d1117?style=for-the-badge&logo=opencv&logoColor=5C3EE8)
![NumPy](https://img.shields.io/badge/NumPy-0d1117?style=for-the-badge&logo=numpy&logoColor=013243)
![Pandas](https://img.shields.io/badge/Pandas-0d1117?style=for-the-badge&logo=pandas&logoColor=150458)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-0d1117?style=for-the-badge&logo=scikit-learn&logoColor=F7931E)
![Matplotlib](https://img.shields.io/badge/Matplotlib-0d1117?style=for-the-badge&logo=python&logoColor=11557c)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=F05032)
![VS Code](https://img.shields.io/badge/VS%20Code-0d1117?style=for-the-badge&logo=visual-studio-code&logoColor=007ACC)
![Jupyter](https://img.shields.io/badge/Jupyter-0d1117?style=for-the-badge&logo=jupyter&logoColor=F37626)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=FCC624)
![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=ffffff)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=siddzzzz&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=8b949e&border_color=30363d" height="175"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=siddzzzz&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&border_color=30363d&langs_count=6" height="175"/>

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=siddzzzz&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=1f6feb&ring=58a6ff&fire=ff7b72&currStreakNum=58a6ff&sideNums=8b949e&currStreakLabel=8b949e&sideLabels=8b949e&dates=8b949e" height="175"/>

</div>

---

## 🏆 Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=siddzzzz&theme=algolia&no-frame=true&no-bg=true&margin-w=6&column=7" />

</div>

---

## 🗺️ Active Quests

<div align="center">

| &nbsp; | Quest | Progress | Status |
|:---:|:---|:---:|:---:|
| 🧠 | Mastering **TensorFlow** deep learning | `████████░░` 80% | 🔵 Active |
| 👁️ | Exploring **Computer Vision** research | `██████░░░░` 60% | 🔵 Active |
| 🔧 | Building a secret side project | `███░░░░░░░` 35% | 🟠 Cooking |
| 📚 | Reading ML papers consistently | `███████░░░` 70% | 🔵 Active |
| ⚔️ | Defeating assignment deadlines | `██████████` ∞% | 🟣 Always |

</div>

---

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=siddzzzz&theme=github-compact&bg_color=0d1117&color=58a6ff&line=1f6feb&point=58a6ff&area=true&area_color=1f6feb&hide_border=true&custom_title=Contribution%20Graph" />

</div>

---

## 💬 Dev Quote

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&bg_color=0d1117&border_color=30363d" />

</div>

---

## 🤝 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=0077B5)](https://www.linkedin.com/in/siddharth-sahay-9a8365254)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=ffffff)](https://github.com/siddzzzz)

<br/><br/>

*"The best way to predict the future is to build it." — Alan Kay* 🚀

</div>

<svg width="100%" viewBox="0 0 800 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="fg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0f2039"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
  </defs>
  <rect width="800" height="100" fill="url(#fg)"/>
  <path d="M0,40 C100,10 200,60 300,35 C400,10 500,55 600,28 C700,5 750,40 800,22 L800,0 L0,0 Z" fill="#0a1628" opacity="0.8"/>
  <path d="M0,55 C120,28 220,65 340,45 C460,25 560,60 680,38 C740,27 770,50 800,40 L800,0 L0,0 Z" fill="#060d18" opacity="0.6"/>
</svg>
