Contributing to GeoTreasury.com
Welcome to the GeoTreasury.com project! We're building a pioneering Cardano-based e-commerce platform that addresses economic displacement through a novel Universal Basic Income (UBI) distribution system. By contributing to this project, you're helping to create a more equitable and sustainable economic future.
GeoTreasury.com leverages Cardano's blockchain infrastructure, Atala PRISM for identity verification, Charli3 Oracle for randomness, and Hydra for scalability. Our mission is to create an economic safety net that grows with digital commerce, ensuring that the benefits of automation are shared across society.
We appreciate your interest in contributing and look forward to collaborating with you!

Table of Contents

How to Contribute
Setting Up the Development Environment
Coding Standards and Best Practices
Reporting Issues and Suggesting Features
Project Repositories
Thank You for Contributing!


How to Contribute

Fork the Repository:Start by forking the repository you wish to contribute to. The GeoTreasury project is organized into several repositories under the GeoTreasury Git organization. See the Project Repositories section for details.

Clone Your Fork:Clone your forked repository to your local machine:  
git clone https://github.com/your-username/repository-name.git


Create a Branch:Create a new branch for your feature or bug fix. Use a descriptive name:  
git checkout -b feature/your-feature-name


Make Changes:Implement your changes while adhering to the project's Coding Standards and Best Practices.

Test Your Changes:Write and run tests to ensure your changes work as expected and do not introduce new issues. Refer to the repository's testing guidelines.

Commit Your Changes:Commit your changes with a clear and descriptive commit message:  
git commit -m "Add feature: your feature description"


Push to Your Fork:Push your changes to your forked repository:  
git push origin feature/your-feature-name


Submit a Pull Request:Open a pull request to the original repository. Provide a detailed description of your changes and reference any related issues.



Setting Up the Development Environment
Each repository may have specific setup instructions, so please refer to the README.md file in the respective repository for detailed guides. Generally, you'll need:

Node.js and npm for frontend and API development.
Haskell and Plutus for smart contract development.
Docker for containerized environments.
Git for version control.

Ensure you have the necessary tools and dependencies installed before starting development.

Coding Standards and Best Practices

Code Formatting:Follow the formatting guidelines specified in each repository. Use tools like Prettier for JavaScript/TypeScript and stylish-haskell for Haskell.

Testing:Write unit tests and integration tests for your code. Aim for high test coverage. Use frameworks like Jest for JavaScript and Hspec for Haskell.

Documentation:Document your code and update relevant documentation in the geotreasury-docs repository. Use JSDoc for JavaScript and Haddock for Haskell.

Commit Messages:Use clear and descriptive commit messages. Reference related issues where applicable (e.g., "Fixes #123").

Pull Requests:Provide a detailed description of your changes in pull requests. Include screenshots, logs, or test results if relevant.



Reporting Issues and Suggesting Features

Issues:If you encounter a bug or issue, check the issue tracker of the relevant repository to see if it has already been reported. If not, create a new issue with:  

A clear description of the problem.  
Steps to reproduce the issue.  
Any relevant logs, screenshots, or code snippets.


Feature Suggestions:We welcome new ideas! Create an issue with:  

A detailed description of the feature.  
Its benefits to the project.  
Potential implementation ideas or approaches.




Project Repositories
The GeoTreasury project is divided into specialized repositories to manage different components effectively:

geotreasury-coreCore logic, including Plutus smart contracts (treasury and side contracts), UBI distribution, and Cardano blockchain integration.

geotreasury-apiE-commerce API layer for ADA payment processing, merchant integration, and UBI allocation.

geotreasury-identityIdentity verification using Atala PRISM for DID management and eligibility checks.

geotreasury-randomnessIntegration with Charli3 Oracle for verifiable randomness in UBI recipient selection.

geotreasury-scalabilityScalability solutions, such as Hydra Heads for off-chain processing.

geotreasury-notificationsMulti-channel notification system for recipients (email, Atala PRISM, on-chain).

geotreasury-reportingTransparency reporting with automated report generation and blockchain explorer integration.

geotreasury-frontendUser interface for recipient onboarding, merchant dashboards, and community governance.

geotreasury-docsComprehensive documentation, including API guides, integration instructions, and user manuals.



Thank You for Contributing!
Your contributions are invaluable to the success of GeoTreasury.com. By participating, you're helping to build a platform that can make a real difference in addressing economic inequality. We appreciate your time and effort and look forward to seeing your contributions!
If you have any questions or need assistance, feel free to reach out to the project maintainers or join our community channels.
