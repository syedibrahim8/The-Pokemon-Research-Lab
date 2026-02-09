# The Pokémon Research Lab 🧪⚡  
A tool to **aggregate a comprehensive dataset of all Pokémon** by fetching it from the public **PokeAPI**, and then provide an **advanced interface** for users to **analyze, manipulate, and export** this large dataset. :contentReference[oaicite:0]{index=0}

---

## ✨ What this repo contains

This repository is a **TypeScript-heavy** frontend project (majority TS) focused on handling a **large Pokémon dataset smoothly** and presenting it through a powerful data table UI. :contentReference[oaicite:1]{index=1}

### Key goals
- **Performance first** for large datasets (fast rendering + smooth scrolling)
- Clean architecture and modular components
- Strong TypeScript safety + predictable state management
- Useful dataset operations: search, sort, filter, edit, export

---

## 🧩 Features (high level)

- Fetch Pokémon dataset from **PokeAPI**
- Large-data table experience (smooth scroll, fast render)
- Sorting / filtering / searching (depending on UI controls in the app)
- Data manipulation (ex: edit cells / derived columns — based on UI)
- Export dataset (CSV/JSON — if enabled in UI)

> If a feature is not currently visible in the UI, treat this section as the project’s intended scope and feel free to adjust.

---

## 🛠️ Tech Stack

- **TypeScript**
- **React**
- Data table utilities (commonly TanStack Table / Virtualization in this kind of app)
- Styling: CSS (and/or utility styling depending on your setup)

Repo language breakdown shows it’s mostly TypeScript. :contentReference[oaicite:2]{index=2}

---

## ✅ Requirements

Make sure you have:

- **Node.js 18+** (recommended)
- One package manager:
  - `pnpm` (recommended)  
  - OR `npm` / `yarn`

---

## 📦 Installation (Step-by-step)

> The app lives inside the `client/` folder. :contentReference[oaicite:3]{index=3}

### 1) Clone the repository
```bash
git clone https://github.com/syedibrahim8/The-Pokemon-Research-Lab.git
cd The-Pokemon-Research-Lab
```
### 2) Go into the client
```bash
cd client
```
### 3) Install dependencies (using pnpm)
```bash
pnpm install
```
### Using npm
```bash
npm install
```
### Using yarn
```bash
yarn
```
## ▶️ Run the project (Development)
From inside client/:
pnpm
```bash
pnpm dev
```
npm
```bash
npm run dev
```
yarn
```bash
yarn dev
```
