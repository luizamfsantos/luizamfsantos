<h1 align="center">Hi, I'm Luiza Santos</h1>
<h3 align="center">I'm a researcher and engineer from Brazil</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/santosluiza/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://komarev.com/ghpvc/?username=luizamfsantos&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="Profile views" />
</p>

<br>

- Currently working on: some projects not yet ready to see the light of day. Don't fret, I got a lot of open repositories for you to dig.
- I would appreciate any feedback on my repos.

<br>

### Highlighted Projects

**[or-experiments-template](https://github.com/luizamfsantos/or-experiments-template)** — Scaffold for optimization-research group projects · *Last worked on: August 2026*
- Pre-commit hooks enforcing complexity limits (radon), lint/format (ruff), and stripped notebook outputs
- GitHub Actions CI (lint + pytest with coverage) gated by CODEOWNERS branch protection
- Experiment configs require a goal/hypothesis/design-note/status block for traceability
- Multiple solver backends (Pyomo/Gurobi/HiGHS, CP-SAT, heuristics) reporting into one comparable result schema

**[bot-detection-mlflow](https://github.com/luizamfsantos/bot-detection-mlflow)** — Modular ML training and evaluation pipeline · *Last worked on: June 2026*
- MLflow experiment tracking with config-driven runs (YAML per experiment)
- Statistical comparison of algorithm performance, not just point metrics
- Model serving via a `/predict` endpoint with automatic feature imputation
- Health-check endpoint for deployment readiness

**[long-short-lstm](https://github.com/luizamfsantos/long-short-lstm)** — LSTM-based long-short trading strategy · *Last worked on: May 2025*
- End-to-end pipeline: data ingestion → LSTM model → trading strategy → backtesting simulation
- Dockerized for reproducible training and simulation runs
- Test suite covering ingestion, model, trading, and simulator logic

**[Weather-Data-Pipeline](https://github.com/luizamfsantos/Weather-Data-Pipeline)** — ELT pipeline for NOAA's Integrated Surface Database · *Last worked on: June 2023*
- Ingests 1.4B+ hourly records (12GB, ~13,000 archive files) from 10,000+ stations via AWS S3
- Orchestrated with Apache Airflow (download → extract → combine → stage → upsert)
- PostgreSQL staging/transform layer feeding a Metabase dashboard for real-time analytics
- Fully containerized with Docker Compose

<br>

### Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow" />
  <img src="https://img.shields.io/badge/Prefect-070E10?style=for-the-badge&logo=prefect&logoColor=white" alt="Prefect" />
  <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="CI/CD" />
</p>

<br>

### GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=luizamfsantos&" alt="GitHub streak stats" />
</p>

<br>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/luizamfsantos/luizamfsantos/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/luizamfsantos/luizamfsantos/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/luizamfsantos/luizamfsantos/output/github-contribution-grid-snake.svg">
  </picture>
</p>
