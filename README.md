# Library Project

A small web project with `index.html`, `script.js`, and `styles.css`.

## What I added
- README.md
- .gitignore
- LICENSE (MIT)

## Quick start
1. Open `index.html` in your browser.

## GitHub
To create a GitHub repo and push:

1. Create a new repository on GitHub (e.g., `library`).
2. Add the remote and push:

```bash
cd /home/arijanb/library
git init
git add .
git commit -m "chore: initial commit"
git remote add origin git@github.com:<your-username>/library.git
git branch -M main
git push -u origin main
```

Alternatively, use GitHub CLI:

```bash
gh repo create <your-username>/library --public --source=. --remote=origin --push
```
