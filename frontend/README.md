# RD-AI-Dashboard — Frontend

The frontend for **RD-AI-Dashboard**, an AI-powered BMW Sales Intelligence Dashboard designed to make business data exploration more intuitive.

Built with Next.js, React, and TypeScript, this application provides the user interface for exploring AI-assisted analytics and data visualizations.

## Features

- Modern web interface built with Next.js
- Responsive layout for dashboard experiences
- TypeScript support for maintainable code
- Designed to integrate with a Python backend
- Intended for natural-language-driven sales analytics

## Tech Stack

- **Framework:** Next.js
- **UI Library:** React
- **Language:** TypeScript
- **Styling:** CSS
- **Package Manager:** npm

## Getting Started

### Prerequisites

Install [Node.js](https://nodejs.org/) and npm.

### Installation

From the frontend directory, run:

```bash
npm install
```

### Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

You can edit the application by modifying files in the `app/` directory. The development server refreshes the page as you make changes.

## Available Scripts

Check `package.json` for the scripts supported by this project. The standard Next.js development command is:

```bash
npm run dev
```

## Project Structure

```text
frontend/
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   ├── page.tsx
│   └── favicon.ico
├── public/
├── package.json
├── package-lock.json
├── next.config.ts
└── tsconfig.json
```

## Backend Integration

The application is designed to work with the project's Python backend. Configure the backend URL and any required environment variables according to the actual application setup.

Never expose API keys or private credentials in frontend code.

## Deployment

The frontend can be deployed to a compatible Next.js hosting platform, such as [Vercel](https://vercel.com/), after configuring the required environment variables and backend connection.

## Related Documentation

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)

---

Part of the **RD-AI-Dashboard** project.
