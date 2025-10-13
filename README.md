# How to Push Code with Git & VS Code (to and from GitHub)

This guide teaches a simple, repeatable workflow to move code between your computer (VS Code) and GitHub.

## What you will learn
1. Create and clone a GitHub repository
2. Make changes locally in VS Code
3. Add, commit, and push changes to GitHub
4. Create branches and open Pull Requests
5. Sync main and keep your repo clean

## Introduction

Git tracks your code changes, GitHub stores them online, and VS Code is where you write and edit your code.  
Together, they make it easy to manage and share your projects safely.

## Code Example

Here’s a quick demo of how to push code from VS Code to GitHub:

```bash
# Stage your changes
git add .

# Commit your work
git commit -m "Updated project files"

# Push your code to GitHub
git push origin main
