# Arian (ariandokoohaki) — Backend Developer & DevOps

> I know few things and I’m trying to learn few more — polished, professional GitHub profile.

---

## 👋 About me

* **Name:** Arian
* **Role:** Backend Developer | DevOps enthusiast
* **Location:** (your city / remote)
* **Contact:** [contact@your-email.com](mailto:contact@your-email.com)
* **Short pitch:** I build backend services and automate deployments. I like Python, FastAPI, Docker, and CI/CD.

---

## 🛠 Tech stack

* **Languages:** Python · C++ · Bash
* **Frameworks / Tools:** FastAPI · Docker · Kubernetes (learning) · Git · PostgreSQL
* **Other:** GitLab CI/CD · GitHub Actions · Terraform (optional)

---

## 🚀 Featured projects

> Replace descriptions and links with your repo links and short highlights.

### [Memories-Diary](https://github.com/ariandokoohaki/Memories-Diary)

A personal diary web app — features: user auth, create/read/update/delete entries, export. *Stack:* Python, Flask/Django/FastAPI (replace).

### [todo_app](https://github.com/ariandokoohaki/todo_app)

A simple todo application demonstrating REST APIs and persistence. *Stack:* Python, SQLite/Postgres.

### [postino_notificatin](https://github.com/ariandokoohaki/postino_notificatin)

Notification microservice — background jobs + email/SMS integration.

> Add 2–3 bullet points for each project: goals, technologies, short demo GIF or screenshot (use an `assets/` folder).

---

## 📈 GitHub stats

![Arian's GitHub stats](https://github-readme-stats.vercel.app/api?username=ariandokoohaki\&show_icons=true\&theme=transparent)

---

## ✨ What I’m learning

* Advanced FastAPI patterns and async design
* Production-ready Docker and Kubernetes deployments
* CI/CD security: SAST/DAST and secrets management

---

## 📫 How to reach me

* Instagram: [https://www.instagram.com/ariandokoohaki](https://www.instagram.com/ariandokoohaki)
* Email: [contact@your-email.com](mailto:contact@your-email.com)

---

## ✅ How to use this README

1. Create a **new repository** with the exact name: `ariandokoohaki` (your GitHub username). This will enable this README as your profile README.
2. Copy this file into the new repo as `README.md` and commit.
3. Replace placeholders (email, project links, screenshots).
4. Pin the repos you want to highlight on your profile (4 recommended).

---

## 📝 Tips for each project

* Add a clear README with: purpose, quick demo (GIF), installation, usage, license.
* Provide a `requirements.txt` or `pyproject.toml` and a `Dockerfile` if possible.
* Add a `LICENSE` (MIT is common) and `CONTRIBUTING.md` if you want contributions.
* Add GitHub Actions for CI and show the badge in project READMEs.

---

## Example badges (copy to README)

```
[![CI](https://github.com/ariandokoohaki/todo_app/actions/workflows/python-ci.yml/badge.svg)](https://github.com/ariandokoohaki/todo_app/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
```

---

## Example minimal Python CI workflow (`.github/workflows/python-ci.yml`)

```yaml
name: Python package
on: [push, pull_request]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-python@v4
        with:
          python-version: '3.11'
      - name: Install
        run: |
          python -m pip install --upgrade pip
          pip install -r requirements.txt
      - name: Run tests
        run: |
          pytest -q
```

---

## License

This README template is free to use. Add your project license files separately.

---

> Replace any placeholder text (email, project links, screenshots) before publishing.
