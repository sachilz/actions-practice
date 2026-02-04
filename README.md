# GitHub Actions Triggers Practice

This repository is created to practice and clearly understand how GitHub Actions workflows are triggered.

## 🎯 Goal

Learn the difference between:

- `push` trigger (automatic)
- `workflow_dispatch` trigger (manual)

## 📁 Workflows

This repo contains two separate workflow files:

### 1️⃣ PUSH WORKFLOW
- Runs automatically when code is pushed to the `main` branch.
- Demonstrates how CI pipelines run on commits.

### 2️⃣ MANUAL WORKFLOW
- Runs only when the **Run workflow** button is clicked.
- Demonstrates manual triggering using `workflow_dispatch`.

## 🧪 What I practiced

- How GitHub reads workflow files from `.github/workflows/`
- How multiple workflows run based on different triggers
- How to identify which workflow ran using the run details
- Understanding that GitHub shows all workflow runs in a single timeline

## 💡 Key Learning

> `workflow_dispatch` never runs automatically.  
> A `push` event triggers only the workflows that listen to `push`.

This repository is purely for learning and experimentation with GitHub Actions.
