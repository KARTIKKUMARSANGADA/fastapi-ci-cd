# 🚀 FastAPI CI/CD Pipeline

A simple **FastAPI application** integrated with a **CI/CD pipeline using GitHub Actions**.
This project demonstrates how to automatically **test and validate code on every push**.

---

## 📌 Features

* ⚡ FastAPI backend
* 🧪 Automated testing using `pytest`
* 🔄 CI pipeline with GitHub Actions
* 📦 Dependency management with `requirements.txt`
* 🚀 Ready for deployment (CD can be added)

---

## 🛠️ Tech Stack

* **Backend:** FastAPI
* **Testing:** Pytest
* **CI/CD:** GitHub Actions
* **Language:** Python 3.10

---

## 📁 Project Structure

```
fastapi-ci-cd/
│
├── app/
│   ├── main.py
│   └── __init__.py
│
├── requirements.txt
├── test_main.py
└── .github/
    └── workflows/
        └── ci-cd.yml
```

---

## ⚙️ CI/CD Workflow

The pipeline runs automatically on every push to the `main` branch.

### 🔄 Steps:

1. Checkout code
2. Setup Python environment
3. Install dependencies
4. Run tests using pytest

---

## ▶️ Run Locally

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/fastapi-ci-cd.git
cd fastapi-ci-cd
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the server

```bash
uvicorn app.main:app --reload
```

### 4. Open in browser

```
http://127.0.0.1:8000
```

---

## 🧪 Run Tests

```bash
pytest
```

---

## 📸 CI Status Badge

Add this to show build status:

```md
![CI](https://github.com/KARTIKKUMARSANGADA/fastapi-ci-cd/actions/workflows/ci-cd.yml/badge.svg)
```

---

## 🚀 Future Improvements

* Add deployment (CD) using Render / AWS
* Add Docker support
* Add database integration (PostgreSQL)
* Add linting (flake8 / black)

---

## 👨‍💻 Author

**Kartikkumar Sangada**

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!
