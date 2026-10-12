# Setting Up Git

Git is a version control system that helps you track changes to files.

## 1. Install Git

Download Git from https://git-scm.com/downloads.

## 2. Configure Your Identity

Run these commands in your terminal:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Use the name and email you want associated with your commits.

## 3. Check Your Configuration

```bash
git config --global --list
git --version
```

## 4. Clone a Repository

```bash
git clone <repository-url>
```

This creates a local copy of the repository.

## 5. Check the Repository Status

```bash
git status
```

This shows the current state of your working directory.
