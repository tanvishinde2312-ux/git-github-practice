# Git Workflow

This document explains the basic Git workflow that I learned while practicing Git and GitHub.

---

## What is Git Workflow?

Git Workflow is the sequence of steps used to manage changes in a project using Git and GitHub.

---

## Step 1: Create or Clone a Repository

To create a local copy of an existing repository:

```bash
git clone <repository-url>
```

---

## Step 2: Check Repository Status

View the current status of your files:

```bash
git status
```

---

## Step 3: Create or Modify Files

Make changes to existing files or create new files in your project.

Example:
- README.md
- git-commands.md
- markdown-notes.md

---

## Step 4: Stage Changes

Add files to the staging area:

```bash
git add .
```

---

## Step 5: Commit Changes

Save your changes with a meaningful message:

```bash
git commit -m "Add Git workflow documentation"
```

---

## Step 6: Push Changes

Upload your commits to GitHub:

```bash
git push origin main
```

---

## Step 7: Pull Latest Changes

Download the latest updates from GitHub:

```bash
git pull origin main
```

---

## Step 8: Create a Branch

Create a new branch for developing a feature:

```bash
git branch feature-branch
```

Switch to the branch:

```bash
git checkout feature-branch
```

Or use:

```bash
git switch feature-branch
```

---

## Step 9: Merge a Branch

After completing your work, merge it into the main branch:

```bash
git merge feature-branch
```

---

## Git Workflow Diagram

```text
Create Repository
        │
        ▼
Clone Repository
        │
        ▼
Create / Edit Files
        │
        ▼
git add .
        │
        ▼
git commit
        │
        ▼
git push
        │
        ▼
GitHub Repository
        │
        ▼
Collaborate / Pull Requests
```

---

## Best Practices

- Write clear commit messages.
- Commit small changes regularly.
- Pull the latest changes before starting work.
- Use branches for new features.
- Keep your README updated.

---

## Learning Outcome

After completing this Git workflow practice, I can:

- Create repositories
- Track file changes
- Stage and commit updates
- Push code to GitHub
- Pull changes from GitHub
- Create and manage branches
- Follow a basic Git workflow
