# Learning React - Movie App

A React learning project showcasing a movie discovery application with routing, component management, and state handling. Built with **React 19** and **Vite** for a modern development experience.

## 🎬 Project Overview

This application is a movie browser that allows users to:

- Browse movies on the home page
- View detailed movie cards with information
- Mark movies as favorites
- Navigate between Home and Favorites pages using React Router

## 📋 Features

- **React Router Integration** - Client-side routing for seamless navigation between pages
- **Component-Based Architecture** - Reusable components (MovieCard, NavBar)
- **State Management** - React hooks for managing favorites and app state
- **Responsive Design** - CSS styling for different screen sizes
- **Modern Tooling** - Vite for fast development and optimized builds
- **ESLint Configuration** - Code quality checks

## 🛠️ Tech Stack

- **Frontend Framework**: React 19.2.5
- **Build Tool**: Vite 8.0.9
- **Routing**: React Router DOM
- **Styling**: CSS (custom)
- **Linting**: ESLint 9

## 📦 Project Structure

```
frontend/
├── src/
│   ├── components/
│   │   ├── MovieCard.jsx      # Movie card component
│   │   └── NavBar.jsx          # Navigation bar
│   ├── pages/
│   │   ├── Home.jsx            # Home/browse movies page
│   │   └── Favorites.jsx       # Saved favorites page
│   ├── css/                    # Styling files
│   ├── assets/                 # Images and static files
│   ├── App.jsx                 # Main app component
│   ├── main.jsx                # React entry point
│   └── index.css               # Global styles
├── index.html                  # HTML template
├── vite.config.js              # Vite configuration
└── package.json                # Dependencies
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/daikictrl/Learning_React.git
cd Learning_React/frontend
```

2. Install dependencies:

```bash
npm install
```

3. Install React Router (if not already installed):

```bash
npm install react-router-dom
```

### Development Server

Start the development server with hot module reloading:

```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint Code

```bash
npm run lint
```

## 📚 Learning Concepts

This project demonstrates:

- React functional components with hooks (useState, useEffect)
- React Router for multi-page navigation
- Component props and state management
- CSS styling and responsive design
- Module bundling with Vite
- JavaScript ES6+ features

## 🎓 What I'm Learning

- Building reusable React components
- Implementing client-side routing
- Managing application state
- Working with modern build tools (Vite)
- React best practices and patterns

## 📝 Notes

- Make sure `react-router-dom` is installed in `package.json` for routing to work
- Use `npm run dev` to start the development server
- HMR (Hot Module Replacement) is enabled for instant feedback during development

## 📄 License

This is a learning project. Feel free to use it as reference material.

---

**Happy Learning! 🚀**
