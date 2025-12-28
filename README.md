# RotaMe

RotaMe is a work-in-progress backend service that automatically generates
weekly staff rotas based on availability and demand.

This project is inspired by real-world experience working in a cinema,
where weekly rotas were created manually and sometimes failed to meet operational demands and/or were susceptible to human errors.

---

## 🎯 Project Goal

- Generate a weekly rota automatically
- Account for higher demand on weekends
- Reduce manual effort for managers
- Serve as a foundation for a scalable, cloud-deployed scheduling system

---

## 🧱 Current Status (MVP – In Progress)

✅ FastAPI backend set up  
✅ API documentation via Swagger  
⏳ Staff and availability logic (next)  
⏳ Rota generation rules  
⏳ Cloud deployment (AWS)

---

## 🛠 Tech Stack

- Python
- FastAPI
- Uvicorn
- (Planned) SQLite / PostgreSQL
- (Planned) AWS

---

## 🚀 Running Locally

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

Then open:
- http://127.0.0.1:8000
- http://127.0.0.1:8000/docs

## 🧠 Why This Project Exists

This project is being built to be used as an internal tool to aid in weekly operations as well as a learning-focused, real-world system to
demonstrate backend development, scheduling logic, and cloud deployment.

It is intentionally developed in small, incremental steps.

