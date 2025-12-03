# Security Policy for ConsoleAI-DevTools-Copilot-Browser-Extension

## 1. Reporting a Vulnerability

We take the security of ConsoleAI-DevTools-Copilot-Browser-Extension very seriously. If you discover a security vulnerability, we would like to be informed as soon as possible so that we can address it.

Please report any security vulnerabilities to us promptly through one of the following channels:

*   **GitHub Security Advisories:** Create a private security report at [https://github.com/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension/security/advisories/new](https://github.com/chirag127/ConsoleAI-DevTools-Copilot-Browser-Extension/security/advisories/new).
*   **Email:** Send an encrypted email to `chirag127.dev@gmail.com`.

We request that you provide as much information as possible, including:

*   A clear description of the vulnerability.
*   Steps to reproduce the vulnerability.
*   Your environment (e.g., browser version, operating system, extension version if applicable).
*   Any proof-of-concept code or screenshots.

## 2. Vulnerability Handling

We will acknowledge receipt of your security report within **24 hours** and will endeavor to respond within **3 business days**. We will keep you informed of the progress of our investigation and remediation efforts.

*   **Triage:** We will triage reported vulnerabilities based on their severity and potential impact.
*   **Remediation:** Once a vulnerability is confirmed, we will work to develop and release a fix as quickly as possible.
*   **Disclosure:** We will follow responsible disclosure practices. After a fix has been released, we may publicly disclose the vulnerability details once we are confident that the risk to users has been mitigated.

## 3. Supported Versions

As ConsoleAI-DevTools-Copilot-Browser-Extension is a browser extension, we are primarily concerned with the latest stable version available through the official browser web stores. We will prioritize security fixes for the **most recent stable release**. Older versions may not be actively maintained or patched.

## 4. Development Practices for Security

We are committed to developing ConsoleAI-DevTools-Copilot-Browser-Extension with security in mind. This includes:

*   **Dependency Management:** Regularly scanning and updating dependencies using `uv` and `Ruff` to address known vulnerabilities.
*   **Linting & Formatting:** Employing `Ruff` for strict code quality and security checks.
*   **Testing:** Utilizing `Pytest` to ensure code integrity and prevent regressions.
*   **Browser Extension Security Best Practices:** Adhering to guidelines for secure browser extension development, including minimizing permissions, sanitizing inputs, and avoiding sensitive data exposure.
*   **AI Integration Security:** When interacting with AI models, we ensure proper input sanitization and output validation to prevent prompt injection and other AI-specific security risks.

## 5. Safe Harbor Statement

We will not pursue legal action against individuals who discover and report security vulnerabilities in good faith, provided they adhere to this security policy and do not engage in activities that disrupt the project or its users.

*Last Updated: December 2025*
