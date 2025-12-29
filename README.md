# front-end-smart-expense-tracker
# react-expense tracker
# 💰 Smart Expense Tracker (React + Tailwind CSS)
# React + Vite

An intuitive and modern application built with **ReactJS** and styled using **Tailwind CSS** for tracking, analyzing, and visualizing personal daily expenses. Data persistence is handled via the browser's `localStorage`.
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

## ✨ Key Features
Currently, two official plugins are available:

* **Expense Management (CRUD):** Easily add, view, and delete expense entries.
* **Persistent Storage:** All expense data is saved locally using `localStorage`, ensuring data remains available between browser sessions.
* **Advanced Filtering & Sorting:** Filter expenses by category, date range, and sort by highest amount or most recent entry.
* **Category-wise Analysis:** Automatically calculates and displays total spending per category.
* **Data Visualization:** Uses Recharts to display a dynamic Pie Chart showing the distribution of spending across all categories.

  ## 🛠️ Tech Stack


| Category | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | **React.js** | Library for building the user interface. |
| **Styling** | **Tailwind CSS** | Utility-first framework for rapid and consistent styling. |
| **Charting** | **Recharts** | A composable charting library built on React components. |
| **State/Data** | **React Hooks** | Utilizes `useState`, `useEffect`, and `useMemo` for state management, persistence, and performance optimization.  |
| **Persistence**| **`localStorage`** | Browser API used to store and retrieve expense data locally. |
The React Compiler is enabled on this template. See [this documentation](https://react.dev/learn/react-compiler) for more information.

## 🚀 Getting Started
Note: This will impact Vite dev & build performances.

Follow these steps to set up the project locally.
## Expanding the ESLint configuration

### Prerequisites

* Node.js (v14+) and npm (or yarn)
