#  Docs-as-Code Starter Kit

This is a lightweight, self-hosted example of a modern technical documentation system using **MkDocs**, **Material for MkDocs**, and **GitHub Actions**.

It demonstrates:
- Docs-as-Code methodology
- CI/CD deployment via GitHub Actions
- Static hosting via GitHub Pages
- Python-based environment with `venv`

---

## Quick Start

```bash
git clone https://github.com/Dom-Caracappa/docs-as-code-starter.git
cd docs-as-code-starter
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Then visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## Project Structure

```
docs-as-code-starter/
├── docs/
│   ├── index.md
│   ├── install.md
│   ├── structure.md
│   ├── customize.md
│   ├── ci-cd.md
│   ├── deploy.md
│   └── assets/
│       └── logo.png
├── .github/
│   └── workflows/
│       └── deploy.yml
├── mkdocs.yml
└── requirements.txt
```

---

## Deployment

This project deploys automatically to GitHub Pages when you push to `main`.

To deploy manually:

```bash
mkdocs gh-deploy --force
```

---

## Author

Made by [Dom Caracappa](https://dom.caracappa.com) to demonstrate high-quality, scalable documentation workflows.

---

## License

MIT
