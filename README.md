# StreamSphere - Real-Time Social Platform React Template

![GitHub Actions Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template/ci.yml?style=flat-square)
![Code Coverage](https://codecov.io/gh/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template/branch/main/graph/badge.svg?style=flat-square)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template?style=flat-square)

[⭐ Star this Repo](https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template)

---

## 🚀 BLUF: Vision & Value Proposition

StreamSphere is a production-ready, open-source architectural template engineered for rapidly deploying scalable, low-latency social media applications. This boilerplate enforces modern best practices using TypeScript, Vite, and TailwindCSS v4 to deliver unparalleled frontend performance.

## 📐 Architectural Blueprint (FSD via TypeScript/Vite)

This repository adheres to the Feature-Sliced Design (FSD) pattern, optimizing component reusability and maintainability across the application surface.

mermaid
graph TD
    A[Root Config/Shared] --> B(Features/Pages)
    B --> C{Components/Entities}
    B --> D{App/Providers}
    C --> E[Shared/UI Elements]
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#ccf,stroke:#333,stroke-width:2px


## 📋 Table of Contents

1.  [🚀 BLUF: Vision & Value Proposition](#-bluf-vision-value-proposition)
2.  [📐 Architectural Blueprint (FSD via TypeScript/Vite)](#-architectural-blueprint-fsd-via-typescriptvite)
3.  [📋 Table of Contents](#-table-of-contents)
4.  [🛠️ Core Technology Stack (2026 Standard)](#-core-technology-stack-2026-standard)
5.  [🤖 AI Agent Directives (Apex Protocol)](#-ai-agent-directives-apex-protocol)
6.  [⚙️ Development & Setup](#-development-setup)
7.  [✅ Development Principles](#-development-principles)
8.  [⚖️ License](#-license)

## 🛠️ Core Technology Stack (2026 Standard)

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Language** | TypeScript 5.x (Strict Mode) | Type Safety, Scalability |
| **Build Tool** | Vite 5.x | Extreme Build Speed |
| **Styling** | TailwindCSS v4 (Pre-release Candidate) | Utility-First Design System |
| **Testing (Unit/Int)** | Vitest | Fast In-memory Unit Testing |
| **Testing (E2E)** | Playwright | Cross-Browser End-to-End Verification |
| **Linting/Formatting** | Biome | Unifying Linter, Formatter, and Bundler Checks |
| **Architecture** | Feature-Sliced Design (FSD) | Enforced Modularity and Dependency Inversion |
| **Real-Time** | WebSocket/Socket.IO Integration Point | Low-Latency Communication Layer |

## 🤖 AI Agent Directives (Apex Protocol)

<details>
<summary><strong>Click to View Apex Directives for Autonomous Maintenance</strong></summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

--- 

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs. Do not assume external libraries unless explicitly defined in the toolchain.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Vulnerabilities (XSS/CSRF in React)**, and **2026 UI Trends (e.g., signals adoption, CSS nesting)**.
    *   **Validation:** Use `docfork` to verify *every* external API signature (e.g., Vite configuration flags, Tailwind JIT behavior).
    *   **Reasoning:** Engage `clear-thought-two` to architect complex state management flows *before* writing code.

--- 

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository is a **WEB / APP / GUI** project.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend)**
    *   **Stack:** **TypeScript 6.x (Strict)**, **Vite 7**, **TailwindCSS v4**, **Tauri v2** (if adapting for desktop hybrid). 
    *   **Lint/Test:** **Biome** (Speed) + **Vitest** (Unit) + **Playwright** (E2E).
    *   **Architecture:** **Feature-Sliced Design (FSD)**. Strict layer separation is non-negotiable: `Shared` -> `Entities` -> `Features` -> `Pages`.
    *   **State Management:** Prefer integrated state management solutions (e.g., Preact Signals, TanStack Query, or custom Context/Hooks) over heavy historical libraries unless specified.

--- 

## 4. EXECUTION VERIFICATION COMMANDS

*   **LINT & FORMAT CHECK:**
    `npx @biomejs/biome check --apply .`
*   **UNIT TEST RUN:**
    `npx vitest`
*   **E2E TEST RUN (Playwright):**
    `npx playwright test`
*   **START DEVELOPMENT SERVER:**
    `npm run dev`

</details>

## ⚙️ Development & Setup

### Prerequisites
Ensure you have Node.js (v20+) and npm/pnpm/yarn installed.

### 1. Clone Repository
bash
git clone https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template.git
cd StreamSphere-Real-Time-Social-Platform-React-Template


### 2. Install Dependencies (Using uv-equivalent speed for Node)
bash
npm install
# OR (Recommended for superior dependency resolution)
pnpm install


### 3. Run Development Server
bash
npm run dev
# Server typically starts on http://localhost:5173


### Development Scripts

| Script | Command | Description |
| :--- | :--- | :--- |
| `dev` | `npm run dev` | Start the blazing fast Vite development server. |
| `build` | `npm run build` | Compile for production using Rollup/Vite bundling. |
| `lint` | `npx @biomejs/biome check .` | Check code quality and formatting standards. |
| `test:unit` | `npx vitest` | Run all unit and integration tests. |
| `test:e2e` | `npx playwright test` | Execute end-to-end browser automation tests. |
| `preview` | `npm run preview` | Locally serve the production build via Vite preview. |

## ✅ Development Principles

We enforce adherence to these architectural tenets:

*   **SOLID:** Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion.
*   **DRY:** Don't Repeat Yourself. Abstract common logic into `Shared/lib` or `Entities`.
*   **YAGNI:** You Aren't Gonna Need It. Resist premature abstraction; build only what is required now.
*   **FSD Layering:** Strict control over imports: Features cannot import from other Features directly; they must flow through Shared or Entities layers.

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**. See the [LICENSE](LICENSE) file for details.

*You are free to share and adapt this work for non-commercial purposes, provided you give appropriate credit.*
