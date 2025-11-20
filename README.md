# verve-web

A modern web application built with PNPM, Vite, React, and TypeScript.

## Prerequisites

- Node.js (v18 or higher recommended)
- PNPM (v8 or higher)

## Getting Started

### Install Dependencies

```bash
pnpm install
```

### Development

Start the development server with hot module replacement:

```bash
pnpm run dev
```

The application will be available at `http://localhost:5173/`

### Build

Build the project for production:

```bash
pnpm run build
```

The built files will be output to the `dist/` directory.

### Preview

Preview the production build locally:

```bash
pnpm run preview
```

## Tech Stack

- **Build Tool**: Vite
- **Framework**: React 19
- **Language**: TypeScript
- **Package Manager**: PNPM

## Project Structure

```
verve-web/
├── public/          # Static assets
├── src/
│   ├── assets/      # Application assets (images, fonts, etc.)
│   ├── App.tsx      # Main App component
│   ├── App.css      # App component styles
│   ├── main.tsx     # Application entry point
│   └── index.css    # Global styles
├── index.html       # HTML entry point
├── vite.config.ts   # Vite configuration
├── tsconfig.json    # TypeScript configuration
└── package.json     # Project dependencies
```

