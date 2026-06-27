# 💪 AQWA – "Strong" Gym Management System

A full-stack gym management platform built to help gym staff manage members, subscriptions, offers, and progress tracking from one clean dashboard.

> AQWA  in Arabic means stronger in English, which is what this platform is getting in each update! 💪

---

## 🏋️ About the Project

Aqwa is a bilingual (Arabic & English) gym management platform designed for small and medium-sized gyms. The system enables staff to manage memberships, monitor subscription status, track body measurements, and handle day-to-day operations through a modern web application.

This repository serves as a central overview of the project and its architecture. The source code is split into separate repositories:

- 🚀 **Frontend:** https://github.com/Janaherself/aqwa-frontend
- ⚙️ **Backend:** https://github.com/Janaherself/aqwa-backend

---

## 🗂️ Repository Structure

```
aqwa/
├── README.md          # Project overview and documentation
└── docs/              # Optional screenshots, diagrams, and assets
```

---

## 🔗 Project Repositories

| Repository | Description |
|------------|-------------|
| [aqwa-frontend](https://github.com/Janaherself/aqwa-frontend) | React + TypeScript single-page application |
| [aqwa-backend](https://github.com/Janaherself/aqwa-backend) | ASP.NET Core Web API following Clean Architecture |

Each repository contains its own setup instructions, development workflow, and implementation details.

---

## ⚡ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript, Vite, Tailwind CSS |
| State & Data | TanStack Query, Zustand |
| Routing | React Router |
| Internationalization | react-i18next |
| Backend | ASP.NET Core, C# |
| Architecture | Clean Architecture (Onion) |
| Database | PostgreSQL |
| ORM | Entity Framework Core |

---

## 🏆 Features

- **Member Management** — Add, view, and manage gym members.
- **Subscription Plans & Offers** — Flexible plan and offer management with expiry tracking.
- **Body Measurements** — Monitor member progress over time.
- **Dashboard** — Surface important information and upcoming expirations.
- **Staff Management** — Role-based management of gym staff.
- **Bilingual Experience** — Full Arabic (RTL) and English support.
- **Light & Dark Themes** — User-selectable themes.
- **Multi-tenant Ready** — Data model designed to support multiple gyms in the future.

---

## 🏗️ Architecture

The backend follows the principles of **Clean Architecture**, separating business logic from infrastructure concerns and keeping dependencies flowing inward.

```text
┌──────────────────────────────────────────┐
│                   API                    │
├──────────────────────────────────────────┤
│              Application                 │
├──────────────────────────────────────────┤
│             Infrastructure               │
├──────────────────────────────────────────┤
│                 Domain                   │
└──────────────────────────────────────────┘
```

The frontend consumes the API through a dedicated service layer and uses modern React patterns for state management and data fetching.

---

## 🚀 Getting Started

To run the application locally:

1. Clone the backend repository and follow its setup instructions.
2. Clone the frontend repository and follow its setup instructions.
3. Configure the frontend to communicate with your backend instance using the environment variables documented in each repository.

- Backend setup: https://github.com/Janaherself/aqwa-backend
- Frontend setup: https://github.com/Janaherself/aqwa-frontend

---

## 🌍 Internationalization

Aqwa supports both **Arabic (RTL)** and **English (LTR)**, with layout direction and translations switching seamlessly at runtime.

---

## 🤝 Contributing

This project is under active development. Check the individual sub-project READMEs for detailed setup and contribution notes.

---

*Built with sweat, clean code, and a lot of ☕ — because even software needs to stay in shape.*
