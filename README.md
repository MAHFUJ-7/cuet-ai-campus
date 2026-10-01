# Smart University Event and Routine Manager

An intelligent academic operations and routine management platform built for Chittagong University of Engineering and Technology (CUET).

## 🚀 Overview

Smart University Event and Routine Manager (CUET UniTrack) streamlines campus scheduling, academic coordination, real-time class announcements, routine tracking, and conflict resolution across students, Class Representatives (CRs), and department coordinators.

---

## 👥 Contributors & Core Roles

- **Mahfuj** ([@MAHFUJ-7](https://github.com/MAHFUJ-7) • `u2204037@student.cuet.ac.bd`)  
  *Project Lead, Shared Architecture, Authentication Infrastructure, CR Module & Core API Integration.*
- **Tahsin** ([@Iftear-Ahmed](https://github.com/Iftear-Ahmed) • `u2204041@student.cuet.ac.bd`)  
  *Student Module, Academic Routine Viewing, Upcoming Events, Student Dashboard & UI Polish.*
- **Nishat** ([@abdullanishat](https://github.com/abdullanishat) • `md.abdullaalnishat1051@gmail.com`)  
  *Coordinator Module, Section & Department Management, Routine Proposal Workflow & Quality Auditing.*

---

## 🛠️ Tech Stack

- **Backend:** Node.js (v20+ ESM), Express, MongoDB (Mongoose 8), JSON Web Tokens (JWT), Bcrypt.js, Helmet, Multer.
- **Frontend:** React 19, Vite, Tailwind CSS v4, React Router 7, Leaflet (Campus Map), PDF.js.
- **Testing:** Node.js native test runner, Supertest, MongoDB Memory Server.

---

## 📂 Project Structure

```
CUET-UniTrack/
├── cuet-ai-campus-api/          # Node.js + Express + MongoDB REST API
│   ├── src/
│   │   ├── config/              # Database and environment configurations
│   │   ├── middleware/          # JWT, Role authorization and error handling
│   │   ├── models/              # Academic, User, Routine, Schedule schemas
│   │   ├── routes/              # Modular API endpoints
│   │   ├── services/            # Section assignment, schedule serialization
│   │   └── utils/               # Validation, HTTP helpers, date formatters
│   └── tests/                   # Integration and unit test suite
├── cuet-ai-campus-web/          # React 19 Single Page Application
│   ├── src/
│   │   ├── components/          # Reusable UI component library & Shell Layout
│   │   ├── context/             # Auth, Theme, and Toast contexts
│   │   ├── features/
│   │   │   ├── auth/            # Sign-in, Sign-up, Password recovery
│   │   │   ├── home/            # Student command center
│   │   │   ├── cr/              # Class Representative dashboard & actions
│   │   │   ├── coordinator/     # Department coordinator administration
│   │   │   ├── routine/         # Daily & weekly routine explorer
│   │   │   ├── events/          # Campus events calendar
│   │   │   └── map/             # Interactive campus map
│   │   └── lib/                 # Routine calculations, offline caching, models
└── 22 Batch CSE Routine...pdf   # Baseline routine document
```

---

## ⚡ Quick Start

### 1. Backend Setup
```bash
cd cuet-ai-campus-api
npm install
cp .env.example .env
npm run dev
```

### 2. Frontend Setup
```bash
cd cuet-ai-campus-web
npm install
npm run dev
```

---

## 📄 License
This project is developed for academic and campus operations management.
