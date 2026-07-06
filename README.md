# OSS SearchLab

OSS SearchLab is a powerful, AI-driven search engine designed for discovering and analyzing open source repositories across the globe. By leveraging the Gemini AI API, OSS SearchLab not only finds the best tools, libraries, and frameworks on platforms like GitHub but also summarizes, categorizes, and provides deep insights into them—all customized for your preferred language and context.

## Key Features

- **AI-Powered Search & Insights**: Understand at a glance what a repository does and why it's popular through concise, intelligent summaries.
- **Trending Repositories**: Discover the most active and trending open source projects daily, weekly, or monthly, complete with AI executive briefs.
- **Deep Dive Reports**: Generate in-depth architectural and usage analysis for any repository, comparing it to alternatives, understanding its tech stack, and more.
- **Multi-language Support**: Search and view AI-generated insights naturally translated into multiple languages (e.g., English, Japanese, German, Spanish, French, Chinese).
- **Persona & Audience Targeting**: Customize the AI's tone (e.g., "Cozy Big Sister", "Hustler PM", "Net-Neet") to receive insights perfectly tuned for your context and humor.
- **Built-in Bookmarks**: Easily save your favorite repositories to review them later.

## Architecture & Tech Stack

This is a modern full-stack web application built with:

- **Frontend**: React 18, Vite, Tailwind CSS, and Lucide Icons.
- **Backend**: Express (Node.js) server acting as a proxy and orchestrator for GitHub API and Gemini API.
- **AI Integration**: The `@google/genai` TypeScript SDK is used for robust, structured output generation, leveraging the Gemini 3.5 capabilities securely on the server.
- **Styling**: Tailwind CSS for responsive, mobile-first design, adhering to modern UI/UX craftsmanship.

## Getting Started

1. Set your `GEMINI_API_KEY` in the environment (`.env`).
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.
4. Enjoy exploring the open source ecosystem with AI!
