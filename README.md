# Aegis Developer Dashboard (v2.0)

![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)
![Tailwind](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-Animation-ec4899?style=for-the-badge&logo=framer)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)

The unified control plane for the Aegis Security Platform.

This dashboard serves as the frontend interface for managing security posture, visualizing real-time metrics, and interacting with the Aegis AI Engine. It demonstrates a modern, component-driven architecture using **Server Components** for performance and **Client Components** for rich interactivity.

---

## 🏗 Architecture & Design

* **Framework:** Next.js 14 (App Router)
* **Styling:** Tailwind CSS with a custom "Glassmorphism" design system (Dark Mode native).
* **Animation:** Framer Motion for complex layout transitions and micro-interactions.
* **Integration:**
    * Connects to `saas-kit-v2` (Repo 1) for user management.
    * Connects to `code-analyzer` (Repo 2) for real-time AI code analysis.

### Key Features
1.  **Live AI Integration:** Directly interfaces with the Python AST Microservice to score code complexity in real-time.
2.  **Visual Data:** Custom-built metric cards with animated progress bars and state-aware interactions.
3.  **Responsive Layout:** A production-grade sidebar layout that adapts seamlessly to mobile.

---

## 🚀 Getting Started

### Prerequisites
* Node.js 18+
* The `code-analyzer` service (Repo 2) must be running on port `8001` for full functionality.

### 1. Installation
```bash
npm install
