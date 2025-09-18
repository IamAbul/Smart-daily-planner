# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# Smart Daily Planner + To-Do (with AI touch)

A modern and responsive **daily planning web app** built with React and TailwindCSS.  
Manage your tasks efficiently with a clean UI and intuitive task management features. Designed to be **resume-ready** and easily extendable for future AI integrations.

---

## Features

- **Add/Delete Tasks** – Quickly manage your daily tasks  
- **Task List** – View all your tasks with interactive hover effects  
- **Dashboard Overview** – Shows total tasks at a glance  
- **Clean & Responsive UI** – Modern card layout, rounded buttons, subtle shadows  
- **Extensible AI Suggestions** – Easy to integrate AI-powered task recommendations in the future  
- **LocalStorage Ready** – Tasks can be persisted on browser (optional enhancement)

---

## Tech Stack

- **Frontend:** React, React Hooks  
- **Styling:** TailwindCSS  
- **State Management:** React useState  
- **Build Tool:** Vite  
- **Optional/Extendable:** Chart.js for dashboards, AI APIs for suggestions

---

## Project Structure
smart-daily-planner/
├─ node_modules/
├─ public/
├─ src/
│ ├─ assets/
│ ├─ App.jsx
│ ├─ index.css
│ └─ main.jsx
├─ package.json
├─ tailwind.config.js
├─ postcss.config.js
└─ README.md

---

## Installation

1. **Clone the repository**

```bash
git clone <your-repo-link>
cd smart-daily-planner
2. Install dependencies
npm install
3. Start the development server
npm run dev
4. Open the app in your browser

Go to http://localhost:5173/

Usage

Enter a task in the input field and click Add

Click Delete to remove tasks

Check the Tasks Overview at the bottom for a quick summary

Future Enhancements

AI-powered task suggestions

Task categorization & priority labels

Charts for completed vs pending tasks using Chart.js

LocalStorage support for persistence

Responsive mobile-friendly design


Author
Abul Hasan
Final Year B.Tech (AI & ML)
Email: abulhasana2004@gmail.com
