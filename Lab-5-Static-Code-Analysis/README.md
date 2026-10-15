# Lab 5 — Static Code Analysis

This repository folder contains the coursework for Lab 5.

## Objective
Improve Python code quality, security, and style using **Pylint**, **Bandit**, and **Flake8**.

## Setup
```bash
python3 -m venv venv
# Windows PowerShell: .\venv\Scripts\Activate.ps1
# Linux/macOS: source venv/bin/activate
python -m pip install pylint bandit flake8
```

## Analyze the assigned Python script
Replace `your_python_script.py` with the actual assigned filename.

```bash
pylint your_python_script.py > pylint_report_before.txt
bandit -r your_python_script.py > bandit_report_before.txt
flake8 your_python_script.py > flake8_report_before.txt
```

## Required work
1. Identify and fix at least four issues, prioritizing high- and medium-severity findings.
2. Document each issue, type, line number, description, and fix in an issue table.
3. Re-run all three tools and save the after-fix reports.
4. Aim for a Pylint score above 9.5 and address Bandit and Flake8 findings.
5. Answer the lab reflection questions.
6. Make three commits documenting fixes related to Pylint, Bandit, and Flake8.

## Expected deliverables
- Cleaned-up Python script
- Issue table (for example, `ISSUES.md`)
- Before/after reports for Pylint, Bandit, and Flake8
- Reflection answers
- Three meaningful commits

> Note: The original lab handout asks you to download a Python script from the repository assigned to you. That script has not been provided in this chat yet, so the code fixes and real analysis reports cannot be produced until the assigned `.py` file is available.
