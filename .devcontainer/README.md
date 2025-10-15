# Brandlift
Project Summary
BrandLift is a leading digital marketing and SEO consulting firm based in Los Angeles, California. The project aims to enhance online visibility and drive business growth through comprehensive digital marketing solutions. It offers services such as AI-powered SEO audits, website development, social media marketing (SMM), Google My Business (GMB) optimization, local SEO, and both paid and organic marketing strategies.

Project Module Description
AI-Powered SEO Audits: Comprehensive website analysis with actionable insights to boost search rankings.
Website Development: Custom, responsive websites built for performance and conversion optimization.
Social Media Marketing (SMM): Strategic campaigns to drive traffic, leads, and revenue growth.
Google My Business (GMB) Optimization: Local SEO strategies to dominate local search results.
Directory Tree
.
├── AI_SEO_Audit_Tool_Research_Framework.md  # Documentation for AI-powered SEO audit tool framework.
├── nextjs-admin-panel-auth.md                # Authentication module for admin panel in Next.js.
├── web_info_summaries/genkit-nextjs-seo-auditor.md  # SEO auditor tool documentation and features.
├── src                                      # Source code for the application.
│   ├── App.tsx                              # Main application entry point.
│   ├── components                            # UI components.
│   ├── contexts                              # Context providers for authentication and theme.
│   ├── pages                                 # Application pages including client and admin views.
│   └── lib                                   # Utility functions and interfaces.
└── package.json                              # Project metadata and dependencies.
File Description Inventory
AI_SEO_Audit_Tool_Research_Framework.md: Outlines the framework and functionalities for an AI-driven SEO audit tool.
nextjs-admin-panel-auth.md: Details the authentication process and setup for the Next.js admin panel.
web_info_summaries/genkit-nextjs-seo-auditor.md: Provides an overview of the GenKit Next.js SEO auditor, its features, and usage instructions.
src/App.tsx: Main application entry point that sets up routing and context providers.
src/components: Contains reusable UI components.
src/contexts: Contains context providers for managing global state.
src/pages: Contains the different pages of the application including the client dashboard and login pages.
src/lib: Contains utility functions and interfaces for client authentication.
Technology Stack
Frontend: Next.js, React, TypeScript, Tailwind CSS
Backend: Node.js
Data Storage: localStorage (no external database dependencies)
Other: APIs for Google services, SEO tools integration.
Usage
To install dependencies and run the project, follow these steps:

Clone the repository.
Navigate to the project directory.
Install dependencies:
pnpm install
Lint the project:
pnpm run lint
Build the project:
pnpm run build
Shadcn-UI Template Usage Instructions
technology stack
This project is built with:

Vite
TypeScript
React
shadcn-ui
Tailwind CSS
All shadcn/ui components have been downloaded under @/components/ui.

File Structure
index.html - HTML entry point
vite.config.ts - Vite configuration file
tailwind.config.js - Tailwind CSS configuration file
package.json - NPM dependencies and scripts
src/app.tsx - Root component of the project
src/main.tsx - Project entry point
src/index.css - Existing CSS configuration
src/pages/Index.tsx - Home page logic
Components
All shadcn/ui components are pre-downloaded and available at @/components/ui
Styling
Add global styles to src/index.css or create new CSS files as needed
Use Tailwind classes for styling components
Development
Import components from @/components/ui in your React components
Customize the UI by modifying the Tailwind configuration
Note
The @/ path alias points to the src/ directory
In your typescript code, don’t re-export types that you’re already importing
Commands
Install Dependencies

pnpm i
Add Dependencies

pnpm add some_new_dependency

**Start Preview**

```shell
pnpm run dev
To build

pnpm run build