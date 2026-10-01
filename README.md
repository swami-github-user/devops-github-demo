# DevOps GitHub Demo

A simple static website for practicing Git and GitHub as part of the DevOps MasterClass.

## Project Structure

```
devops-github-demo/
│
├── index.html
├── style.css
└── README.md
```

## Run Locally

Open `index.html` in any browser.

## Git Workflow

```bash
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/devops-github-demo.git
git push -u origin main
```

## Deploy with GitHub Pages

1. Go to the repository **Settings → Pages**
2. Under **Source**, select the `main` branch and `/ (root)` folder
3. Save. Your site will be live at `https://<your-username>.github.io/devops-github-demo/`
