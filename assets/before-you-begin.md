# Before you begin

Use this checklist before working on a lecture notebook or homework.

**First time?** Work through the [Getting Started guide](https://docs.google.com/document/d/1jUiWn5Q7L2bPBx7yrEfOYs7Cy5U-pQGrA9VJSkVC5Bs) first, then come back here.

## 1. Save your work

Save your notebook or script and keep a backup copy of any edits you want to keep **before** updating the course files.

## 2. Get the latest course files

### If you cloned the repository

Open the `ma` folder in VS Code, choose **Terminal → New Terminal**, and run:

```sh
git pull
```

You can also use your computer's terminal from inside `ma`.

> **If Git reports a conflict or says your changes would be overwritten, pause.** Ask your AI agent to help you keep your work safe before continuing, or email the TA. Do not discard your work just to make the update succeed.

### If you download files manually

Open the specific file you need in [scripts](https://github.com/apostolosfilippas/ma/tree/main/scripts) or [homework](https://github.com/apostolosfilippas/ma/tree/main/homework) on GitHub, then click **Download raw file** (the download arrow).

Download any required [data files](https://github.com/apostolosfilippas/ma/tree/main/data) too. Keep the same folder structure on your computer: notebooks in `scripts/` or `homework/`, and input data in `data/`, all inside `ma`.

To keep the course environment current, also download [pyproject.toml](https://github.com/apostolosfilippas/ma/blob/main/pyproject.toml), [uv.lock](https://github.com/apostolosfilippas/ma/blob/main/uv.lock), and [.python-version](https://github.com/apostolosfilippas/ma/blob/main/.python-version) into `ma`, backing up any changes you made to them first. Downloading a notebook alone does not set up Python; use the Getting Started guide if you have not done that yet.

## 3. Update your Python environment

In a terminal inside `ma`, run:

```sh
uv sync
```

This installs the package versions required by the course.

## 4. Open your file and begin

**Notebook (`.ipynb`):** Open it in VS Code, click **Select Kernel**, and choose the course's `.venv` environment. Run code cells from top to bottom with **Shift + Enter**, waiting for each to finish. Some homeworks contain only instructions; read those and create your work as directed.

**Python script (`.py`):** In VS Code's Command Palette, choose **Python: Select Interpreter**, select the course's `.venv`, then click **Run Python File**. For example, you can also run the first script from a terminal inside `ma`:

```sh
uv run python scripts/0.simple.py
```

## If something does not work

Save the full error message and a screenshot of the whole window. You can ask your AI agent for help, or email the TA with both and a short description of what you tried.
