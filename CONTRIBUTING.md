# Contributing to GeoTreasury.com

Welcome to the GeoTreasury.com project! We're building a pioneering Cardano-based e-commerce platform that addresses economic displacement through a novel Universal Basic Income (UBI) distribution system. By contributing to this project, you're helping to create a more equitable and sustainable economic future.

GeoTreasury.com leverages Cardano's blockchain infrastructure, Atala PRISM for identity verification, Charli3 Oracle for randomness, and Hydra for scalability. Our mission is to create an economic safety net that grows with digital commerce, ensuring that the benefits of automation are shared across society.

We appreciate your interest in contributing and look forward to collaborating with you!

---

## Table of Contents
- [How to Contribute](#how-to-contribute)
- [Setting Up the Development Environment](#setting-up-the-development-environment)
- [Coding Standards and Best Practices](#coding-standards-and-best-practices)
- [Reporting Issues and Suggesting Features](#reporting-issues-and-suggesting-features)
- [Project Repositories](#project-repositories)
- [Thank You for Contributing!](#thank-you-for-contributing)

---

## How to Contribute

1. **Fork the Repository**:  
   Start by forking the repository you wish to contribute to. The GeoTreasury project is organized into several repositories under the [GeoTreasury Git organization](https://github.com/geotreasury). See the [Project Repositories](#project-repositories) section for details.

2. **Clone Your Fork**:  
   Clone your forked repository to your local machine:  
   ```
   git clone https://github.com/your-username/repository-name.git
   ```

3. **Create a Branch**:  
   Create a new branch for your feature or bug fix. Use a descriptive name:  
   ```
   git checkout -b feature/your-feature-name
   ```

4. **Make Changes**:  
   Implement your changes while adhering to the project's [Coding Standards and Best Practices](#coding-standards-and-best-practices).

5. **Test Your Changes**:  
   Write and run tests to ensure your changes work as expected and do not introduce new issues. Refer to the repository's testing guidelines.

6. **Commit Your Changes**:  
   Commit your changes with a clear and descriptive commit message:  
   ```
   git commit -m "Add feature: your feature description"
   ```

7. **Push to Your Fork**:  
   Push your changes to your forked repository:  
   ```
   git push origin feature/your-feature-name
   ```

8. **Submit a Pull Request**:  
   Open a pull request to the original repository. Provide a detailed description of your changes and reference any related issues.

---

## Setting Up the Development Environment

Each repository may have specific setup instructions, so please refer to the `README.md` file in the respective repository for detailed guides. Generally, you'll need:

- **Node.js** and **npm** for frontend and API development.
- **Haskell** and **Plutus** for smart contract development.
- **Docker** for containerized environments.
- **Git** for version control.

Ensure you have the necessary tools and dependencies installed before starting development.

---

## Coding Standards and Best Practices

- **Code Formatting**:  
  Follow the formatting guidelines specified in each repository. Use tools like [Prettier](https://prettier.io/) for JavaScript/TypeScript and [stylish-haskell](https://github.com/haskell/stylish-haskell) for Haskell.

- **Testing**:  
  Write unit tests and integration tests for your code. Aim for high test coverage. Use frameworks like [Jest](https://jestjs.io/) for JavaScript and [Hspec](https://hspec.github.io/) for Haskell.

- **Documentation**:  
  Document your code and update relevant documentation in the `geotreasury-docs` repository. Use [JSDoc](https://jsdoc.app/) for JavaScript and [Haddock](https://haskell-haddock.readthedocs.io/) for Haskell.

- **Commit Messages**:  
  Use clear and descriptive commit messages. Reference related issues where applicable (e.g., "Fixes #123").

- **Pull Requests**:  
  Provide a detailed description of your changes in pull requests. Include screenshots, logs, or test results if relevant.

---

## Reporting Issues and Suggesting Features

- **Issues**:  
  If you encounter a bug or issue, check the issue tracker of the relevant repository to see if it has already been reported. If not, create a new issue with:  
  - A clear description of the problem.  
  - Steps to reproduce the issue.  
  - Any relevant logs, screenshots, or code snippets.

- **Feature Suggestions**:  
  We welcome new ideas! Create an issue with:  
  - A detailed description of the feature.  
  - Its benefits to the project.  
  - Potential implementation ideas or approaches.

---

## Project Repositories

The GeoTreasury project is divided into specialized repositories to manage different components effectively:

- **`geotreasury-core`**  
  Core logic, including Plutus smart contracts (treasury and side contracts), UBI distribution, and Cardano blockchain integration.

- **`geotreasury-api`**  
  E-commerce API layer for ADA payment processing, merchant integration, and UBI allocation.

- **`geotreasury-identity`**  
  Identity verification using Atala PRISM for DID management and eligibility checks.

- **`geotreasury-randomness`**  
  Integration with Charli3 Oracle for verifiable randomness in UBI recipient selection.

- **`geotreasury-scalability`**  
  Scalability solutions, such as Hydra Heads for off-chain processing.

- **`geotreasury-notifications`**  
  Multi-channel notification system for recipients (email, Atala PRISM, on-chain).

- **`geotreasury-reporting`**  
  Transparency reporting with automated report generation and blockchain explorer integration.

- **`geotreasury-frontend`**  
  User interface for recipient onboarding, merchant dashboards, and community governance.

- **`geotreasury-docs`**  
  Comprehensive documentation, including API guides, integration instructions, and user manuals.

---

## Thank You for Contributing!

Your contributions are invaluable to the success of GeoTreasury.com. By participating, you're helping to build a platform that can make a real difference in addressing economic inequality. We appreciate your time and effort and look forward to seeing your contributions!

If you have any questions or need assistance, feel free to reach out to the project maintainers or join our community channels.