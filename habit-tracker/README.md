# 🌱 Habit Tracker

A modern, lightweight habit tracking application built with React and TypeScript.
The project focuses on clean component architecture, reusable state management, and a simple user experience that helps users build and maintain consistent daily habits.

## 📌 Project Overview

Habit Tracker allows users to create habits, track daily completion, and monitor their consistency across a weekly timeline.

This project was built to demonstrate practical frontend engineering skills including:

* Component-based React development
* Type-safe application architecture
* State management with React Context
* Custom React hooks
* Browser storage persistence
* Responsive UI development

---

# ✨ Features

## ✅ Habit Management

Users can:

* Create new habits
* Delete existing habits
* Mark habits as completed
* Toggle completion status for specific days
* Manage multiple habits simultaneously

## 📅 Weekly Tracking System

The application provides a weekly view where users can:

* Navigate between weeks
* View habits across individual days
* Track completion history visually

The calendar functionality is powered by date utilities to handle week calculations and date comparisons reliably.

## 💾 Persistent Storage

Habit data is automatically stored locally in the browser.

Features include:

* Persistent data between sessions
* Automatic state synchronisation
* Date restoration when loading saved data

---

# 🛠️ Tech Stack

## Frontend

| Technology   | Purpose                          |
| ------------ | -------------------------------- |
| React 19     | User interface development       |
| TypeScript   | Type safety and maintainability  |
| Vite         | Development tooling and bundling |
| Tailwind CSS | Styling and responsive layouts   |
| date-fns     | Date manipulation utilities      |

## Architecture

* React Context API for global habit state
* Custom hooks for reusable logic
* Component-driven UI structure
* LocalStorage-based persistence layer

---

# 🏗️ Application Architecture

The project follows a modular React structure:

```
src
│
├── Components
│   ├── Header
│   ├── HabitForm
│   └── HabitList
│
├── context
│   ├── HabitProvider
│   └── HabitContext
│
├── Hooks
│   └── useLocalStorage
│
└── App.tsx
```

---

# 🧠 Technical Implementation

## State Management

Habit data is managed through a dedicated provider layer.

The provider handles:

* Adding habits
* Removing habits
* Updating completion records
* Sharing state across components

This keeps business logic separate from UI components.

---

## Custom Local Storage Hook

A reusable `useLocalStorage` hook manages persistence.

Responsibilities:

* Reading stored data
* Updating browser storage automatically
* Restoring JavaScript Date objects from saved values

This creates a cleaner separation between application logic and storage handling.

---

# 🚀 Getting Started

## Prerequisites

Make sure you have:

* Node.js installed
* npm installed
* Git installed

---

## Installation

Clone the repository:

```bash
git clone https://github.com/missing0201/habit_tracker.git
```

Navigate into the project:

```bash
cd habit_tracker/habit-tracker
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The application will be available locally through the Vite development server.

---

# 📦 Available Scripts

| Command           | Description              |
| ----------------- | ------------------------ |
| `npm run dev`     | Start development server |
| `npm run build`   | Create production build  |
| `npm run preview` | Preview production build |
| `npm run lint`    | Run code quality checks  |

---

# 📸 Screenshots

*Add screenshots here before sharing with employers.*

Recommended screenshots:

* Main dashboard
* Weekly habit tracker
* Creating a habit
* Completed habit examples

Example:

```
screenshots/
├── dashboard.png
├── weekly-view.png
└── habit-complete.png
```

---

# 🔮 Future Improvements

Potential improvements:

* User authentication
* Cloud database synchronisation
* Mobile application version
* Habit streak calculations
* Progress analytics dashboard
* Notifications and reminders
* Dark mode support
* Drag-and-drop habit organisation

---

# 📚 Learning Outcomes

Building this project improved my understanding of:

* Designing scalable React applications
* Managing shared application state
* Creating reusable hooks
* Working with TypeScript interfaces
* Handling dates and calendar logic
* Building maintainable frontend architecture

---

# 👨‍💻 Author

**Missing0201**

GitHub:
https://github.com/missing0201

---

# 📄 License

This project is open source and available under the MIT License.
