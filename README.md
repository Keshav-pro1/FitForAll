# FitForAll

A sports training platform for everyone, built with React, TypeScript, and Tailwind CSS.

## Overview

FitForAll makes sport-specific training accessible to everyone, regardless of level. It combines guided training content with a fast, animated, responsive interface and secure user authentication.

## Features

- User authentication and account management (Clerk)
- Video-based training content (React Player)
- Smooth animations and transitions (GSAP, Framer Motion)
- Client-side routing across multiple pages (React Router)
- Responsive, utility-first UI (Tailwind CSS)

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 18 + TypeScript |
| Build tool | Vite 5 |
| Styling | Tailwind CSS, PostCSS, clsx, tailwind-merge |
| Routing | React Router v6 |
| Auth | Clerk |
| Animation | GSAP, Framer Motion |
| Media | React Player |
| Icons | Lucide React, Font Awesome |
| Linting | ESLint, typescript-eslint |

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Installation

```bash
git clone https://github.com/Keshav-pro1/FitForAll.git
cd FitForAll
npm install
```

### Environment Variables

Create a `.env` file in the project root:

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

Get the key from your [Clerk dashboard](https://dashboard.clerk.com).

### Run

```bash
npm run dev
```

The app runs at `http://localhost:5173`.

## Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## Project Structure

```
FitForAll/
├── src/                 # Application source code
├── index.html           # Entry HTML
├── vite.config.ts       # Vite configuration
├── tailwind.config.js   # Tailwind configuration
├── postcss.config.js    # PostCSS configuration
├── eslint.config.js     # ESLint configuration
└── tsconfig*.json       # TypeScript configuration
```

## Contributing

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a pull request

## Author

**Keshav** — [@Keshav-pro1](https://github.com/Keshav-pro1)
