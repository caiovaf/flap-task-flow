<div align="center">

# 📋 Flap — Task Flow & Kanban Suite

**A streamlined, responsive agile task and workflow management suite built for modern teams.**

[![React](https://img.shields.io/badge/React-18.3-61dafb?style=flat-square&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.4-646cff?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38bdf8?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

</div>

---

## 📌 Overview

**Flap** is an agile task tracking and workflow platform engineered for clarity, speed, and focus. Built with React and Tailwind CSS, it provides developers and cross-functional teams with an uncluttered interface to create, track, prioritize, and complete mission-critical deliverables.

---

## ✨ Key Features

- **⚡ Instant Task Lifecycle Management:** Create, toggle completion, inspect, and remove tasks with zero lag.
- **🧭 Dynamic Detail Routing:** Integrated multi-view navigation via `react-router-dom` to view rich task descriptions and metadata.
- **🎨 Modern Dark UI:** Engineered with Tailwind CSS and Lucide React icons for a high-contrast, distraction-free aesthetic.
- **💾 Client-Side State & Persistence:** Optimized state flow with UUID identification and instant local synchronization.
- **📱 Fully Responsive:** Clean layout across mobile devices, tablets, and widescreen displays.

---

## 🛠️ Architecture & Tech Stack

```text
flap-task-flow/
├── public/              # Static assets
└── src/
    ├── assets/          # Icons & media
    ├── components/      # Modular UI components
    │   ├── AddTask.jsx  # Task creation interface & validation
    │   ├── Input.jsx    # Reusable styled input primitives
    │   └── Tasks.jsx    # Interactive task lists & action handlers
    ├── pages/
    │   └── TaskPage.jsx # Rich task inspection & routing view
    ├── App.jsx          # Root state management & layout
    └── main.jsx         # Application entry point & router setup
```

| Technology | Purpose |
| :--- | :--- |
| **React 18** | Declarative component architecture & optimized state reconciliation |
| **Vite 5** | Lightning-fast HMR and optimized production bundling |
| **Tailwind CSS** | Utility-first design system with responsive tokens |
| **React Router v6** | Declarative client-side routing and path parameter parsing |
| **Lucide React** | Clean, accessible SVG iconography |
| **UUID** | Universally unique identifiers for reliable state tracking |

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (v18+) installed.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/caiovaf/flap-task-flow.git
   cd flap-task-flow
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the local development server:**
   ```bash
   npm run dev
   ```

4. **Build for production:**
   ```bash
   npm run build
   ```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
