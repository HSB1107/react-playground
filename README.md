# 🧪 React Playground
### A Centralized Lab for UI Components & Technical POCs

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

## 🎯 Overview
**React Playground** is a custom-built sandbox designed to architect, test, and document reusable UI components and Proof of Concepts (POCs). Rather than scattered repositories, this project serves as a unified environment to showcase high-quality frontend engineering, clean code principles, and interactive design patterns.

Inspired by the **Storybook** workflow, it features a dynamic sidebar for navigating through isolated component implementations and technical experiments in real-time.

## 🚀 Key Features
* **Component Isolation:** Each POC is rendered in a dedicated "Stage" to ensure modularity.
* **Dynamic Registry:** Automated sidebar navigation powered by a centralized component registry.
* **Modern Tech Stack:** Leveraging **Vite** for HMR, **TypeScript** for type safety, and **Tailwind CSS** for utility-first styling.
* **Interactive Logic:** Demonstrations of complex state management, custom hooks, and performance optimizations.

## 🛠 Tech Stack
* **Core:** React 18+ (Functional Components & Hooks)
* **Build Tool:** Vite
* **Language:** TypeScript
* **Styling:** Tailwind CSS
* **Icons:** Lucide React

## 📂 Project Structure
```text
src/
├── components/       # Shared UI elements (Button, Card, Sidebar)
├── labs/             # The POCs and experimental components
│   ├── FormBuilder/  # Logic for future Google Form clone
│   └── DataTables/   # Complex state management POCs
├── registry/         # Configuration for dynamic routing/sidebar
└── App.tsx           # Layout wrapper with Stage & Sidebar
