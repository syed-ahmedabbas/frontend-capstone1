# 🚀 FlyRank Capstone — Frontend AI Engineering Track

[![Tech Stack](https://img.shields.io/badge/Stack-Next.js%20%7C%20React%20%7C%20TypeScript%20%7C%20Tailwind-blue)](https://nextjs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Welcome to the **FlyRank Frontend AI Engineering Track** capstone project! This repository contains the source code, configurations, and documentation for the development of our high-performance, responsive AI-powered web application.

---

## 🛠️ Technology Stack

Our application is built on modern, production-grade frontend technologies:

*   **Framework:** [Next.js](https://nextjs.org/) (App Router, React 19)
*   **Language:** [TypeScript](https://www.typescriptlang.org/) (Strict Mode)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/) (Mobile-First responsive utilities)
*   **Target Environments:** Mobile, Tablet, and Desktop web views

---

## 📁 Repository Structure

Below is the directory layout and location of key files:

```text
├── .git/                 # Git version control
├── .gitignore            # Git ignored files & directories
├── LICENSE               # MIT License terms
├── CLAUDE.md             # Development conventions & commands (Claude-specific)
├── GEMINI.md             # Developer instructions referencing CLAUDE.md
└── README.md             # Project documentation (this file)
```

*(Note: Application source code files under `/app`, `/components`, `/public`, and `/styles` will be added as we scaffold the Next.js application.)*

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

Ensure you have the following installed on your machine:
*   [Node.js](https://nodejs.org/) (v18.x or later recommended)
*   [npm](https://www.npmjs.com/) (packaged with Node.js) or another preferred package manager (pnpm, yarn)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd flyrank-capston
   ```

2. Install dependencies (once dependencies are added to `package.json`):
   ```bash
   npm install
   ```

### Development Server

Run the development server locally:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Build and Production

To build the application for production:
```bash
npm run build
```

To run the built production bundle:
```bash
npm run start
```

---

## 📐 Development Guidelines & Conventions

We follow strict standards to keep the codebase clean, performant, and type-safe. Please refer to:
*   [CLAUDE.md](file:///c:/Users/x_o/Desktop/flyrank-capston/CLAUDE.md) for detailed style guides, TypeScript configurations, coding conventions, and command references.
*   [GEMINI.md](file:///c:/Users/x_o/Desktop/flyrank-capston/GEMINI.md) for instructions guiding AI assistant interactions in this codebase.

Key rules summary:
1.  **Strict TypeScript:** No implicit `any`, define explicit return and prop types.
2.  **Mobile-First Design:** Base styles are designed for mobile screens, building up for desktop.
3.  **Clean Components:** Functional component organization under `/components` using React Server Components (RSC) by default.

---

## 🗺️ Roadmap & Weekly Milestones

*   [x] **Week 1:** Repository initialization, licensing, and documentation standards.
*   [ ] **Week 2:** Next.js scaffolding, core component design system, and tailwind theme setup.
*   [ ] **Week 3:** Core features, API integration, and routing layout.
*   [ ] **Week 4:** Optimization, performance analysis, final styling polish, and deployment.
