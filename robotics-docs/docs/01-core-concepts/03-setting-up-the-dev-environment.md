---
sidebar_position: 3
---

# Setting up the Development Environment

A well-configured development environment is crucial for any robotics project. This lesson will guide you through installing the necessary software and tools to begin your journey into Physical AI and humanoid robotics.

## Prerequisites

Before we begin, ensure your system meets the following basic requirements:

*   **Operating System**: Windows 10/11, macOS (Ventura or later), or a recent Linux distribution (Ubuntu 22.04 LTS or later recommended).
*   **Internet Connection**: Required for downloading software and dependencies.
*   **Administrator/Root Access**: You might need elevated permissions to install some tools.

## Essential Tools

We will primarily use the following tools and software:

1.  **Node.js and npm**: Docusaurus, our documentation framework, requires Node.js. `npm` (Node Package Manager) comes bundled with Node.js and is used to manage project dependencies.
    *   **Installation**: Download and install the latest LTS (Long Term Support) version from the official [Node.js website](https://nodejs.org/).
    *   **Verification**: Open a terminal and run:
        ```bash
        node -v
        npm -v
        ```
        You should see version numbers displayed.

2.  **Yarn (Optional but Recommended)**: Yarn is an alternative package manager that can sometimes offer faster and more reliable dependency management.
    *   **Installation**: After Node.js and npm are installed, run in your terminal:
        ```bash
        npm install -g yarn
        ```
    *   **Verification**: Run:
        ```bash
        yarn -v
        ```

3.  **Git**: Essential for version control and collaborating on code.
    *   **Installation**: Follow the instructions on the official [Git website](https://git-scm.com/downloads).
    *   **Verification**: Run:
        ```bash
        git --version
        ```

4.  **Visual Studio Code (VS Code)**: A popular, lightweight, and powerful code editor.
    *   **Installation**: Download from the official [VS Code website](https://code.visualstudio.com/).
    *   **Recommended Extensions**:
        *   **Markdown All in One**: For enhanced Markdown editing.
        *   **Prettier**: For code formatting.
        *   **ESLint**: For JavaScript/TypeScript linting.

## Next Steps

Once you have these tools installed and verified, your development environment will be ready. In the next lesson, we'll dive into setting up our first robotics project!