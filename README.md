# CI/CD Automation Pipeline Simulation


## Project Overview

This project simulates a **CI/CD (Continuous Integration and Continuous Deployment)** pipeline using **GitHub Actions**.

It automatically:

- Runs unit tests with **pytest**
- Checks code quality with **flake8**
- Measures test coverage
- Performs a **simulated deployment** once all checks pass

---

## Features

- Automated build validation
- Unit testing of Python components
- Code linting and style enforcement
- Continuous Integration workflow using GitHub Actions
- Simulated deployment stage for demonstration

---

## Tech Stack

- **Language:** Python 3.10
- **Tools:** GitHub Actions, pytest, flake8
- **CI/CD:** Workflow automation on every push or pull request

---

## How to Run Locally

```bash
# 1. Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run tests manually
pytest
```
