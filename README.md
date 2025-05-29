

# 📦 DevOps Git Project

Welcome to the *DevOps Git Workflow Project*. This project is designed to help you understand how to manage a project using Git and GitHub by following best practices used in real-world software development.

---

## 📁 Project Structure


main                # Final stable code (production-ready)
└── Dev             # Development branch for active work
    └── feature/*   # Individual feature branches (e.g., feature/login-page)


---

## 🎯 Objective

The main goal is to practice version control skills and workflows, including:

* Creating and using different branches
* Working with pull requests
* Writing clear commit messages
* Using tags for versioning
* Collaborating through GitHub

---

## 🚀 Getting Started

### Clone the Repository

bash
git clone https://github.com/Shashimpally/DevOps_git_project.git
cd DevOps_git_project


---

## 🔀 Branching Workflow

### 1. Create the Development Branch

bash
git checkout -b Dev


### 2. Create a Feature Branch from Dev

bash
git checkout Dev
git checkout -b feature/your-feature-name


### 3. Merge Feature Branch into Dev (once feature is complete)

bash
git checkout Dev
git merge feature/your-feature-name


### 4. Merge Dev into Main (final release)

> Use a *Pull Request* on GitHub to merge Dev into Main for clean collaboration.

---

## 📄 Key Files

* index.html – Starter file or web page
* .gitignore – Lists files/folders to exclude from Git tracking
* README.md – This documentation file
* Other features/pages should be built in separate feature branches

---

## 🏁 Outcome

By working on this project, you’ll learn how to:

* Organize your code using branches
* Collaborate effectively with others on GitHub
* Maintain a clean, professional Git history
