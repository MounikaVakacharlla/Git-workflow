# Git-workflow


## Objective

As a DevOps trainee, I learned how to implement a feature branch workflow by creating a separate branch, making changes, pushing the branch to GitHub, and creating a Pull Request (PR). This workflow is widely used in enterprise projects to enable collaboration, code review, and controlled integration of changes into the main branch.

---

# Project Context

The feature branch workflow is a standard practice in DevOps and software development because it allows developers to work on new features independently without affecting the main codebase.

---

# Task Performed

## Step 1: Create a Feature Branch

Created a new feature branch from the main branch:

```bash
git checkout -b feature/login-validation
```

### Purpose

* Creates a new branch named `feature/login-validation`.
* Switches the working directory to the newly created branch.
* Keeps changes isolated from the main branch.

---

## Step 2: Create a New File and Add Content

Created a file named `login.md` and added sample content:

```bash
echo "Login validation workflow" > login.md
```

### Purpose

* Simulates a new feature or documentation update.
* Represents work being developed independently.

---

## Step 3: Stage the Changes

Added the file to Git staging area:

```bash
git add login.md
```

### Purpose

* Prepares the file for commit.
* Allows Git to track the changes.

---

## Step 4: Commit the Changes

Committed the staged changes:

```bash
git commit -m "Added login validation documentation"
```

### Purpose

* Saves a snapshot of the changes in the branch.
* Creates a meaningful history of development activities.

---

## Step 5: Push Branch to GitHub

Uploaded the feature branch to the remote repository:

```bash
git push origin feature/login-validation
```

### Purpose

* Publishes the branch to GitHub.
* Makes the branch available for collaboration and review.

---

## Step 6: Create a Pull Request (PR)

After pushing the branch:

1. Opened the GitHub repository.
2. Selected the feature branch.
3. Clicked compare & PullRequest.
4. Compared `feature/login-validation` with `main`.
5. Added title and description.
6. Submitted the Pull Request.

### Purpose

* Requests review before merging changes.
* Enables team collaboration and quality checks.
* Maintains code quality and project standards.

---

# Why Feature Branches Are Used

Feature branches are used because they:

* Isolate new development work from the main branch.
* Allow multiple developers to work simultaneously.
* Reduce the risk of introducing unstable code.
* Make testing easier before merging changes.
* Support organized and structured development workflows.

### Benefits

* Better collaboration
* Safer development process
* Easier troubleshooting
* Improved code management
* Supports parallel development

---

# How Pull Requests Enable Code Review

A Pull Request (PR) is a mechanism for proposing changes before merging them into the main branch.

### Pull Requests Help To:

* Review code quality.
* Identify bugs and issues early.
* Discuss implementation approaches.
* Ensure project standards are followed.
* Approve changes before merging.

### Benefits of Pull Requests

* Improved code quality
* Better team collaboration
* Knowledge sharing among developers
* Reduced production issues
* Controlled and auditable change management

---

Conclusion:

Through this task, I learned how to implement a feature branch workflow used in real-world DevOps and software development projects. I gained hands-on experience creating a feature branch, making changes, committing updates, pushing branches to GitHub, and creating a Pull Request for review. I also understood the importance of feature branches and pull requests in maintaining code quality, enabling collaboration, and supporting a structured development process.

---
