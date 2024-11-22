# Understanding Git Branches

## What is a Git Branch?
A **branch** in Git is essentially a pointer to one of the commits in your repository's history. By default, every Git repository starts with a branch called `main` (or `master` in older versions). Branches allow you to isolate your work, which is useful for developing features, fixing bugs, or experimenting without affecting the main project.

## Key Concepts of Git Branches

### 1. **Why Use Branches?**
Branches in Git provide a way to:

- **Isolate work**: Work on a feature or bug fix without disturbing the main or stable codebase.
- **Parallel Development**: Multiple developers can work on different features at the same time.
- **Experimentation**: Safely try out new ideas without affecting the main project.

### 2. **How Branching Works**
- When you create a new branch, it is based on the current state of the branch you're on (often `main`).
- The new branch starts off with the same history as the branch it was branched from.
- You can work on the new branch independently. Any commits made will only affect that branch.
- To merge your changes into the main branch, you'll perform a **merge**.

## Basic Git Branch Commands

### 1. **Create a New Branch**
```bash
git branch <branch-name>
