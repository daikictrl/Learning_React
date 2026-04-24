# Repository Guidelines

## Project Structure & Module Organization
This is a React 19 application built with Vite, following a modular component-based architecture:
- **`src/components/`**: Reusable UI components (e.g., `MovieCard`, `NavBar`).
- **`src/pages/`**: Main page views (`Home`, `Favorites`) that serve as route targets.
- **`src/contexts/`**: Global state management using React Context API (`MovieContext`).
- **`src/services/`**: External API interactions (e.g., `api.js` for movie data).
- **`src/css/`**: Component-specific stylesheets. Ensure CSS file names match their respective component names where applicable.

## Build, Test, and Development Commands
- **Start Development Server**: `npm run dev`
- **Build Production Bundle**: `npm run build`
- **Lint Codebase**: `npm run lint`
- **Preview Production Build**: `npm run preview`

## Coding Style & Naming Conventions
- **Framework**: React 19 with Vite.
- **Language**: Modern JavaScript (ESM). Use `.jsx` extension for files containing JSX.
- **State Management**: Prefer React Hooks (`useState`, `useEffect`) and Context API for cross-component state.
- **Linting**: Rules are enforced via `eslint.config.js`. Note that `no-unused-vars` is set to error except for variables matching `^[A-Z_]`.
- **Naming**: Use PascalCase for components and camelCase for hooks and utilities.

## Commit & Pull Request Guidelines
- **Message Format**: Use concise, descriptive messages starting with an imperative verb (e.g., "Fix API base URL", "Add MovieContext provider").
- **Patterns**: Follow the existing pattern of atomic commits that focus on specific fixes or features.
