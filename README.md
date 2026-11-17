# 🐾 PawRescue AI

> **AI-Powered Emergency Management Platform for Animal Welfare Operations**  
> *Goa AI Hackathon 2026 — Animal Welfare*

---

## 📌 Overview

**PawRescue AI** is an intelligent, end-to-end emergency management platform designed to streamline animal rescue operations. From citizen incident reporting to AI-assisted triage, smart rescue dispatch, veterinary care, and shelter tracking, the platform unifies all stakeholders into a single, responsive system.

---

## 🛠️ Technology Stack

| Layer | Technology |
|---|---|
| **Frontend** | React, Vite, TypeScript, Tailwind CSS, shadcn/ui |
| **Backend** | Python, FastAPI, Uvicorn |
| **Database & Platform** | Supabase (PostgreSQL + PostGIS, Auth, Storage, Realtime) |
| **AI / Computer Vision** | YOLO11n (Species Detection) + Python Rule Engine (Urgency Triage) |
| **Maps & Routing** | Leaflet, OpenStreetMap, OSRM / OpenRouteService |
| **Testing** | Pytest (Backend) & Vitest (Frontend) |
| **Version Control & CI** | Git & GitHub |

---

## 📂 Project Structure

```
pawrescue-ai/
│
├── frontend/             # React + Vite + TypeScript application (Citizen, Rescuer, Admin)
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/              # FastAPI Python backend
│   ├── app/
│   │   ├── api/          # REST API endpoints & route handlers
│   │   ├── models/       # Pydantic & database schemas
│   │   ├── services/     # Business logic & integrations
│   │   └── main.py       # FastAPI application entry point
│   └── requirements.txt
│
├── ai/                   # AI & Machine Learning pipelines
│   ├── detection/        # YOLO11n animal detection models & scripts
│   ├── prioritization/   # Urgency assessment rule engine
│   └── dispatch/         # Proximity & routing recommendation logic
│
├── database/             # Database schemas & migrations
│   └── migrations/       # Supabase / PostgreSQL SQL migrations
│
├── docs/                 # Architecture, API docs, and specifications
│
├── .gitignore
└── README.md
```

---

## 🚀 Development Roadmap

1. **Phase 1: Project Initialization & Git** *(Current)*
2. **Phase 2: Frontend Scaffolding (Citizen, Rescuer, Admin Portals)**
3. **Phase 3: Backend Setup (FastAPI & Core APIs)**
4. **Phase 4: Database Integration (Supabase + PostGIS)**
5. **Phase 5: AI Engine (YOLO11n Animal ID + Priority Rules)**
6. **Phase 6: Geospatial Routing & Smart Dispatch**
7. **Phase 7: Realtime Alerts, Testing & Deployment**

---

## 👥 User Roles

- **Citizen Portal:** Easy reporting with camera capture, GPS auto-fill, and symptom checklists.
- **Rescue Team Portal:** Live assigned cases, route calculation, status updates.
- **Admin / Dispatcher Dashboard:** Real-time incident map, AI triage review, team dispatch, and shelter oversight.
