# Security Policy for TweetStorm-Real-Time-Social-Media-Web-App

## Our Commitment to Security

The `TweetStorm` team is deeply committed to ensuring the security and integrity of our platform. We value the contributions of the security research community and believe that responsible disclosure is essential for maintaining a safe environment for all our users. This document outlines our security policy, including how to report vulnerabilities and what you can expect from us.

## Supported Versions

As an actively developed project, security patches and updates are applied directly to our main development branch. We only provide security support for the latest version available in the `main` branch.

| Version | Supported          |
| ------- | ------------------ |
| Latest `main` | :white_check_mark: |
| < 1.0.0 | :x:                |

## Reporting a Vulnerability

We take all security reports seriously. If you believe you have discovered a security vulnerability in `TweetStorm`, please report it to us privately to protect the project and its users.

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please use the preferred method below:

### GitHub Private Vulnerability Reporting (Preferred Method)

Use the [private vulnerability reporting feature](https://github.com/chirag127/TweetStorm-Real-Time-Social-Media-Web-App/security/advisories/new) on GitHub. This is the most secure and efficient way to reach our maintainers directly.

### What to Include in Your Report

To help us triage and validate your finding as quickly as possible, please include the following in your report:

*   **Type of vulnerability** (e.g., XSS, CSRF, SQLi, Authentication Bypass).
*   **A detailed description** of the vulnerability and its potential impact.
*   **Step-by-step instructions** to reproduce the issue, including any URLs, request/response captures, or code snippets.
*   **Proof-of-Concept (PoC)** code or a working exploit.
*   Any **mitigation suggestions** you might have.

## Our Disclosure Process

1.  **Acknowledgement:** We will acknowledge receipt of your vulnerability report within **48 hours**.
2.  **Triage & Investigation:** We will investigate the report to confirm the vulnerability and determine its severity. We aim to provide an initial assessment and a status update within **7 business days**.
3.  **Remediation:** Once confirmed, we will work on a fix. The timeline for a patch will vary depending on the complexity of the vulnerability.
4.  **Coordinated Disclosure:** We will coordinate with you on the public disclosure of the vulnerability. We prefer to release a patch before disclosing the details to the public. We will credit you for your discovery unless you prefer to remain anonymous.

## Security Measures

We employ the following measures to enhance the security of our project:

*   **Dependency Scanning:** We use GitHub Dependabot to automatically scan our dependencies for known vulnerabilities and create pull requests to update them.
*   **Static Code Analysis:** We have integrated static analysis security testing (SAST) tools, such as GitHub CodeQL, into our CI/CD pipeline to identify potential vulnerabilities in our codebase before they are deployed.
*   **Code Reviews:** All code changes are subject to a mandatory peer review process to ensure code quality and identify potential security flaws.

We thank you for your help in keeping `TweetStorm-Real-Time-Social-Media-Web-App` and its users safe.
