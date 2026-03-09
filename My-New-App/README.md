# Week 03: Developer tools and Workflow

## Author

- **Name:** Purity Wanjiku Muriithi
- **GitHub:** https://github.com/PURITY-MURIITHI
- **Date:** 09/03/2026

## Project Description

### Why I Created This Project

This week focused on mastering the Command Line Interface (CLI) and Advanced Git Workflows. These tools are the backbone of professional development, allowing for faster project management, automated scripting, and seamless collaboration through GitHub.

### What I created this project for.

This repository serves as a practical demonstration of my ability to navigate file systems via terminal, automate project setups with PowerShell scripts, and manage complex version control scenarios including branching, merging, and remote synchronization.


## Technologies Used

- PowerShell / Bash (Terminal Navigation & Scripting)
- Git (Version Control)
- GitHub (Remote Collaboration)
- Markdown (Documentation)

## Project Structure
C:.
```
├───docs
├───iyf-s10-week-01-PURITY-MURIITHI
│   ├───My-New-App
│   │   └───src
│   │       ├───css
│   │       └───js
│   └───src
│       └───assets
│           └───images
├───My-Awesome-App
│   ├───docs
│   ├───src
│   │   ├───css
│   │   ├───images
│   │   └───js
│   └───tests
├───My-New-App
│   ├───docs
│   ├───src
│   │   ├───css
│   │   ├───images
│   │   └───js
│   └───tests
├───src
│   └───assets
│       └───images
├───tests
└───week03-clone
    ├───My-New-App
    │   └───src
    │       ├───css
    │       └───js
    └───src
        └───assets
            └───images
```
## Screenshot

![AwesomeApp](src/assets/images/awesomeapp.png)
![AwesomeApp2](src/assets/images/awesomeapp2.png)
![Gitignore](src/assets/images/gitignore.png)

## Features

✅ CLI Proficiency - Full directory management without a GUI.
✅ Automated Workflow - Custom PowerShell script for instant project scaffolding.
✅ Branching Strategy - Managed feature development using isolated Git branches.
✅ Remote Synchronization - Demonstrated push, pull, and clone workflows.
✅ Environment Protection - Implemented .gitignore to keep repositories clean.


## How to Run

1. Clone the repo: git clone https://github.com/PURITY-MURIITHI/iyf-s10-week-03-PURITY-MURIITHI.git
2. Run Script: Execute .\new-project.ps1 -ProjectName "My-Awesome-App" to see the automation in action.
3. Verify Git: Run git log --oneline to view the full version history of this tasks.

## Lessons Learnt

### **Technical Skills & Proficiency Levels**

- Terminal Navigation 
What I did: Managed files entirely via PowerShell using cd, mkdir -p, and ls. I practiced moving and renaming assets like purity.jpg using CLI commands.

- Shell Scripting 
What I did: Wrote a new-project.ps1 script to automate the creation of standardized project structures, saving time on setup.

- Git Branching & Merging 
What I did: Used git checkout -b to develop features in isolation and merged them into main after resolving simulated conflicts.

- Remote Workflow 
What I did: Mastered the git remote -v and git pull sequence to synchronize work between a local environment and a "simulated collaborator" (cloned folder).

### Challenges Faced

1. Duplicate File Extensions
Challenge: An asset was incorrectly named purity.jpg.jpeg, causing confusion in the file path.
Solution: Used the PowerShell command Rename-Item to clean the extension to a standard .jpeg format for better code referencing.

2. PowerShell Script Execution Policies
Challenge: Running .ps1 scripts can sometimes be blocked by Windows security policies.
Solution: Learned to set execution policies to allow custom scripts to run safely during development.

## Future Improvements

- [ ] **Enhance Setup Script**: Add automatic `git init` and an initial commit to `new-project.ps1`.
- [ ] **Git Shortcuts**: Create PowerShell aliases for frequent commands like `git status` and `git pull`.
- [ ] **CI/CD Basics**: Explore GitHub Actions to automatically "lint" or check my code formatting on every push.
- [ ] **Asset Optimization**: Add a script step to compress images in the `assets/images/` folder automatically.


## Contact

- Email: muriithipurity28@gmail.com
- LinkedIn: [Purity Muriithi](www.linkedin.com/in/purity-muriithi-295955212
)
- GitHub: [@PURITY-MURIITHI](https://github.com/PURITY-MURIITHI)

## Live Demo

[View Live Demo](https://github.com/PURITY-MURIITHI/iyf-s10-week-03-PURITY-MURIITHI.git)

## License

This project is open source and available under the [MIT License](LICENSE).

# My-New-App
