<!-- Accent palette: #6C63FF (indigo) • #00BFA6 (teal) • #FF6B6B (coral) -->
<h1 align="center">Syeda Rabbiya Bukhari</h1>
<p align="center">BS Data Science @ FCIT (7th semester) • Machine Learning • HTR Research (team) • UI/UX (learning)</p>

<p align="center">
  <a href="https://www.kaggle.com/rabbiyabukhari">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/>
  </a>
  <a href="https://www.linkedin.com/in/syeda-rabbiya-bukhari-462819196/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:rabbiya.bukhari786@gmail.com">
    <img src="https://img.shields.io/badge/Email-6C63FF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## About me
I build practical ML projects and write down what works and what doesn’t.  
I’m part of a team working on **handwritten text recognition (HTR)** for **Notescape**, where we benchmark on standard datasets and focus on **improving accuracy** (CER/WER) through better training, decoding, augmentation, and error analysis.

## Now
- Strengthening ML fundamentals: EDA → features → classic models → proper validation
- Studying deep learning (foundations, training routines, evaluation)
- Strengthening UI/UX across my projects so results are clear, accessible, and visually consistent
- Improving repo structure and READMEs across learning projects

---

## Featured projects

- **Plantly (team project): plant recognition + care tips**  
  Uses the plant.id API for identification and Wikipedia scraping for concise care guidance.  
  **My role:** care-tips pipeline and API integration.  
  _TypeScript, React, Flask/FastAPI_  
  Repo: https://github.com/rabbiyabukhari/ML_project-plantly-smart-plant-care

- **Google Play Store: analysis, clustering, rating prediction**  
  Notebook-driven pipeline: data cleaning, EDA, KMeans clustering, and baseline regression (RandomForest/GradientBoosting) with MAE/MSE/R² reporting.  
  _Python, pandas, scikit-learn, matplotlib_  
  Repo: https://github.com/rabbiyabukhari/Google-Play-Store-Apps-Comprehensive-Analysis-Clustering-and-Prediction

- **Artificial Intelligence (classic search algorithms)**  
  BFS, DFS, IDDFS, Greedy Best-First, and A* with notes and lab material.  
  _Python_  
  Repo: https://github.com/rabbiyabukhari/Artificial_Intelligence

- **Dynamic Programming (learning repo)**  
  Solutions to core DP problems (knapsack, LIS, coin change, edit distance, etc).  
  _Python_  
  Repo: https://github.com/rabbiyabukhari/Dynammic-Programming-Codes  <!-- consider renaming to Dynamic-Programming-Codes -->

- **Notescape (team project): AI-assisted study workspace**  
  **My role:** CI/CD setup (GitHub Actions), file-upload pipeline, PDF chunking for downstream processing/search, merging teammates’ work (PR reviews), UI/UX design for study flows; ongoing HTR research to improve accuracy on existing datasets (CER/WER benchmarking).  
  _TypeScript, React_  
  Repo: https://github.com/NotescapeAi/Notescape

---

## Competitions

- **SOFTEC’25 – Machine Learning (36-hour sprint)** — **21/25 overall**  
  This rattled me. Instead of deciding ML wasn’t my cup of tea, I asked the better question: where does my practice actually lack, what don’t I know yet, and what should I do next?

- **PuCON'25 - Palm Print | Auth (two rounds)** — **4/24 in Round 2 (jury evaluation)**  
  I briefly reached 1st on the live board. In the last six hours I couldn’t work because I was also competing elsewhere. I also made preventable mistakes:
  - Trained on Colab T4 across two Google accounts, so run and file tracking suffered
  - Training error oscillated and accuracy stalled near ~96%, and under pressure I hard-coded a threshold/percent
  - Limited evolutionary search to ~30 generations while others ran ~100+
  - Didn’t stand up a minimal RNN baseline in time

### What I learned
- One account and a clean folder tree. If files are messy, results will be messy.
- No hard-coded thresholds. Tune on a held-out set and record the choice.
- Give search methods enough budget and log convergence.
- Start with a simple baseline, change one thing at a time, and measure it.
- Avoid overlapping commitments near the deadline; reserve the last six hours for stability checks.

### Next-time plan
- Colab hygiene: `/MyDrive/ml_runs/<project>/<YYYY-MM-DD>_<exp>` with a `config.json` per run
- Tracking: write `metrics.csv` with timestamp, seed, config hash, MAE/MSE/F1, and chosen threshold; save artifacts per run
- Budget: 100–150 generations or trials with patience and early stop
- Baselines: keep a tiny RNN and a tree-based regressor that train in under a minute
- Schedule: no parallel competitions on the final day; keep a final test window for sanity checks

---

## Skills (working set)
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&labelColor=3776AB&color=3776AB" />
  <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white&labelColor=150458&color=150458" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white&labelColor=F7931E&color=F7931E" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&labelColor=009688&color=009688" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&labelColor=2496ED&color=2496ED" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-6C63FF?logo=githubactions&logoColor=white&labelColor=6C63FF&color=6C63FF" />
  <img src="https://img.shields.io/badge/Figma-00BFA6?logo=figma&logoColor=white&labelColor=00BFA6&color=00BFA6" />
</p>

**Languages:** Python, SQL, TypeScript  
**ML:** scikit-learn, model selection/validation, basic tuning  
**Data:** pandas, NumPy, matplotlib  
**Apps/Tools:** FastAPI, Git, Docker, Linux, Jupyter/Colab  
**Research (HTR):** benchmarking on existing datasets, CER/WER evaluation, decoding strategies, augmentation, error analysis  
**UI/UX:** basic Figma; layout and typography for data apps  
**Ops:** CI/CD with GitHub Actions; repo hygiene and PR reviews

## Education
**BS Data Science, FCIT** · 7th semester

**A Levels, The Lahore Alma**  
Selected subjects: Computer Science, Mathematics, Art & Design

**O Levels, Garrison Academy for Cambridge Studies**  
Selected subjects: Mathematics, Physics, Chemistry, Computer Science


## GitHub stats
<p>
  <img src="https://github-readme-stats.vercel.app/api?username=rabbiyabukhari&show_icons=true&hide_title=true&theme=tokyonight" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rabbiyabukhari&layout=compact&theme=tokyonight" height="150" />
</p>
