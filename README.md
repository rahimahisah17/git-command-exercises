# Git Command Exercises

![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)
![Markdown](https://img.shields.io/badge/Markdown-Documentation-000000?logo=markdown)

A hands-on Git practice repository demonstrating essential Git commands used in day-to-day software development. This project covers Git configuration, repository initialization, file tracking, committing changes, connecting to a remote repository, pushing to GitHub, and preparing a repository for GitHub Actions workflows.

Each exercise includes the command executed, a brief explanation, and a corresponding screenshot captured in Visual Studio Code.

## 🎯 Learning Objectives

By completing this project, you will learn how to:

- Configure Git with a global username and email.
- Initialize a new Git repository.
- Create and track files using Git.
- Stage changes before committing.
- Create meaningful commits using conventional commit messages.
- Connect a local repository to a remote GitHub repository.
- Push commits to GitHub.
- Create the directory structure required for GitHub Actions.
- Document Git workflows using Markdown.
```
## 📁 Project Structure

```text
git-command-exercises/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── screenshots/
│   ├── config.png
│   ├── init.png
│   ├── index.png
│   ├── vim.png
│   ├── stage.png
│   ├── commit.png
│   ├── remote.png
│   ├── push.png
│   ├── workflow.png
│   └── deploy.png
├── README.md
└── index.html
```
## 🚀 Exercises

### 1. Configure Git

Configure the global Git username and email.

```bash
git config --global user.name "DevUser" && git config --global user.email "dev@skill-sch.com"
```

![Configure Git](screenshots/config.png)

---

### 2. Initialize a Repository

Create a project directory and initialize Git.

```bash
mkdir git-command-exercises && cd git-command-exercises && git init
```

![Initialize Repository](screenshots/init.png)

---

### 3. Create a File

Create the `index.html` file.

```bash
touch index.html
```

![Create File](screenshots/index.png)

---

### 4. Open the File in Vim

Open `index.html` using Vim.

```bash
vim index.html
```

![Open in Vim](screenshots/vim.png)

---

### 5. Stage the File

Stage the file for commit.

```bash
git add index.html
```

![Stage File](screenshots/stage.png)

### 6. Commit Changes

Commit the staged changes.

```bash
git commit -m "feat: add home page"
```

![Commit Changes](screenshots/commit.png)

---

### 7. Add a Remote Repository

Connect the local repository to GitHub.

```bash
git remote add origin https://github.com/rahimahisah17/git-command-exercises.git
```

![Add Remote](screenshots/remote.png)

---

### 8. Push to GitHub

Push the local branch to the remote repository.

```bash
git push -u origin main
```

![Push to GitHub](screenshots/push.png)

---

### 9. Create the GitHub Actions Workflow Directory

Create the directory structure for GitHub Actions.

```bash
mkdir -p .github/workflows
```

![Workflow Directory](screenshots/workflow.png)

---

### 10. Create the Deployment Workflow

Create the deployment workflow file.

```bash
touch .github/workflows/deploy.yml
```

![Deployment Workflow](screenshots/deploy.png)