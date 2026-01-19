# gh-deployment-workflow
CI/CD project: Automated GitHub Pages deployment using GitHub Actions
# GitHub Pages Deployment with CI/CD

[![Deploy to GitHub Pages](https://github.com/mostakimidlc-prog/gh-deployment-workflow/actions/workflows/deploy.yml/badge.svg)](https://github.com/mostakimidlc-prog/gh-deployment-workflow/actions/workflows/deploy.yml)

## 📖 Project Description

This project demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions. Any changes to `index.html` automatically trigger a deployment to GitHub Pages.
https://roadmap.sh/projects/github-actions-deployment-workflow
## 🌐 Live Demo

Visit the deployed website: [https://mostakimidlc-prog.github.io/gh-deployment-workflow/](https://mostakimidlc-prog.github.io/gh-deployment-workflow/)

## 🎯 Project Goals

- Learn GitHub Actions workflow syntax
- Understand CI/CD concepts
- Automate deployment to GitHub Pages
- Practice conditional workflow execution

## 🔧 How It Works

1. Developer pushes changes to the `main` branch
2. GitHub Actions workflow detects changes to `index.html`
3. Workflow builds and deploys the site to GitHub Pages
4. Website is automatically updated

## 📁 Project Structure
```
gh-deployment-workflow/
├── .github/
│   └── workflows/
│       └── deploy.yml       # GitHub Actions workflow
├── index.html               # Main HTML file
└── README.md               # Project documentation
```

## 🚀 Technologies Used

- **GitHub Actions** - CI/CD automation
- **GitHub Pages** - Static site hosting
- **HTML/CSS** - Website content

## 📝 Workflow Features

- ✅ Triggers only on `index.html` changes
- ✅ Deploys only from `main` branch
- ✅ Automatic build and deployment
- ✅ No manual intervention required

## 🧪 Testing the Workflow

1. Clone this repository
2. Make changes to `index.html`
3. Commit and push to `main` branch
4. Watch the Actions tab for deployment progress
5. Visit the GitHub Pages URL to see updates

## 📚 Learning Outcomes

- GitHub Actions workflow configuration
- Path-based triggering in CI/CD
- GitHub Pages deployment
- YAML syntax for workflows
- CI/CD best practices

---

**Author:** mostakimidlc-prog  
**Project Type:** DevOps Learning Project
