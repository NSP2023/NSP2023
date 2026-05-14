<!-- 🌊 CYAN HERO BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,100:00CFFF&height=260&section=header&text=Noshin%20Syara%20Promitee&fontSize=42&fontColor=000000&animation=fadeIn&fontAlignY=38"/>
</p>

<!-- 👾 TYPING INTRO -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=24&duration=3000&color=00F7FF&center=true&vCenter=true&width=750&lines=Frontend+Developer;AI+%2B+Hardware+Explorer;Robotics+%26+Systems+Enthusiast;Persistent+Learner"/>
</p>

---

# 💫 About Me

> 🎓 3rd Year Computer Science & Engineering Student  
> ⚙️ Passionate about scalable applications and real-world systems  
> 🤖 Strong interest in AI, robotics, embedded systems, and system design  
> 🎮 Experienced in web development, game development, and software engineering  
> 🚀 Always exploring new technologies, architectures, and innovative ideas  

---

# ⚡ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,python,java,js,react,django,unreal,mysql,git,latex,vscode,blender" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaFX-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
</p>

---

# 📊 GitHub Analytics

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=NoshinSyaraPromitee&show_icons=true&theme=tokyonight&hide_border=true&title_color=00F7FF&icon_color=00F7FF&bg_color=0D1117"/>

  <img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=NoshinSyaraPromitee&theme=tokyonight&hide_border=true&ring=00F7FF&fire=00F7FF&currStreakLabel=00F7FF"/>
</p>

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NoshinSyaraPromitee&layout=compact&theme=tokyonight&hide_border=true&title_color=00F7FF"/>
</p>

---

# 📈 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=NoshinSyaraPromitee&theme=tokyo-night&hide_border=true&area=true&color=00F7FF&line=00F7FF&point=FFFFFF"/>
</p>

---

# 🐍 Activity Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/NoshinSyaraPromitee/NoshinSyaraPromitee/output/github-contribution-grid-snake-dark.svg" alt="Snake animation"/>
</p>

<details>
<summary>⚡ Snake Setup (One Time)</summary>

Create this file:

`.github/workflows/snake.yml`

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    permissions:
      contents: write

    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: NoshinSyaraPromitee
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            dist/github-contribution-grid-snake.svg?palette=github-light

      - name: Push Snake Animation
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
