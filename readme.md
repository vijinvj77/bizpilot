# 🚀 BizPilot – AI Powered Business Operations OS

🔗 Repository: https://github.com/vijinvj77/bizpilot

BizPilot is a modern, AI-powered SaaS platform designed to help businesses manage operations in a single unified system. It combines CRM, task management, invoicing, workflow automation, and an AI assistant.

This project is built to demonstrate **production-level full-stack architecture** using Laravel and Angular.

---

## 🧠 Key Features

### 🏢 Multi-Tenant SaaS

* Company-based data isolation
* Role-based access control (RBAC)
* Scalable architecture for multiple organizations

### 📊 Dashboard & Analytics

* KPI cards (Revenue, Tasks, Leads)
* Interactive charts
* AI-generated insights

### 📇 CRM

* Lead management
* Customer tracking
* Status pipelines

### ✅ Task Management

* Task list and Kanban board
* Assign users, priorities, deadlines

### 💰 Invoicing

* Invoice creation and tracking
* Payment status management

### ⚙️ Automation Engine

* Rule-based workflows (IF → THEN)
* Event-driven processing

### 🤖 AI Assistant

* Chat-based business insights
* Smart summaries and reports

---

## 🏗️ Tech Stack

### Backend

* Laravel (API-first architecture)
* MySQL
* Redis (planned)

### Frontend

* Angular 20 (Standalone Components)
* Signals-based state management

### DevOps (Planned)

* Docker
* CI/CD pipelines

---

## 📁 Project Structure

```id="zjjzq6"
bizpilot/
 ├── backend/    # Laravel API
 ├── frontend/   # Angular App
 └── README.md
```

---

### 📦 Backend Structure (Laravel)

```id="n4yr96"
backend/
 ├── app/
 │    ├── Modules/
 │    │    ├── Auth/
 │    │    ├── CRM/
 │    │    ├── Task/
 │    │    ├── Invoice/
 │    │    ├── Automation/
 │    │    ├── AI/
 │    │
 │    ├── Services/
 │    ├── Repositories/
 │    ├── Jobs/
 │    ├── Events/
 │
 ├── routes/
 ├── database/
```

---

### 🅰️ Frontend Structure (Angular)

```id="0n4sd6"
frontend/
 ├── src/app/
 │    ├── core/
 │    ├── shared/
 │    ├── features/
 │    ├── layout/
 │    ├── app.routes.ts
 │    └── app.config.ts
```

---

## 🔌 API Endpoints

```id="4thp3q"
/api/v1/

Auth:
POST   /auth/login
POST   /auth/register

CRM:
GET    /leads
POST   /leads

Tasks:
GET    /tasks
POST   /tasks

AI:
POST   /ai/query

Automation:
POST   /rules
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash id="a7ojqi"
git clone https://github.com/vijinvj77/bizpilot.git
cd bizpilot
```

---

## 🔧 Backend Setup (Laravel)

```bash id="9nqg45"
cd backend
composer install
cp .env.example .env
php artisan key:generate
```

Update `.env` with your DB credentials, then:

```bash id="r9q8sm"
php artisan migrate
php artisan serve
```

Backend runs at:
👉 http://localhost:8000

---

## 🅰️ Frontend Setup (Angular)

```bash id="0w5kk2"
cd frontend
npm install
ng serve
```

Frontend runs at:
👉 http://localhost:4200

---

## 🔐 Authentication Flow

* Token-based authentication
* Angular interceptor attaches token
* Route guards protect private routes

---

## 🧠 Architecture Highlights

* Feature-based Angular architecture
* Modular Laravel backend (domain-driven)
* Service + Repository pattern
* Event-driven automation system
* AI integration layer

---

## 🚀 Future Enhancements

* Real-time updates (WebSockets)
* Payment integration (Stripe/Razorpay)
* Advanced AI analytics
* Plugin system
* PWA support

---

## 👨‍💻 Author

**Vijin V J**
📧 [vijinvj77@gmail.com](mailto:vijinvj77@gmail.com)
📱 +91 9747052235

---

## ⭐ Contribution

Feel free to fork, raise issues, or contribute.

---

## 📄 License

For educational and portfolio use.
