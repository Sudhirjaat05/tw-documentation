# Git – Local Version Control System

## What is Git?
Git is a distributed version control system that records project file modifications over time, allowing complete history tracking and safe experimental branching[cite: 41, 46].

## Essential Commands Learned in Class
- **Initialization & Identity:** 
  - `git init`[cite: 55]
  - `git config --global user.name "Name"` & `git config --global user.email "email"`[cite: 53]
- **Core Workflow:**
  - `git status` (inspect working directory)[cite: 59]
  - `git add .` (stage modifications)[cite: 61]
  - `git commit -m "Message"` (record local snapshot)[cite: 62]
- **Branching & History:**
  - `git log --oneline`[cite: 64]
  - `git switch -c <branch-name>`[cite: 90]
  - `git merge <branch>`[cite: 91]