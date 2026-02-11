# UCSB-DS-PROJ-2026
A rent prediction model on Goleta &amp; Isla Vista housing prices

## UCSB DS Project – Team Workflow Guide
🔹 What This Project Is

We are building a rent prediction model using Python and Jupyter notebooks.
We are using GitHub to collaborate.

## Before You Start (One-Time Setup)
1️⃣ Clone the Repository
Open Terminal and run:
```
git clone https://github.com/AnikaAchary/UCSB-DS-PROJ-2026.git
cd UCSB-DS-PROJ-2026
```
2️⃣ Create a Virtual Environment (IMPORTANT)
```
python -m venv venv
source venv/bin/activate   # Mac
```
Install dependencies:
```
pip install -r requirements.txt
```

## Project Structure
```
UCSB-DS-PROJ-2026/
│── notebooks/       → Jupyter notebooks (analysis)
│── src/             → Reusable Python code
│── data/            → Data files (DO NOT upload huge files)
│── models/          → Saved trained models
│── README.md        → Instructions
│── requirements.txt → Python packages
```

## Team Rules (VERY IMPORTANT)

#### Rule 1: NEVER work directly on ```main```

Always create your own branch:
```
git checkout -b feature/your-name-task
```
Example:
```
git checkout -b feature/anika-eda
```

#### Rule 2: Pull before you start working
```
git pull origin main
```
Always do this before starting work.

#### Rule 3: Commit Often (Small Changes)

After making changes:
```
git add .
git commit -m "Short description of what you did"
git push
```

Example:
```
git commit -m "Add feature engineering functions"
```

#### Rule 4: Use Pull Requests (PRs)
After pushing your branch:
1. Go to GitHub
2. Click Compare & Pull Request
3. Add a short description
4. Submit

Someone reviews before merging into ```main```

❌ DO NOT:

❌ Edit someone else’s notebook without asking

❌ Push directly to main

❌ Upload huge raw datasets

❌ Delete files randomly

## Notebook Guidelines

We avoid merge conflicts by splitting work:

01_eda.ipynb → Data exploration

02_modeling.ipynb → Model training

03_results.ipynb → Final evaluation

If you are assigned a notebook, you “own” it.

## Code Guidelines

Reusable code goes in ```src/```:

Example:
```
data_prep.py
features.py
train.py
evaluate.py
```
## If Something Breaks

Run:
```
git status
```

If unsure:
1. Don't panic
2. Don't delete the repo
3. Ask in groupchat with a screenshot


