# Reown AppKit
A custom Safe{App} template for Reown integrations.Reown Documentation

This repository contains the documentation for Reown. The documentation is built using Mintlify.

Contributing to the Documentation

We welcome contributions to improve our documentation! Here's how you can help:

Creating a Pull Request

Fork the repository
Create a new branch for your changes:
git checkout -b feature/your-feature-name
Make your changes to the documentation files
Commit your changes:
git add .
git commit -m "Description of your changes"
Push your changes to your fork:
git push origin feature/your-feature-name
Create a Pull Request from your fork to the main repository
Fill out the PR template with a description of your changes
A team member will review your PR.
Running the Documentation Locally

To run the documentation locally, you'll need to have Node.js installed on your machine. Then follow these steps:

Install dependencies:
pnpm install
Run the development server:
pnpm run dev
or

Install the Mintlify CLI globally:

npm install -g mintlify
Clone the repository:

git clone https://github.com/your-username/reown-docs.git
cd reown-docs
Start the development server:

mintlify dev
Open your browser and navigate to http://localhost:3000 to view the documentation

The development server will automatically reload when you make changes to the documentation files.

Documentation Structure

/api - API documentation
/advanced - Advanced usage guides
/appkit - AppKit documentation
/cloud - Cloud documentation
/components - UI components documentation
/snippets - Code snippets and examples
/web3modal - Web3Modal documentation
/walletkit - WalletKit documentation
Writing Documentation

Documentation files are written in MDX format
Images should be placed in the /images directory
Follow the existing documentation style and formatting
Use clear and concise language
Include code examples where appropriate
Test all code snippets to ensure they work as expected
Building a project with AI?

If you're using Cursor IDE (or another AI-based IDE) to build a project with Reown AppKit, we provide a .mdc file that enhances your development experience. The reown-appkit.mdc file in this repository contains Cursor-specific rules and type hints for Reown AppKit.

To use it in your project:

Copy the reown-appkit.mdc file from this repository
Create a .cursor/rules folder in your project's root directory (if it doesn't exist)
Place the .mdc file in your project's .cursor/rules folder
For more info, refer to Cursor's documentation.

Need Help?

If you have any questions or need help with your contribution, please:

Check the existing documentation
Reach out to the team on Discord
Thank you for contributing to Reown's documentation!

