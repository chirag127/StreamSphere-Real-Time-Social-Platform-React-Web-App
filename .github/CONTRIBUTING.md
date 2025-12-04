# Contributing to StreamSphere-Real-Time-Social-Platform-React-Web-App

Thank you for considering contributing to StreamSphere-Real-Time-Social-Platform-React-Web-App! We aim to maintain a production-ready, open-source template for scalable real-time social media apps, built with React, Vite, and TailwindCSS v4.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. By participating, you are expected to uphold this code. Please report any unacceptable behavior to <your-email@example.com>.

## 2. How to Contribute

We welcome contributions of all kinds, including:

*   **Bug Reports:** Please provide a clear description of the bug, steps to reproduce it, and your environment (OS, browser, Node.js version).
*   **Feature Requests:** Explain the feature and why it would be valuable. Consider how it aligns with the project's goals.
*   **Code Contributions:** We prefer contributions via Pull Requests.

## 3. Development Workflow

To contribute code, please follow these steps:

1.  **Fork the Repository:** Create your own fork of the `chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App` repository.
2.  **Clone Your Fork:** `git clone https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App.git` and navigate into the directory: `cd StreamSphere-Real-Time-Social-Platform-React-Web-App`.
3.  **Set Up Project:** Follow the setup instructions in the `README.md` to install dependencies and configure the project.
    *   `npm install` or `yarn install` (depending on your package manager preference specified in README).
4.  **Create a New Branch:** For each feature or fix, create a new branch:
    `git checkout -b feat/your-feature-name` or `git checkout -b fix/your-bug-fix`.
5.  **Make Your Changes:** Develop your feature or fix, adhering to the project's coding standards and architectural patterns.
6.  **Test Your Changes:** Ensure all tests pass. Add new tests for any new features or significant bug fixes.
    *   Run unit tests: `npm test` or `yarn test`.
    *   Run E2E tests (if applicable): `npm run e2e` or `yarn run e2e`.
7.  **Lint and Format:** Ensure your code is clean and adheres to the established linting and formatting rules.
    *   Run linter: `npm run lint` or `yarn lint`.
    *   Run formatter: `npm run format` or `yarn format`.
8.  **Commit Your Changes:** Write clear, concise commit messages.
    `git commit -m "feat: Add user profile editing functionality"`
9.  **Push to Your Fork:** `git push origin feat/your-feature-name`.
10. **Open a Pull Request:** Submit a Pull Request from your feature branch to the `main` branch of the `chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App` repository. Provide a detailed description of your changes.

## 4. Architectural Guidelines

*   **Technology Stack:** TypeScript, Vite, TailwindCSS v4.
*   **Architecture:** Feature-Sliced Design (FSD) is the preferred pattern for frontend organization. Aim for modularity, scalability, and maintainability.
*   **State Management:** Utilize standardized state management solutions as defined in the project's `README.md`.
*   **Component Design:** Follow best practices for React component development, emphasizing reusability and separation of concerns.

## 5. Branching Strategy

We follow a simplified Gitflow-like branching strategy:

*   `main`: Stable production releases.
*   `develop`: Integration branch for features.
*   `feat/*`: Feature branches (e.g., `feat/user-auth`).
*   `fix/*`: Bug fix branches (e.g., `fix/login-bug`).

All Pull Requests should target the `develop` branch, which will be periodically merged into `main` for releases.

## 6. Pull Request Guidelines

*   **Clear Title and Description:** The title should concisely describe the PR. The description should explain the "what" and "why" of your changes.
*   **Link to Issues:** If your PR addresses an issue, reference it using keywords like `Closes #123` or `Fixes #456`.
*   **Code Reviews:** All PRs will be reviewed by at least one maintainer. Be prepared to address feedback.
*   **CI Checks:** Ensure all Continuous Integration checks (build, lint, test) pass before submitting your PR. The workflow is defined in `.github/workflows/ci.yml`.

## 7. Reporting Security Vulnerabilities

We take security seriously. If you discover a security vulnerability, please follow the guidelines outlined in the `.github/SECURITY.md` file. Do not open a public issue for security concerns.

## 8. Project Standards

This project adheres to the following principles:

*   **SOLID:** Adhere to the Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles where applicable.
*   **DRY:** Don't Repeat Yourself. Extract common logic into reusable functions or components.
*   **YAGNI:** You Ain't Gonna Need It. Avoid adding functionality until it's actually required.

By contributing, you agree that your contributions will be licensed under the **CC BY-NC 4.0 License**.
