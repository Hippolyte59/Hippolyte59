
# 👋 Salut, je suis Hippolyte

**Développeur full‑stack | Web |
Open‑Source**  
  

---
![GitHub Followers](https://img.shields.io/github/followers/Hippolyte59?style=flat)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=Cloudflare&logoColor=white)
![OVH](https://img.shields.io/badge/OVH-%23123F6D?style=flat&logo=OVH&logoColor=blue)
![Proxmox](https://img.shields.io/badge/Proxmox-proxmox?style=flat&logo=Proxmox&logoColor=%23E57000&labelColor=%232b2a33&color=%232b2a33)
![Visual Studio Code](https://img.shields.io/badge/VS%20Code-0078d7?style=flat&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## 🛠️ Stack & Outils

**Frontend**  
React · Next.js · TypeScript · HTML5 · CSS3 · TailwindCSS · SASS · Vite  
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwind-css&logoColor=white)

**Backend**  
Python (FastAPI, Django) · Node.js (Express, NestJS) · GraphQL · REST  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)  
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)

**Bases de données & Data**  
PostgreSQL · MySQL · MongoDB · Redis · SQLAlchemy · Alembic · Prisma  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)

**DevOps & Cloud**  
Docker · Kubernetes · Helm · GitHub Actions · Terraform · AWS (EKS, S3, RDS)  
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)  

**Tests & Qualité**  
pytest · unittest · jest · Playwright · ESLint · pre-commit · SonarCloud  

**Observabilité & Sécurité**  
Prometheus · Grafana · Sentry · OAuth2/JWT · OWASP  

**Outils divers**  
Git · Linux · tmux · VSCode · Postman · DBeaver  

---

## 🚀 Projets phares
- **[app-portfolio](https://github.com/Hippolyte59/app-portfolio)** — Portfolio React + FastAPI · Docker · JWT Auth  
- **[data-dashboard](https://github.com/Hippolyte59/data-dashboard)** — Dashboard temps réel · Graphs · Filtrage interactif  
- **[automation-bot](https://github.com/Hippolyte59/automation-bot)** — Scripts Python ETL · Scraping · Tests automatisés  

![GIF projets](https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif)

---

## 📊 Statistiques GitHub
![Hippolyte59 GitHub Stats](https://github-readme-stats.vercel.app/api?username=Hippolyte59&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Hippolyte59&layout=compact&theme=tokyonight)
![Activity Graph](https://github-readme-activity-graph.cyclic.app/graph?username=Hippolyte59&theme=react-dark&hide_border=true)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=Hippolyte59&theme=tokyonight)

---

## 💻 Compétences importantes
- **Architecture :** Clean Architecture, Hexagonal, DDD  
- **Méthodes :** TDD, CI/CD, code review strict, documentation vivante  
- **Performance :** Caching, mise à l’échelle horizontale, optimisation SQL  
- **Sécurité :** Gestion des secrets, tests intégration sécurité  

---

## 🌐 Contact
- Email : hippolyte@example.com  
- Portfolio : [https://hippolyte.dev](https://hippolyte.dev)  
- LinkedIn : [https://www.linkedin.com/in/hippolyte](https://www.linkedin.com/in/hippolyte)  
- Twitter : [https://twitter.com/hippolyte_dev](https://twitter.com/hippolyte_dev)  

---

## ⚡ Automatisation
- GitHub Actions pour mettre à jour le README (What I’m working on, stats, repos épinglés)  
- Services : [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats), [Activity Graph](https://github.com/ashutosh00710/github-readme-activity-graph), [Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)

```yaml
name: Update README
on:
  schedule:
    - cron: '0 8 * * *'
  workflow_dispatch:
jobs:
  update:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - run: echo "Update README sections dynamically"
      - run: |
          git config user.name "github-actions"
          git config user.email "actions@github.com"
          git add README.md && git commit -m "chore: update README" || echo "no changes"
          git push
