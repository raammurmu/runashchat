---

# Contributing to RunAshChat

First off, thank you for considering contributing to RunAshChat! It’s people like you who make open-source tools better for everyone.

By participating in this project, you agree to abide by our Code of Conduct and the terms of the Apache 2.0 License.

## 🏗 Development Workflow

To ensure a smooth contribution process, we recommend the following workflow:

### 1. Setup Your Environment

* Fork the repository to your own GitHub account.
* Clone the fork locally: `git clone https://github.com/your-username/RunAshChat.git`
* Install dependencies: `npm install`
* Copy `.env.example` to `.env.local` and add your API keys.

### 2. Branching

Create a branch for your feature or bug fix:

```bash
git checkout -b feature/your-feature-name
# OR
git checkout -b fix/your-bug-name

```

### 3. Coding Standards

* **TypeScript:** This project is strictly typed. Avoid using `any`.
* **Linting:** Run `npm run lint` before committing to catch common errors.
* **Styling:** Use Tailwind CSS utility classes and [shadcn/ui](https://ui.shadcn.com) components for consistency.
* **Architecture:** Since we use the Next.js App Router, ensure server components are used by default and `'use client'` is only applied where interactivity is required.

## 🛠 Working with MCP

If you are contributing a new feature related to the **Model Context Protocol (MCP)**:

* Ensure your changes support both **HTTP** and **SSE** transport types where applicable.
* If adding a new built-in tool, document the tool's schema clearly in the code.
* Test your changes against a live MCP server (e.g., a local bridge or a service like Composio).

## 📥 Submitting a Pull Request

1. **Sync your fork:** Ensure your branch is up to date with the `main` branch of the original repository.
2. **Commit messages:** Use descriptive commit messages (e.g., `feat: add support for local MCP bridges`).
3. **Open the PR:** Provide a clear description of the changes. If it fixes a bug, link the issue using `Closes #123`.
4. **Review:** One of the maintainers will review your PR. We may suggest some changes or improvements before merging.

## 🐛 Reporting Bugs

If you find a bug, please open an **Issue** and include:

* A clear, descriptive title.
* Steps to reproduce the behavior.
* Expected vs. actual results.
* Screenshots (if applicable).
* Your environment (Browser, OS, Node version).

## 💡 Feature Requests

We love new ideas! If you have a suggestion:

* Check the existing Issues to see if it’s already been proposed.
* Open a new issue with the tag `enhancement`.
* Explain why this feature would be useful for the community.

---

**Thank you for helping make RunAshChat the best open-source AI interface!**

---


