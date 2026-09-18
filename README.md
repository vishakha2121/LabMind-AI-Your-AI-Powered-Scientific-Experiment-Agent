<div align="center">

# 🧪 LabMind AI

### Your AI-Powered Scientific Experiment Agent

**Plan. Execute. Analyze. Discover.**

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev)
[![SQLite](https://img.shields.io/badge/SQLite-3-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)]()

<br/>

> **Turn a simple research question into a complete experiment workflow — with AI-powered planning, tracking, analysis, and future research suggestions.**

<br/>

[Features](#-features) • [Demo](#-demo) • [Tech Stack](#-tech-stack) • [Installation](#-installation) • [API Docs](#-api-endpoints) • [Screenshots](#-screenshots)

</div>

---

## 📖 Table of Contents

- [About The Project](#-about-the-project)
- [The Problem](#-the-problem)
- [The Solution](#-the-solution)
- [How It Works](#-how-it-works)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Environment Variables](#-environment-variables)
- [API Endpoints](#-api-endpoints)
- [Database Schema](#-database-schema)
- [Screenshots](#-screenshots)
- [Comparison](#-comparison)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 🧪 About The Project

**LabMind AI** is a full-stack, AI-powered scientific experiment agent that transforms the traditionally fragmented process of scientific experimentation into a streamlined, intelligent, and connected workflow — all within a single, modern web application.

At its core, LabMind AI answers a powerful question:

> *"What if your research assistant could plan your experiment, track every step, analyze your results, and tell you what to do next — automatically?"*

By combining the reasoning capabilities of **Large Language Models (Google Gemini)** with a **dynamic Knowledge Graph (NetworkX)**, LabMind AI creates a living research environment where every experiment, result, and insight is connected, searchable, and actionable.

Built with **FastAPI**, **React**, **SQLite**, and **Google Gemini**, it runs smoothly on **any CPU-based laptop** — no GPU, no cloud credits, no paid subscriptions required.

---

## ❗ The Problem

Scientific research — especially at the student, academic, and small-lab level — is plagued by fragmentation:

- 📓 **Experiment plans** live in scattered notebooks, Word docs, or memory
- 📊 **Results** are stored in Excel sheets, lab journals, or lost entirely
- 🔗 **Connections** between past experiments and current work are forgotten
- 🤔 **Next steps** are guesswork, based on intuition rather than data
- 💸 **Enterprise lab software** (LIMS, ELN) costs thousands of dollars
- 🖥️ **AI research tools** often require GPUs, paid APIs, or cloud credits

**Result:** Wasted time, repeated mistakes, missed insights, and slow research progress.

---

## 💡 The Solution

LabMind AI solves every one of these problems with an elegant, accessible, and intelligent approach:

| Problem | LabMind AI Solution |
|---------|---------------------|
| Manual experiment planning | AI generates structured protocols in seconds |
| Scattered result tracking | Centralized SQLite DB with structured schema |
| Lost cross-experiment insights | Knowledge Graph links concepts automatically |
| Guesswork for next steps | AI suggests future directions from data |
| Expensive lab software | 100% free, open-source, self-hosted |
| GPU/cloud requirements | Runs on any CPU laptop, free Gemini tier |

---

## 🔬 How It Works

**Step 1 — Ask a Research Question**
> *"Does green tea extract inhibit bacterial growth?"*

**Step 2 — AI Generates an Experiment Plan**
Gemini returns: hypothesis, variables, materials, procedure, duration, safety notes.

**Step 3 — Workflow Created Automatically**
Each step becomes a trackable task with status, notes, and time tracking.

**Step 4 — Execute & Record Results**
User logs observations, measurements, and notes as the experiment progresses.

**Step 5 — AI Analyzes Results**
Gemini reviews results and provides interpretation, statistics, and improvement suggestions.

**Step 6 — Knowledge Graph Updates**
Concepts, methods, and findings are auto-linked into a visual graph.

**Step 7 — AI Suggests Next Research Directions**
Based on everything so far, LabMind AI recommends follow-up experiments.

---

## ✨ Features

### 🤖 1. AI Experiment Planner
- Natural language input → structured protocol
- Powered by Google Gemini API
- Context-aware (uses past experiments)
- Domain-agnostic (biology, chemistry, physics, CS, etc.)

### 📋 2. Workflow Manager
- Drag-and-drop step ordering
- Real-time status updates
- Progress bars & completion %
- Deadline tracking

### 📊 3. Result Tracker & Visualizer
- Structured data entry (numeric, text, categorical)
- Auto-generated charts (line, bar, scatter)
- Comparison across experiments
- Export to CSV / JSON

### 🕸️ 4. Dynamic Knowledge Graph
- Built with NetworkX
- Nodes = concepts, methods, materials, findings
- Edges = relationships (uses, causes, supports)
- Interactive visualization
- Grows automatically with each experiment

### 🔮 5. AI Research Suggester
- Analyzes past experiments
- Suggests next steps with confidence scores
- Explains reasoning
- Links to relevant past work

### 🎨 6. Modern, Attractive UI
- Dark theme with gradient accents
- Glassmorphism cards
- Smooth animations (Framer Motion)
- Fully responsive design

### 📈 7. Analytics Dashboard
- Total experiments & steps
- Success rate
- Time invested
- Most-used concepts
- Activity timeline

### 🔐 8. Data Ownership
- All data stored locally (SQLite)
- No third-party sharing
- Export/backup anytime
- Open-source

---

## 🛠️ Tech Stack

### 🎨 Frontend
| Tech | Purpose |
|------|---------|
| React 18 | Component-based UI |
| Vite | Lightning-fast build tool |
| TailwindCSS | Utility-first styling |
| Framer Motion | Smooth animations |
| Recharts | Data visualization |
| React Router | Client-side routing |
| Axios | API communication |
| React Context API | State management |

### ⚙️ Backend
| Tech | Purpose |
|------|---------|
| Python 3.10+ | Core language |
| FastAPI | Async web framework |
| SQLAlchemy | ORM |
| Pydantic | Data validation |
| Uvicorn | ASGI server |
| Alembic | DB migrations |

### 🧠 AI / ML
| Tech | Purpose |
|------|---------|
| Google Gemini API | LLM for planning, analysis, suggestions |
| google-generativeai | Python SDK |
| NetworkX | Knowledge Graph construction |

### 💾 Database
| Tech | Purpose |
|------|---------|
| SQLite | Lightweight file-based DB |

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                     FRONTEND (React + Vite)                 │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐   │
│  │Dashboard │  │Experiments│ │Knowledge │  │AI Suggest│   │
│  └────┬─────┘  └────┬─────┘  └────┬─────┘  └────┬─────┘   │
│       │             │             │             │           │
│       └─────────────┴──────┬──────┴─────────────┘           │
│                            │ Axios                          │
└────────────────────────────┼────────────────────────────────┘
                             │ REST API
┌────────────────────────────┼────────────────────────────────┐
│                     BACKEND (FastAPI)                       │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐   │
│  │ Routes   │→ │ Services │→ │ Models   │→ │ Schemas  │   │
│  └──────────┘  └────┬─────┘  └────┬─────┘  └──────────┘   │
│                     │             │                         │
│              ┌──────┴──────┐  ┌───┴────────┐               │
│              │ Gemini Svc  │  │  SQLite    │               │
│              │ NetworkX    │  │  Database  │               │
│              └─────────────┘  └────────────┘               │
└─────────────────────────────────────────────────────────────┘
```

---

## 📁 Project Structure

```
labmind-ai/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── config.py
│   │   ├── database.py
│   │   ├── models/
│   │   ├── schemas/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── ai/
│   │   ├── knowledge_graph/
│   │   └── utils/
│   ├── data/app.db
│   ├── requirements.txt
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── api/
│   │   ├── context/
│   │   └── styles/
│   ├── package.json
│   └── vite.config.js
│
└── docs/
    └── screenshots/
```

---

## 🚀 Installation

### 📋 Prerequisites

Before you begin, ensure you have:

- ✅ **Python 3.10+** → [Download](https://python.org/downloads)
- ✅ **Node.js 18+** → [Download](https://nodejs.org)
- ✅ **Git** → [Download](https://git-scm.com)
- ✅ **Google Gemini API Key** → [Get Free Key](https://aistudio.google.com/app/apikey)

---

### 🔹 Step 1: Clone the Repository

```bash
git clone https://github.com/vishakha2121/LabMind-AI-Your-AI-Powered-Scientific-Experiment-Agent.git
cd LabMind-AI-Your-AI-Powered-Scientific-Experiment-Agent
```

---

### 🔹 Step 2: Backend Setup

```bash
# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

### 🔹 Step 3: Configure Environment Variables

Create a `.env` file inside the `backend/` folder:

```env
GEMINI_API_KEY=your_gemini_api_key_here
DATABASE_URL=sqlite:///./data/app.db
SECRET_KEY=your_secret_key_here
DEBUG=True
```

> ⚠️ **Never commit your `.env` file to GitHub!**

---

### 🔹 Step 4: Run the Backend

```bash
uvicorn app.main:app --reload --port 8000
```

Backend will run at → `http://localhost:8000`

API docs will be available at → `http://localhost:8000/docs`

---

### 🔹 Step 5: Frontend Setup

Open a **new terminal**:

```bash
# Navigate to frontend
cd frontend

# Install dependencies
npm install
```

---

### 🔹 Step 6: Configure Frontend Environment

Create a `.env` file inside the `frontend/` folder:

```env
VITE_API_URL=http://localhost:8000/api
```

---

### 🔹 Step 7: Run the Frontend

```bash
npm run dev
```

Frontend will run at → `http://localhost:5173`

---

### 🎉 Done!

Open `http://localhost:5173` in your browser and start experimenting!

---

## 🔐 Environment Variables

### Backend (`backend/.env`)

| Variable | Description | Required |
|----------|-------------|----------|
| `GEMINI_API_KEY` | Google Gemini API key | ✅ Yes |
| `DATABASE_URL` | SQLite database path | ✅ Yes |
| `SECRET_KEY` | Secret key for tokens | ✅ Yes |
| `DEBUG` | Debug mode (True/False) | Optional |

### Frontend (`frontend/.env`)

| Variable | Description | Required |
|----------|-------------|----------|
| `VITE_API_URL` | Backend API base URL | ✅ Yes |

---

## 🔌 API Endpoints

### 🧪 Experiments

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/experiments` | Get all experiments |
| `GET` | `/api/experiments/{id}` | Get single experiment |
| `POST` | `/api/experiments` | Create experiment |
| `POST` | `/api/experiments/plan` | AI-generate experiment plan |
| `PUT` | `/api/experiments/{id}` | Update experiment |
| `DELETE` | `/api/experiments/{id}` | Delete experiment |

### 📋 Steps

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/experiments/{id}/steps` | Get all steps |
| `POST` | `/api/experiments/{id}/steps` | Add step |
| `PUT` | `/api/steps/{id}` | Update step |
| `DELETE` | `/api/steps/{id}` | Delete step |

### 📊 Results

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/results` | Get all results |
| `POST` | `/api/results` | Add result |
| `GET` | `/api/results/{experiment_id}` | Results by experiment |

### 🕸️ Knowledge Graph

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/knowledge/graph` | Get full graph |
| `GET` | `/api/knowledge/nodes` | Get all nodes |
| `POST` | `/api/knowledge/nodes` | Add node |
| `GET` | `/api/knowledge/search?q=` | Search concepts |

### 🤖 AI

| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api/ai/plan` | Generate experiment plan |
| `POST` | `/api/ai/analyze` | Analyze results |
| `POST` | `/api/ai/suggest` | Suggest future directions |

### 📈 Dashboard

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/dashboard/stats` | Get dashboard statistics |

---

## 💾 Database Schema

### `experiments`
| Column | Type | Description |
|--------|------|-------------|
| id | INTEGER | Primary key |
| title | TEXT | Experiment title |
| description | TEXT | Description |
| domain | TEXT | Science domain |
| status | TEXT | Active/Completed |
| created_at | DATETIME | Timestamp |

### `steps`
| Column | Type | Description |
|--------|------|-------------|
| id | INTEGER | Primary key |
| experiment_id | INTEGER | Foreign key |
| step_order | INTEGER | Step number |
| title | TEXT | Step title |
| description | TEXT | Details |
| status | TEXT | Pending/In Progress/Completed |

### `results`
| Column | Type | Description |
|--------|------|-------------|
| id | INTEGER | Primary key |
| step_id | INTEGER | Foreign key |
| data | JSON | Result data |
| notes | TEXT | Observations |
| created_at | DATETIME | Timestamp |

### `knowledge_nodes`
| Column | Type | Description |
|--------|------|-------------|
| id | INTEGER | Primary key |
| label | TEXT | Concept name |
| type | TEXT | Concept/Method/Material |
| description | TEXT | Details |

### `knowledge_edges`
| Column | Type | Description |
|--------|------|-------------|
| id | INTEGER | Primary key |
| source_id | INTEGER | Source node |
| target_id | INTEGER | Target node |
| relation | TEXT | Relationship type |

### `ai_suggestions`
| Column | Type | Description |
|--------|------|-------------|
| id | INTEGER | Primary key |
| experiment_id | INTEGER | Foreign key |
| suggestion | TEXT | AI suggestion |
| confidence | FLOAT | Confidence score |
| created_at | DATETIME | Timestamp |

---

## 📸 Screenshots

### 🏠 Dashboard
![Dashboard](docs/screenshots/dashboard.png)

### 🧪 Experiment Detail
![Experiment Detail](docs/screenshots/experiment-detail.png)

### 🕸️ Knowledge Graph
![Knowledge Graph](docs/screenshots/knowledge-graph.png)

### 🔮 AI Suggestions
![AI Suggestions](docs/screenshots/ai-suggestions.png)

> 📌 **Note:** Add your own screenshots in `docs/screenshots/` folder.

---

## ⚔️ Comparison

| Feature | LabMind AI | ELN/LIMS | ChatGPT | Notion |
|---------|-----------|----------|---------|--------|
| AI experiment planning | ✅ | ❌ | ⚠️ Manual | ❌ |
| Persistent experiment data | ✅ | ✅ | ❌ | ✅ |
| Knowledge Graph | ✅ | ⚠️ Rare | ❌ | ❌ |
| AI next-step suggestions | ✅ | ❌ | ⚠️ Manual | ❌ |
| Free & open-source | ✅ | ❌ | ⚠️ Freemium | ⚠️ Freemium |
| Runs on CPU | ✅ | ⚠️ Cloud | ✅ | ✅ |
| Structured schema | ✅ | ✅ | ❌ | ❌ |
| Result visualization | ✅ | ✅ | ⚠️ Limited | ⚠️ Limited |
| Learning curve | Low | High | Low | Medium |

---

## 🗺️ Roadmap

- [x] Project setup & architecture
- [x] Backend API (FastAPI + SQLite)
- [x] Gemini AI integration
- [x] Knowledge Graph (NetworkX)
- [x] React frontend with TailwindCSS
- [x] Dashboard & analytics
- [ ] User authentication
- [ ] Cloud sync (optional)
- [ ] Mobile app (React Native)
- [ ] Collaboration features
- [ ] PubMed / arXiv integration
- [ ] Voice input for hands-free logging

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit** your changes
   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. **Push** to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open** a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 👩‍💻 Author

**Vishakha**

- 🐙 GitHub: [@vishakha2121](https://github.com/vishakha2121)
- 📧 Email: your-email@example.com

---

## 🙏 Acknowledgements

- [Google Gemini API](https://ai.google.dev) — for LLM capabilities
- [FastAPI](https://fastapi.tiangolo.com) — for the backend framework
- [React](https://react.dev) — for the frontend
- [TailwindCSS](https://tailwindcss.com) — for styling
- [NetworkX](https://networkx.org) — for Knowledge Graph
- [Recharts](https://recharts.org) — for data visualization

---

<div align="center">

### ⭐ If you found this project helpful, please give it a star!

**Made with ❤️ by Vishakha**

**Plan. Execute. Analyze. Discover.**

</div>