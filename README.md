# 📦 Modular Monorepo

A modular backend/frontend architecture using:
- **FastAPI** (Python)
- **MongoDB**
- **TailwindCSS**
- **Vite**
- Folder-per-domain (DDD-style)

## ⚙️ Highlights
- Auth + user management
- Domain separation: `/users`, `/products`, `/orders`
- Swagger + OpenAPI docs
- Tailwind UI components
- Simple monorepo structure (apps + libs)

## 🧰 Tech Stack
- FastAPI
- MongoDB
- TailwindCSS
- Vite + React 19
- Pytest

## 🚀 Start
```bash
cd backend && poetry install && uvicorn main:app
cd frontend && yarn install && yarn dev
Designed for clarity, reusability and fast iteration ⚡
