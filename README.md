# Hyumane

Welcome to the Hyumane codebase&#x20;

---

## 📖 Table of Contents

1. [About](#-about)
2. [Tech Stack](#-tech-stack)
3. [Features](#-features)
4. [Getting Started](#-getting-started)

   * [Prerequisites](#prerequisites)
   * [Installation](#installation)
   * [Environment Variables](#environment-variables)
   * [Database Setup](#database-setup)
5. [Available Scripts](#-available-scripts)
6. [API Endpoints](#-api-endpoints)
7. [Project Structure](#-project-structure)
8. [Deployment](#-deployment)
9. [Contact](#-contact)
   [Contact](#-contact)

---

## 🔥 About

Hyumane is a streetwear brand, and this Next.js + Express + Prisma project showcases modern web development techniques. This repository serves as a personal showcase of my process and skills—feel free to explore how I architected, built, and deployed each component end-to-end.

## 🛠 Tech Stack

* **Frontend**: Next.js (React) + TypeScript + Tailwind CSS
* **Backend**: Express.js + TypeScript + Prisma ORM (SQLite for dev, Postgres for prod)
* **Deployment**: Vercel (frontend), Heroku/Render (backend)
* **CI/CD**: GitHub Actions for linting, testing & migrations
* **Other**: Framer Motion (animations), Stripe (payments), Docker&#x20;

## ✨ Features

* File-based routing & SSR/SSG with Next.js
* RESTful API routes under `/api/*`
* Full CRUD for products (create, read, update, delete)
* Tailwind-driven design system & responsive layout
* Image optimization via Next/Image
* JWT or API-key-based auth (coming soon)
* Unit & integration tests (Jest + React Testing Library + Supertest)
* Automated deployments & preview environments


## 🔌 API Endpoints

| Method | Route               | Description              |
| ------ | ------------------- | ------------------------ |
| GET    | `/api/products`     | List all products        |
| GET    | `/api/products/:id` | Get single product by ID |
| POST   | `/api/products`     | Create a new product     |
| PUT    | `/api/products/:id` | Update product by ID     |
| DELETE | `/api/products/:id` | Delete product by ID     |


## 📁 Project Structure

```
hyumane-site/
├── backend/
│   ├── src/
│   │   ├── index.ts       # Express entrypoint
│   │   ├── routes/        # Route handlers
│   │   └── prisma/        # Prisma client & migrations
│   └── prisma/            # Schema & migrations
├── frontend/
│   ├── pages/             # Next.js pages
│   ├── components/        # Reusable UI components
│   ├── styles/            # Tailwind & globals
│   └── public/            # Static assets
├── .github/               # CI workflows
└── README.md
```

## 📬 Contact

* **Your Name** (Ethan James Lim)
* Email: [ethanjameslimtianwen@gmail.com](mailto:ethanjameslimtianwen@gmail.com)

---
