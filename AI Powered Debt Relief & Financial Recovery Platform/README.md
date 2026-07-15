# 🤝 AI Powered Debt Relief & Financial Recovery Platform

An AI-powered financial recovery platform that helps users manage debt obligations, analyze financial health, predict settlement outcomes, and generate professional negotiation letters.

Built using FastAPI, React, SQLModel, and SQLite.

---

## 📌 Features

- 🔐 User authentication and registration
- 📊 Financial health analysis based on income, expenses, debt, and savings
- 🏦 Loan tracking and management
- 💡 Settlement prediction for overdue accounts
- 📝 AI-generated negotiation letters for creditors
- 📚 History tracking for settlements and generated letters
- 🧪 Backend API structure ready for testing and extension
- 🐳 Docker support for backend and frontend services

---

## 🏗️ Project Architecture

```text
User
  ↓
React Frontend
  ↓
FastAPI Backend
  ↓
Services Layer
 ├── Auth Service
 ├── Loan Management
 ├── Financial Health Analyzer
 ├── Settlement Predictor
 └── Letter Generator
  ↓
SQLite Database
```

---

## 📂 Project Structure

```text
AI Powered Debt Relief & Financial Recovery Platform/
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── database.py
│   │   ├── models.py
│   │   ├── schemas.py
│   │   ├── routers/
│   │   └── ai/
│   └── Dockerfile
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── App.jsx
│   │   ├── api.js
│   │   └── main.jsx
│   ├── package.json
│   └── Dockerfile
│
├── scripts/
├── docker-compose.yml
├── requirements.txt
└── README.md
```

---

## ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| FastAPI | Backend API development |
| React | Frontend user interface |
| SQLModel | Database models and queries |
| SQLite | Local relational database |
| JWT + bcrypt | Authentication and security |
| Docker | Containerized deployment |
| Vite | Frontend development server |

---

## 🚀 Installation

### 1. Clone Repository

```bash
git clone <repository-url>

cd "AI Powered Debt Relief & Financial Recovery Platform"
```

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

Activate environment:

Windows:

```bash
.venv\Scripts\activate
```

Linux / macOS:

```bash
source .venv/bin/activate
```

### 3. Install Backend Dependencies

```bash
pip install -r requirements.txt
```

### 4. Install Frontend Dependencies

```bash
cd frontend
npm install
cd ..
```

---

## ▶️ Run Backend

```bash
cd backend
uvicorn app.main:app --reload --port 8000
```

Backend runs at:

```text
http://127.0.0.1:8000
```

Swagger UI:

```text
http://127.0.0.1:8000/docs
```

---

## ▶️ Run Frontend

```bash
cd frontend
npm run dev
```

Frontend runs at:

```text
http://localhost:5173
```

---

## 🐳 Run with Docker

```bash
docker compose up --build
```

This will start:

- Backend on port 8000
- Frontend on port 3000

---

## 🔗 Main API Endpoints

- POST /auth/register
- POST /auth/login
- GET /loans/
- POST /loans/
- POST /analysis/financial-health
- POST /settlement/predict
- POST /settlement/letter
- GET /settlement/history

---

## 🌟 Future Enhancements

- AI-powered credit counseling recommendations
- PDF export of financial summaries
- Email integration for negotiation letters
- Advanced analytics dashboards
- Multi-user role-based access control
- Cloud deployment and production-grade hosting

---

## 👨‍💻 Project Purpose

This platform is designed to support users who want a practical and structured way to understand their financial situation, evaluate debt stress, and take informed steps toward recovery.

## 👨‍💻 Author

**Course : Google Cloud Generative AI**
**NVRCET TENALI**
**B.Tech CSE (AI & ML)**

**GUTTULA CHAITANYA SRIRAM**

Email : gchaitanyasriram991@gmail.com

Roll No : 237T1A0525

GitHub :  