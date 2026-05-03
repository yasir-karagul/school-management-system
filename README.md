<div align="center">

# School Management System

A full-featured web application for managing school operations — students, teachers, classes, attendance, and grades — built with a modern Next.js stack.

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)](https://www.prisma.io/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)

</div>



## Overview

School Management System is a web-based platform designed to centralize and simplify daily school administration. It provides role-based dashboards for admins, teachers, and students — covering everything from class scheduling and attendance tracking to grade management and reporting.



## Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Next.js 14 (App Router) |
| Language | TypeScript |
| Styling | Tailwind CSS |
| ORM | Prisma |
| Database | PostgreSQL |
| Deployment | Docker + Docker Compose |



## Features

- 👨‍💼 **Admin Dashboard** — manage students, teachers, classes, and subjects
- 👩‍🏫 **Teacher Dashboard** — view assigned classes, record attendance and grades
- 🎓 **Student Dashboard** — view schedule, grades, and attendance records
- 📅 **Class Scheduling** — assign teachers to classes and manage timetables
- ✅ **Attendance Tracking** — daily attendance records per class
- 📊 **Grade Management** — record and view student performance
- 🔐 **Role-Based Access Control** — separate views and permissions per role
- 🐳 **Dockerized** — ready to run in any environment



## Getting Started

### Prerequisites

- Node.js >= 18
- Docker & Docker Compose
- PostgreSQL (or use the Docker setup)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/yasir-karagul/school-management-system.git
cd school-management-system

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env
# Edit .env with your database connection string

# 4. Run database migrations
npx prisma migrate dev

# 5. Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Run with Docker

```bash
docker-compose up -d
```



## Project Structure

```
school-management-system/
├── prisma/          # Database schema & migrations
├── public/          # Static assets
├── src/
│   ├── app/         # Next.js App Router pages
│   ├── components/  # Reusable UI components
│   └── lib/         # Utilities & helpers
├── docker-compose.yml
└── tailwind.config.ts
```



## Database Schema

Managed with **Prisma ORM**. Run the following to explore the schema:

```bash
npx prisma studio
```


<div align="center">
Built with ❤️ by <a href="https://github.com/yasir-karagul">Yasir Khalid Abed</a>
</div>
