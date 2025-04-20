# 10x-cards

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/your-repository/10x-cards)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Table of Contents
- [Project Description](#project-description)
- [Tech Stack](#tech-stack)
- [Getting Started Locally](#getting-started-locally)
- [Available Scripts](#available-scripts)
- [Project Scope](#project-scope)
- [Project Status](#project-status)
- [License](#license)

## Project Description
10x-cards is an innovative educational tool that allows users to quickly create and manage sets of flashcards. Leveraging advanced AI technologies, the application generates flashcard suggestions from provided text, streamlining the learning process through spaced repetition. This tool aims to simplify the creation and management of high-quality flashcards for efficient studying.

## Tech Stack
- **Frontend:** Angular 18, SCSS, Angular Material
- **Backend:** Supabase (PostgreSQL database, built-in authentication, multiple SDKs)
- **AI Integration:** Openrouter.ai (access to models such as OpenAI, Anthropic, Google, etc.)
- **CI/CD & Hosting:** GitHub Actions for CI/CD pipelines and DigitalOcean (Docker-based deployment)

## Getting Started Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Bl4ckburn/10x-cards.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd 10x-cards
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Ensure you are using Node version v22.14.0 (as specified in `.nvmrc`):**
   ```bash
   nvm use
   ```
5. **Start the development server:**
   ```bash
   npm start
   ```

## Available Scripts
The following scripts are available as defined in the `package.json`:

- **`ng`:** Run Angular CLI commands.
- **`npm start`:** Launches the development server using Angular (`ng serve`).
- **`npm run build`:** Compiles the project for production.
- **`npm run watch`:** Builds the project in watch mode for development.
- **`npm test`:** Executes the unit tests.
- **`npm run lint`:** Runs the linter to check code quality.

## Project Scope
- **Automated Flashcard Generation:** Paste text to generate flashcard suggestions using AI integration.
- **Manual Flashcard Management:** Create, edit, and delete flashcards as needed.
- **User Authentication:** Register and log in to manage personal flashcards securely.
- **Spaced Repetition:** Utilize a spaced repetition algorithm to optimize learning sessions.
- **Statistics Tracking:** Monitor the number and acceptance rate of AI-generated flashcards.

*Note: This project is in the MVP stage, focusing on essential functionalities with plans for future enhancements.*

## Project Status
This project is currently under active development and is in its MVP stage.

## License
This project is licensed under the MIT License.
