# Halfagiraf Pages Demo - Agent Scaffold

Generated: 2026-02-12T23:17:14.125Z
Repo: https://github.com/stevenmcsorley/botdemo
Linear project: https://linear.app/halfagiraf/project/halfagiraf-pages-demo-a5176358a792
Pages: GitHub Pages scaffold added (site/ + .github/workflows/pages.yml).

## Objective
build a simple creative web app and deploy on GitHub Pages

## Stage Summaries

### Research
# Research Brief: Botdemo Repository Analysis
**Project:** Halfagiraf Pages Demo

## 1) Current Architecture
*   The site is a static GitHub Pages demo, presenting marketing content for GitHub's product categories (AI tools, workflows, security).
*   It uses a simple, informational architecture organized by user segments (company size, use case, industry) and product features.
*   The architecture is purely front-end, lacking any backend services, conversational logic, or bot-specific components like NLP engines or dialogue managers.

## 2) Gaps
*   **No Bot Framework:** Lacks core chatbot components such as a natural language understanding (NLU) layer, dialogue management, or integration APIs, as defined by standard bot architectures (Rocket.Chat, Microsoft Bot Framework).
*   **Static Interaction:** The site is informational only, with no interactive conversational interface, user input handling, or response generation capabilities.
*   **Absence of MLOps Pipeline:** Missing the infrastructure for training, deploying, and maintaining an AI/ML model, which is critical for an intelligent chatbot (as highlighted in r/mlops discussions).

## 3) Risks
*   **Misleading Scope:** The repository name "botdemo" suggests a functional chatbot example, but it is a static marketing page, creating potential confusion and misaligned user expectations.
*   **Scalability & Complexity:** Building an actual bot on this foundation would require a complete architectural overhaul, introducing significant complexity in state management, security, and channel integrations.
*   **Maintenance Overhead:** Adding dynamic bot functionality would shift the project from low-maintenance static pages to requiring ongoing model training, monitoring, and dependency updates.

## 4) Quick Wins
*   **Integrate a Frontend Demo:** Embed a simple, pre-built chatbot UI widget (e.g., using a service like JointJS's demo components) to provide visual interactivity without a complex backend.
*   **Clarify Repository Purpose:** Update the README to explicitly state that this is a **GitHub Pages product showcase demo**, not a functional bot codebase, to manage expectations.
*   **Add Architecture Documentation:** Create a basic document outlining a proposed future-state bot architecture, referencing diagrams and concepts from Engati or Microsoft's solutions handbook.

## 5) Next Milestones
*   **Define Bot Scope:** Decide if the goal is a simple rule-based FAQ bot (lower effort) or an AI-driven assistant (requires NLU/model integration).
*   **Select a Core Framework:** Choose a foundational technology stack (e.g., Microsoft Bot Framework, Rocket.Chat Bots architecture) to structure development.
*   **Build a Minimal Viable Bot (MVB):** Implement a single, narrow use case (e.g., answering questions from a static document) with a basic dialogue flow and a test deployment.

Sources:
1. Bots Architecture
https://developer.rocket.chat/docs/bots-architecture
2. Architecture
https://microsoft.github.io/botframework-solutions/skills/handbook/architecture/
3. r/mlops on Reddit: Chatbot architecture recommendations and help request
https://www.reddit.com/r/mlops/comments/1eubbd7/chatbot_architecture_recommendations_and_help/
4. Chatbot – Demo applications & examples
https://www.jointjs.com/demos/chatbot
5. Chatbot Architecture | Engati
https://www.engati.ai/glossary/chatbot-architecture
Research report saved: `data/research-reports/2026-02-12T23-16-12-528Z-research-with-5-external-sources...

### Repo Audit
Repository analysis: stevenmcsorley/botdemo (branch: main)
## Implemented (with file evidence)
*   `README.md:1-2` – Repository exists with a name and a high-level description "Halfagiraf GitHub Pages demo".

## Missing or Incomplete (with file evidence)
*   `README.md:1-3` – The README is minimal and lacks essential project documentation. It is missing a clear statement of purpose, setup/installation instructions, and deployment guidance for GitHub Pages.
*   No `package.json` file is present in the provided excerpts. This is required to define project dependencies, scripts (e.g., `dev`, `build`), and the project's Node.js environment.
*   No `index.html` file is present in the provided excerpts. This is the essential entry point for a web application and is required for GitHub Pages to serve content.
*   No application source code (e.g., `src/` directory, `App.jsx`, `main.jsx`) is present in the provided excerpts. The repository lacks the core creative web app implementation.
*   No build configuration (e.g., `vite.config.js`) is present. This is needed to configure the build tool for static asset output compatible with GitHub Pages.
*   No GitHub Actions workflow file (e.g., `.github/workflows/deploy.yml`) is present. This is the standard method to automate build and deployment to GitHub Pages.
*   No static deployment directory (e.g., `dist/`, `build/`, or `.nojekyll` file) is present. The repository lacks the built artifacts or configuration needed for Pages to host the site.

## Next Actions
1.  Create a `package.json` to define the project, its dependencies (e.g., React, Vite), and npm scripts for `dev`, `build`, and `preview`.
2.  Scaffold the core application: create `index.html`, `src/main.jsx`, and `src/App.jsx` to build a simple, creative React-based web app.
3.  Add a build configuration file (`vite.config.js` or equivalent) to set the correct `base` path and output directory for GitHub Pages deployment.
4.  Create a GitHub Actions workflow (`.github/workflows/deploy.yml`) to build the site and deploy it to the `gh-pages` branch on every push to `main`.
5.  Update the `README.md` with clear instructions for local development, a description of the app, and a link to the live GitHub Pages site.

Code evidence files:
- README.md

### Planning
Created 10 planning issues in project "Halfagiraf Pages Demo".
- https://linear.app/halfagiraf/issue/HAL-52/halfagiraf-pages-demo-task-1
- https://linear.app/halfagiraf/issue/HAL-53/halfagiraf-pages-demo-task-2
- https://linear.app/halfagiraf/issue/HAL-54/halfagiraf-pages-demo-task-3
- https://linear.app/halfagiraf/issue/HAL-55/halfagiraf-pages-demo-task-4
- https://linear.app/halfagiraf/issue/HAL-56/halfagiraf-pages-demo-task-5
- https://linear.app/halfagiraf/issue/HAL-57/halfagiraf-pages-demo-task-6
- https://linear.app/halfagiraf/issue/HAL-58/halfagiraf-pages-demo-task-7
- https://linear.app/halfagiraf/issue/HAL-59/halfagiraf-pages-demo-task-8
- https://linear.app/halfagiraf/issue/HAL-60/halfagiraf-pages-demo-task-9
- https://linear.app/halfagiraf/issue/HAL-61/halfagiraf-pages-demo-task-10

## Planning Issue Links
1. https://linear.app/halfagiraf/issue/HAL-52/halfagiraf-pages-demo-task-1
2. https://linear.app/halfagiraf/issue/HAL-53/halfagiraf-pages-demo-task-2
3. https://linear.app/halfagiraf/issue/HAL-54/halfagiraf-pages-demo-task-3
4. https://linear.app/halfagiraf/issue/HAL-55/halfagiraf-pages-demo-task-4
5. https://linear.app/halfagiraf/issue/HAL-56/halfagiraf-pages-demo-task-5
6. https://linear.app/halfagiraf/issue/HAL-57/halfagiraf-pages-demo-task-6
7. https://linear.app/halfagiraf/issue/HAL-58/halfagiraf-pages-demo-task-7
8. https://linear.app/halfagiraf/issue/HAL-59/halfagiraf-pages-demo-task-8
9. https://linear.app/halfagiraf/issue/HAL-60/halfagiraf-pages-demo-task-9
10. https://linear.app/halfagiraf/issue/HAL-61/halfagiraf-pages-demo-task-10

## Next
- Run the project locally (manual).
- Paste test output and errors into Slack to trigger iterate fixes.
- Enable GitHub Pages for this repo (Settings -> Pages -> Build and deployment: GitHub Actions).
