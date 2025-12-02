# Contributing to TeraBridge-Terabox-Direct-Link-Generator

Thank you for considering contributing to `TeraBridge-Terabox-Direct-Link-Generator`! We welcome your contributions to help make this project even better. This document outlines the process and guidelines for contributing.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. By participating, you are expected to uphold its values. Please report any unacceptable behavior to [codeofconduct@example.com](mailto:codeofconduct@example.com) or through a GitHub issue.

## 2. Getting Started

### 2.1 Prerequisites

Before you begin, ensure you have the following installed:

*   **Git:** For version control.
*   **Node.js:** Version 18.x or higher recommended.
*   **npm or Yarn:** Package manager.
*   **Vite:** For the build process.
*   **Node.js Ecosystem:** General familiarity with modern JavaScript/TypeScript development.

### 2.2 Setup

Follow these steps to set up your development environment:

1.  **Fork the Repository:** Click the "Fork" button on the repository's GitHub page (`https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator`) to create your own copy.
2.  **Clone Your Fork:**
    bash
    git clone https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator.git
    cd TeraBridge-Terabox-Direct-Link-Generator
    
3.  **Set Upstream Remote:** This helps you keep your fork updated.
    bash
    git remote add upstream https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator.git
    
4.  **Install Dependencies:**
    bash
    npm install
    # or
    yarn install
    
5.  **Run Development Server:** To test your changes locally.
    bash
    npm run dev
    # or
    yarn dev
    

## 3. Contribution Workflow

We follow a standard GitHub pull request (PR) workflow:

1.  **Create a Feature Branch:** Always work on a new branch for your feature or bugfix.
    bash
    git checkout -b feature/your-feature-name
    # or
    git checkout -b fix/your-bug-fix
    
2.  **Make Your Changes:** Implement your changes according to the project's architectural guidelines and coding standards.
3.  **Test Your Changes:** Ensure your changes are thoroughly tested. Run the provided test suite (`npm test` or `yarn test`). If you are adding new functionality, write new tests.
4.  **Lint and Format:** Ensure your code adheres to the project's linting and formatting standards.
    bash
    npm run lint -- --fix
    # or
    yarn lint --fix
    
    bash
    npm run format
    # or
    yarn format
    
5.  **Commit Your Changes:** Write clear, concise commit messages. Follow conventional commit standards if possible.
    bash
    git add .
    git commit -m "feat: Add new link generation algorithm"
    
6.  **Push to Your Fork:** Push your branch to your fork on GitHub.
    bash
    git push origin feature/your-feature-name
    
7.  **Open a Pull Request:** Go to the original repository (`https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator`) and open a new Pull Request from your feature branch.
    *   **Title:** Provide a clear and descriptive title for your PR.
    *   **Description:** Explain what your PR does, why it's needed, and any potential impacts. Link to any relevant issues.

## 4. Coding Standards & Best Practices

*   **Language:** Primarily TypeScript. Use strict typing whenever possible.
*   **Framework:** Vite with React.
*   **Styling:** Tailwind CSS v4.
*   **Architecture:** Adhere to modern web development patterns. Aim for modularity, reusability, and separation of concerns.
*   **Testing:** Write unit and end-to-end tests using Vitest and Playwright.
*   **Linting/Formatting:** Use Biome for code linting and formatting consistency.
*   **Commit Messages:** Follow Conventional Commits guidelines.
*   **Documentation:** Ensure new code is adequately documented, especially public APIs.

## 5. Reporting Issues

If you encounter a bug or have a feature request, please:

1.  **Check Existing Issues:** Search the GitHub Issues page to see if your issue has already been reported.
2.  **Create a New Issue:** If it's a new issue, open a new one using the provided templates. Provide as much detail as possible, including:
    *   A clear, descriptive title.
    *   Steps to reproduce the bug.
    *   Expected vs. Actual behavior.
    *   Environment details (browser, OS, etc.).
    *   Screenshots or error logs if applicable.

## 6. Updating Your Fork

To keep your fork up-to-date with the main repository:

bash
git checkout main # Or the branch you are working on
git fetch upstream
git merge upstream/main


Then, resolve any merge conflicts and push the changes to your fork.

## Thank You!

We appreciate your effort in contributing to `TeraBridge-Terabox-Direct-Link-Generator`. Your contributions are invaluable!