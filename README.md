# ConsoleAI-DevTools-Copilot-Browser-Extension

A revolutionary AI-powered copilot designed to supercharge your browser's developer tools. ConsoleAI provides real-time error analysis, intelligent code optimization suggestions, and deep debugging insights, dramatically boosting developer productivity and accelerating the web development lifecycle.

---

## Project Status

[![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension/ci.yml?style=flat-square)](https://github.com/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension?style=flat-square)](https://codecov.io/gh/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension)
[![Tech Stack](https://img.shields.io/badge/tech-stack-JavaScript%2C%20HTML%2C%20CSS-blue?style=flat-square)](https://github.com/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension)
[![Lint/Format](https://img.shields.io/badge/lint--format-Biome-brightgreen?style=flat-square)](https://github.com/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension)
[![License](https://img.shields.io/badge/license-CC%20BY--NC%204.0-orange?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension?style=flat-square)](https://github.com/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension)

---

## ⭐ Star this Repo!

If you find ConsoleAI valuable, please consider starring this repository to show your support and help increase its visibility. Your support fuels continued development and improvements.

---

## 🚀 Key Features

*   **Real-time Error Analysis:** Instantly identifies and explains JavaScript errors, network failures, and console warnings.
*   **Code Optimization Suggestions:** Offers actionable insights to improve code performance, readability, and maintainability.
*   **Intelligent Debugging:** Provides contextual debugging tips and potential solutions based on observed issues.
*   **Productivity Boost:** Streamlines the development workflow by automating repetitive analysis tasks.
*   **Seamless Integration:** Works directly within your browser's existing developer tools.

---

## 🌳 Project Structure

text
ConsoleAI-DevTools-Copilot-Browser-Extension/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   ├── CONTRIBUTING.md
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── SECURITY.md
├── src/
│   ├── content/
│   │   ├── content.js
│   │   └── style.css
│   ├── background/
│   │   └── background.js
│   ├── devtools/
│   │   ├── devtools.html
│   │   └── devtools.js
│   ├── popup/
│   │   ├── popup.html
│   │   └── popup.js
│   └── utils/
│       └── aiHelper.js
├── public/
│   └── manifest.json
├── .gitignore
├── AGENTS.md
├── badges.yml
├── LICENSE
├── PROPOSED_README.md
├── README.md
└── package.json


---

## 🤖 AI Agent Directives

<details>
<summary>View AI Agent Directives</summary>

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
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type (`package.json` for JS/TS Extensions) and apply the corresponding **Apex Toolchain**.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (JavaScript/TypeScript)**
    *   **Stack:** This project leverages **JavaScript (ESNext)**. Key tools include **Vite 7** (for ultra-fast bundling and development server), **Biome** (for extremely fast linting and formatting), and **Vitest** (for robust unit and integration testing). **WebExtension Polyfill** is used for cross-browser compatibility.
    *   **Architecture:** Adheres to a **Modular Monolith** pattern, ensuring clear separation of concerns for different parts of the extension (content scripts, background scripts, devtools page, popup), while maintaining a unified codebase.
    *   **AI Integration:** Potential integration with external AI services via `fetch` API, prioritizing secure and efficient communication.
    *   **UI Framework:** Vanilla HTML/CSS/JS, with potential for minimal modern framework if performance dictates.

*   **SECONDARY SCENARIO A: SYSTEMS / PERFORMANCE (Rust/Go) - *Not applicable.***
*   **SECONDARY SCENARIO B: DATA / AI / SCRIPTS (Python) - *Not applicable.***

---

## 4. DEVELOPMENT & DEPLOYMENT MANDATES
*   **VERSION CONTROL:** Utilize Git. Adhere to GitFlow or a similar structured branching strategy.
*   **LINTING & FORMATTING:** **Biome** is mandatory for both linting and formatting across the entire codebase. Ensure all code is compliant before committing.
*   **TESTING:** **Vitest** is the standard for unit and integration tests. Aim for high test coverage (>90%). E2E tests should be considered for critical user flows using tools like Playwright if applicable.
*   **BUILD SYSTEM:** **Vite** is the build tool. Ensure the build process is optimized for production.
*   **CONTINUOUS INTEGRATION (CI):** GitHub Actions (`ci.yml`) must be configured for automated testing and linting on every push/pull request.
*   **DEPENDENCY MANAGEMENT:** Use `npm` or `yarn`. Always lock dependencies.
*   **LICENSING:** All code MUST be under **CC BY-NC 4.0**.

---

## 5. SECURITY & PRIVACY MANDATES
*   **Data Minimization:** Collect only the data strictly necessary for functionality.
*   **Secure Communication:** Use HTTPS for all external API calls. Sanitize all user inputs.
*   **Dependency Scanning:** Regularly scan dependencies for known vulnerabilities.
*   **Privacy Policy:** Maintain a clear and accessible privacy policy.
*   **Secure Coding Practices:** Follow OWASP Top 10 guidelines for browser extensions.

---

## 6. ARCHITECTURAL PRINCIPLES
*   **SOLID:** Adhere to Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles where applicable.
*   **DRY (Don't Repeat Yourself):** Avoid redundant code. Abstract common logic into reusable modules/functions.
*   **KISS (Keep It Simple, Stupid):** Favor straightforward solutions over complex ones.
*   **YAGNI (You Ain't Gonna Need It):** Do not implement features that are not currently required.

---

## 7. DOCUMENTATION & COMMUNICATION
*   **README.md:** Acts as the project's operational manual. Must be comprehensive and up-to-date.
*   **AGENTS.md:** Defines the AI's operational directives and context.
*   **CONTRIBUTING.md:** Provides clear guidelines for external contributions.
*   **ISSUE_TEMPLATE:** Standardizes bug reporting.
*   **PULL_REQUEST_TEMPLATE:** Standardizes pull request submissions.

---

## 8. PRODUCTIVITY ENHANCEMENT
*   **Command Palette:** Implement a command palette for quick access to features if applicable.
*   **Contextual Awareness:** Leverage browser context (DOM, network, console logs) to provide highly relevant AI insights.
*   **User Feedback Loop:** Integrate mechanisms for users to provide feedback on AI suggestions.

---

## 9. RETIRED PRODUCT PROTOCOL
*   **Archival:** Even retired products must maintain professional documentation and metadata. The goal is preservation and historical value, not abandonment.

</details>

---

## 🛠️ Development Standards

ConsoleAI is built with modern web technologies and adheres to rigorous development standards.

### Setup

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension.git
    cd ConsoleAI-DevTools-Copilot-Browser-Extension
    

2.  **Install dependencies:**
    bash
    npm install
    # or
    yarn install
    

### Scripts

| Script          | Description                                              |
| :-------------- | :------------------------------------------------------- |
| `npm run dev`   | Starts the Vite development server for hot-reloading.    |
| `npm run build` | Builds the extension for production deployment.          |
| `npm run lint`  | Runs Biome to lint and format the codebase.              |
| `npm run test`  | Executes unit and integration tests using Vitest.        |

### Core Principles

*   **SOLID:** Emphasizing modularity and maintainability.
*   **DRY:** Keeping code concise and reducing redundancy.
*   **KISS:** Favoring simplicity and clarity.
*   **YAGNI:** Implementing features only when needed.

---

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

We welcome contributions! Please see the [CONTRIBUTING.md](.github/CONTRIBUTING.md) file for detailed guidelines on how to submit bug reports, feature requests, and pull requests.

---

## 🔒 Security

Your security is important. Please refer to our [SECURITY.md](.github/SECURITY.md) file for details on reporting security vulnerabilities and our security practices.
