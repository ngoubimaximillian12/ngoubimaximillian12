<!-- VSCode-style banner with animated gradient -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&text=Maximillian%20Diangha%20Ngoubi&fontAlign=50&fontAlignY=40&color=gradient&desc=AI%20%26%20ML%20Researcher%20%7C%20Full-Stack%20Dev%20%7C%20Data%20Scientist&descAlign=50&descAlignY=60" />
</p>

<h1 align="center">Hi there 👋, I'm Maximillian Diangha Ngoubi</h1>

<p align="center">
  <em>🧠 AI & ML Researcher | 💻 Full-Stack Developer | 📊 Data Scientist</em>
</p>

<p align="center">
  <a href="mailto:ngoubimaximillian12@gmail.com">
    <img src="https://img.shields.io/badge/Email-Drop%20a%20message-blue?style=for-the-badge&logo=gmail" />
  </a>
  <a href="https://www.linkedin.com/in/diangha-ngoubi-42a49b281/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://www.maximillian.pro/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-lightgrey?style=for-the-badge&logo=google-chrome" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=ngoubimaximillian12&style=for-the-badge&color=blue" alt="Visitor Count" />
</p>

---

## 🚀 About Me

- 🤖 Building intelligent agents & AI tools for real-world impact  
- 🧠 Passionate about AI for climate, health, sport & automation  
- 🌱 Exploring LLM integration, AutoML & scalable MLOps  
- 🌍 Based in **Edinburgh**, serving clients worldwide  

---

## 💻 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-181717?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r" />
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java" />
  <img src="https://img.shields.io/badge/Flask-000?style=for-the-badge&logo=flask" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=ngoubimaximillian12&show_icons=true&theme=github_dark&count_private=true" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ngoubimaximillian12&layout=compact&theme=github_dark" />
</p>

---

## 🏆 GitHub Trophy Board

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ngoubimaximillian12&theme=darkhub&row=1&column=6" />
</p>

---

## 🔥 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.cyclic.app/graph?username=ngoubimaximillian12&theme=github-dark&hide_border=true" />
</p>

---

## 🚧 Featured Projects with GIFs

| Project | Preview | Description |
|--------|---------|-------------|
| **OmniAgent-AI** | ![](https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif) | Self-learning offline AI assistant using DeepSeek |
| **LLM-AutoML** | ![](https://media.giphy.com/media/xT0xeJpnrWC4XWblEk/giphy.gif) | Zero-code AutoML with fairness feedback |
| **EPL Match Predictor** | ![](https://media.giphy.com/media/3o7TKHh2oG7jYr3nLW/giphy.gif) | Predict match outcomes using ensemble ML |
| **House Price Estimator** | ![](https://media.giphy.com/media/QBd2kLB5qDmysEXre9/giphy.gif) | XGBoost + Streamlit app for real estate |
| **Connect3 Game** | ![](https://media.giphy.com/media/U3qYN8S0j3bpK/giphy.gif) | Python-based 2-player strategy game |

> Replace GIF links above with your own previews when ready.

---

## ⚙️ Auto-Build GitHub README (via Actions)

Create `.github/workflows/README.yml`:

```yaml
name: Update README

on:
  schedule:
    - cron: "0 */6 * * *"
  push:
    branches: [ main ]
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.GITHUB_TOKEN }}
          base: header, activity, community, repositories
