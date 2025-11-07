# 👋 Hi, I’m Vivek Saraswat

🎓 Final-year B.Tech (CSE) • AI · ML · Data Analytics · Full-stack Software Development  
I build practical ML systems, data dashboards, and backend services — learning by shipping.

---

<!-- Badges (replace or remove any you don't want) -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saraswat-vivek)
[![Email](https://img.shields.io/badge/Email-viveksaraswat49@gmail.com-red?logo=gmail&logoColor=white)](mailto:viveksaraswat49@gmail.com)
[![Python](https://img.shields.io/badge/Python-%2314354C.svg?logo=python&logoColor=white)](#)
[![FastAPI](https://img.shields.io/badge/FastAPI-%2300ABD1.svg?logo=fastapi&logoColor=white)](#)
[![Django](https://img.shields.io/badge/Django-%23092E20.svg?logo=django&logoColor=white)](#)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%230073B3.svg?logo=postgresql&logoColor=white)](#)
[![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?logo=mongodb&logoColor=white)](#)
[![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?logo=streamlit&logoColor=white)](#)

---

## 🔧 What I build
- End-to-end ML systems: data ingestion → model → API → UI  
- Data analytics & dashboards (Power BI / Tableau / Streamlit)  
- Robust backends & APIs using **FastAPI** and **Django**, with databases (Postgres, MongoDB) and ORMs (SQLAlchemy, Django ORM)  
- Real-time features with **WebSockets** (FastAPI/Starlette) and async patterns

---

## 🛠 Core Tech Stack

**Languages:** Python · SQL · JavaScript  
**Backend / APIs:** FastAPI · Django · Django REST Framework · REST · GraphQL (intro)  
**ORM / DB Tools:** SQLAlchemy · Alembic (migrations) · Django ORM · Pydantic  
**Databases:** PostgreSQL · MongoDB  
**Real-time & Asynchronous:** WebSockets · asyncio · uvicorn · Celery (task queues)  
**Dev & Ops:** Docker · Git · GitHub Actions (CI) · Nginx · systemd  
**Frontend / Visualization:** React.js · Streamlit · Power BI · Tableau

---

## 🌟 Featured Projects (backend-focused)

> Replace `REPO_URL` placeholders with your real repo links and add metrics (accuracy, users, requests/sec) where available.

### 1. Inventory & POS System — *Fullstack (Streamlit UI + FastAPI backend)*  
**Stack:** Streamlit frontend · **FastAPI** backend · SQLAlchemy · **PostgreSQL** · Docker · JWT auth  
**Highlights:**  
- REST API for products, billing, stock management  
- Role-based auth (admin / cashier) and PDF invoice generation  
- DB migrations with Alembic; CI using GitHub Actions  
**Repo:** `https://github.com/viveksaraswat123/inventory-pos-system`  
**Why this backend?** FastAPI gives fast dev iteration + async endpoints for concurrent billing updates.

---

### 2. Spam SMS Classifier — *Model + Serving*  
**Stack:** Python (scikit-learn) · **FastAPI** serving · Docker · SQLite/Postgres (metadata)  
**Highlights:**  
- Trained Naive-Bayes model with preprocessing pipeline saved as pickle  
- Production endpoint `/predict` with Pydantic validation and input sanitization  
**Repo:** `https://github.com/viveksaraswat123/spam-sms-classifier`  
**Why this backend?** Simple, lightweight model serving with FastAPI and validated inputs.

---

### 3. Bollywood Movie Recommender — *API + Frontend*  
**Stack:** Collaborative filtering (pandas + scikit-learn) · **Django REST Framework** API · React frontend · **PostgreSQL**  
**Highlights:**  
- Recommendation endpoints (user → movie suggestions) and rating ingestion API  
- Background job to recompute similarity matrices (Celery + Redis)  
**Repo:** `https://github.com/viveksaraswat123/bollywood-recommender`  
**Why Django?** Useful for a full MVC app with admin panel, auth, and rapid API scaffolding.

---

### 4. Hospital Patient Analytics Dashboard — *Data pipeline + Dashboard*  
**Stack:** ETL (pandas) → **PostgreSQL** warehousing → Power BI / Streamlit dashboard · FastAPI for lightweight query APIs  
**Highlights:**  
- ETL jobs to clean 2019–2024 patient records, computed KPIs, and scheduled refresh jobs  
- Streamlit app for quick ad-hoc analytics; Power BI report for stakeholders  
**Repo:** `https://github.com/viveksaraswat123/hospital-patient-analytics`  
**Why this backend?** FastAPI provides data endpoints for dashboards and streamlines scheduled data refresh.

---

### 5. Real-time IoT Accidental Alert System — *Realtime backend*  
**Stack:** **FastAPI** (WebSockets) · MongoDB (time-series/events) · Docker · MQTT integration  
**Highlights:**  
- Real-time WebSocket channel for alerts and a REST API to log events  
- Stores incident logs in MongoDB for quick writes and retrieval  
**Repo:** `https://github.com/viveksaraswat123/iot-accident-alert`  
**Why this backend?** FastAPI + WebSockets for low-latency real-time communication; MongoDB for flexible event storage.

---

## ✅ How I structure backend projects (best practices I follow)
- Use Pydantic models for request/response validation (FastAPI).  
- Keep clear separation: routers, services, schemas, models, db (for FastAPI).  
- Use SQLAlchemy + Alembic for migrations and typed models; use Django ORM when starting with full web apps.  
- Containerize with Docker; run CI checks (lint, tests) on PRs.  
- Add health endpoints (`/health`, `/metrics`) for observability.

---

## 📈 Roadmap / What I’m learning next
- Productionizing model serving: model versioning, A/B testing, monitoring (Prometheus/Grafana).  
- Advanced backend topics: distributed task queues, message brokers, async DB drivers.  
- Contribute to open source backend/ML infra projects.

---

## 🤝 Let’s collaborate / Contact
- LinkedIn: https://www.linkedin.com/in/saraswat-vivek  
- Email: viveksaraswat49@gmail.com  
- GitHub: https://github.com/viveksaraswat123

---
