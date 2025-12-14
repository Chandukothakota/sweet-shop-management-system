# 🍬 Sweet Shop Management System

## 📌 Objective
Design, build, and test a full-stack **Sweet Shop Management System**.  
This project demonstrates skills in **API development, database management, frontend implementation, testing, and modern development workflows**, including responsible **AI-assisted coding**.

---

## 🧱 Tech Stack

### Backend
- **Node.js**
- **Express.js**
- **PostgreSQL**
- **ORM:** Prisma
- **Authentication:** JWT (User / Admin)
- **Testing:** Jest + Supertest

### Frontend
- **React.js (Vite)**
- **TypeScript**
- **Tailwind CSS / Material UI**

---

## 🔐 Authentication & Roles
- Users can **register** and **login**
- JWT-based authentication
- Role-based authorization:
  - **USER**
  - **ADMIN**

---

## 📦 Sweet Model
Each sweet contains:
- `id`
- `name`
- `category`
- `price`
- `quantity`

---

## 🚀 Backend API Endpoints

### Auth
- `POST /api/auth/register` – Register user
- `POST /api/auth/login` – Login user

### Sweets
- `POST /api/sweets` – Add sweet (**Admin only**)
- `GET /api/sweets` – List all sweets
- `GET /api/sweets/search` – Search sweets
- `PUT /api/sweets/:id` – Update sweet (**Admin only**)
- `DELETE /api/sweets/:id` – Delete sweet (**Admin only**)

### Inventory
- `POST /api/sweets/:id/purchase` – Purchase sweet
- `POST /api/sweets/:id/restock` – Restock sweet (**Admin only**)

---

## 🖥️ Frontend Features
- User registration & login
- Dashboard displaying sweets
- Search & filter sweets
- Purchase button (disabled when out of stock)
- Admin panel to add, update, and delete sweets
- Responsive and modern UI

---

## ⚙️ Setup Instructions

### Backend Setup
```bash
cd backend
npm install
npm run dev
