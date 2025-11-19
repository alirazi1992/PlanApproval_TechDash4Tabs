# PlanApproval Technician Dashboard (4 Tabs)

A focused prototype of the **Technician Dashboard** for the PlanApproval ecosystem, built as a single-page web app with **four main tabs** for day-to-day technical operations.  
This project is implemented with **React + TypeScript + Vite + Tailwind CSS**, originally scaffolded from a Magic Patterns Vite template and then customized for the PlanApproval workflow.  

> Goal: provide a clean, modern, and extendable UI for technician-side features of the PlanApproval system.

---

## Features

- **Four-tab technician workspace**
  - Dedicated tabs (e.g. *Overview*, *Projects*, *Calendar*, *Reports* – depending on the current UI) for separating technician responsibilities.
  - Tabbed navigation at the top of the dashboard for quick context switching.

- **PlanApproval-style layout**
  - Designed to fit into the broader PlanApproval UI language (cards, panels, clean layout).
  - Suitable as a standalone prototype or as a module to be embedded into the main PlanApproval app.

- **Modern frontend stack**
  - **React + TypeScript** single-page application.
  - **Vite** for fast dev server and optimized builds.
  - **Tailwind CSS** utility-first styling.
  - Build output in `dist/` ready to be hosted on any static server. :contentReference[oaicite:0]{index=0}

- **Dummy data for UI prototyping**
  - Uses mocked data (no backend) so you can focus on layout, states, and UX.
  - Easy to swap with real APIs later.

---

## Tech Stack

- **Framework:** React (TypeScript)
- **Bundler/Dev Server:** Vite
- **Styling:** Tailwind CSS + PostCSS
- **Language:** TypeScript / JSX
- **Package Manager:** npm

Key project files (already in the repo): :contentReference[oaicite:1]{index=1}

- `index.html` – App entry HTML shell  
- `src/` – React components, pages, and layout for the 4-tab dashboard  
- `vite.config.ts` – Vite configuration  
- `tailwind.config.js` – Tailwind configuration  
- `postcss.config.js` – PostCSS pipeline  
- `package.json` / `package-lock.json` – dependencies & scripts  

---

## Getting Started

### Prerequisites

- **Node.js** (recommended: v18+)
- **npm** (comes with Node)

### Project Structure (high level)


PlanApproval_TechDash4Tabs/

├─ dist/                 # Production build output (generated)

├─ src/                  # Source code (React/TypeScript)

│  ├─ components/        # Reusable UI components & layout pieces

│  ├─ pages/ or views/   # Dashboard / tab view containers (depending on implementation)

│  ├─ main.tsx           # App entry point

│  └─ ...                # Other utility files, hooks, types, etc.

├─ index.html            # Root HTML file

├─ package.json          # Scripts & dependencies

├─ tailwind.config.js    # Tailwind configuration

├─ postcss.config.js     # PostCSS configuration

├─ tsconfig*.json        # TypeScript configuration

└─ vite.config.ts        # Vite configuration
