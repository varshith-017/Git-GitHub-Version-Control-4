# Git & GitHub Version Control – DevOps Internship Task 4

## Project Overview

This project demonstrates practical Git and GitHub version control concepts through a simple web application. It showcases repository management, branching strategies, feature development, commits, pull requests, merging, and version tagging.

## Objective

To understand and implement Git and GitHub workflows used in real-world software development and DevOps environments.

## Tools & Technologies

- Git
- GitHub
- Visual Studio Code
- HTML
- CSS
- JavaScript
- Command Prompt / VS Code Terminal

## Project Structure

```text
Git-GitHub-Version-Control-4/
│
├── index.html
├── style.css
├── script.js
├── README.md
├── .gitignore
│
├── docs/
│   └── git-workflow.md
│
└── screenshots/
```

## Git Branching Strategy

This project follows a three-branch workflow:

| Branch | Purpose |
|---|---|
| main | Contains the stable project version |
| dev | Integrates and tests development changes |
| add-project-feature | Implements new project features |

### Branching Workflow

```text
Feature Branch
      |
      | Pull Request
      v
     Dev
      |
      | Pull Request
      v
     Main
      |
      v
   Release v1.0
```

## Git Operations Implemented

1. Initialized a local Git repository.
2. Connected the local repository to GitHub.
3. Created main, dev, and feature branches.
4. Added and committed project files.
5. Implemented a feature branch demonstration.
6. Pushed branches to GitHub.
7. Created and merged Pull Requests.
8. Merged feature into dev.
9. Merged dev into main.
10. Created and pushed Git tag v1.0.

## Important Git Commands

```bash
git init
git add .
git commit -m "Initial commit"
git branch
git switch dev
git switch -c add-project-feature
git remote add origin <repository-url>
git push -u origin main
git pull origin main
git merge dev
git tag -a v1.0 -m "First stable release"
git push origin v1.0
git log --oneline --graph --all
git status
```

## GitHub Repository

**Repository:** Git-GitHub-Version-Control-4

**GitHub URL:**  
https://github.com/varshith-017/Git-GitHub-Version-Control-4

## Version Information

- Project Version: 1.0
- Git Tag: v1.0
- Version Status: First Stable Release

## Learning Outcomes

- Understanding distributed version control systems.
- Managing repositories using Git and GitHub.
- Working with multiple branches.
- Understanding commits, pushes, and pulls.
- Creating and merging Pull Requests.
- Understanding collaborative development workflows.
- Managing project versions using Git tags.
- Maintaining project documentation using Markdown.

## Conclusion

This project provided hands-on experience with Git and GitHub version control. It demonstrated how developers manage source code, work with branches, collaborate through Pull Requests, and maintain stable releases.

The project successfully demonstrates a basic Git branching and version-control workflow used in real-world DevOps practices.

---

**DevOps Internship – Task 4**  
**Project:** Git & GitHub Version Control  
**Version:** v1.0