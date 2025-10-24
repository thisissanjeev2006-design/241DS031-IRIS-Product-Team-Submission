# ⚛️ React + Vite + Tailwind CSS Project

A modern, fast, and responsive web application built using **React 18**, **Vite**, and **Tailwind CSS**.  
Designed for scalability, maintainability, and developer productivity — perfect for building high-performance modern web experiences.

---

## 🚀 Features

- ⚡ **Vite** — Next-generation build tool for instant server startup and lightning-fast HMR.  
- ⚛️ **React 18** — Leverages concurrent rendering and performance improvements.  
- 🎨 **Tailwind CSS** — Utility-first CSS framework with full customization.  
- 🧭 **React Router v6** — Declarative routing for seamless navigation.  
- 🧩 **Modular Architecture** — Clean folder structure for scalability and readability.  
- 📱 **Responsive UI** — Mobile-first, adaptive layouts for all screen sizes.  
- 🔧 **PostCSS + Autoprefixer** — Automatic vendor prefixing and modern CSS features.  

---

## 💡 Design Rationale

This project was built with the goal of **creating a lightweight, high-performance React setup** that prioritizes **developer efficiency and scalability**.  

**Key design principles:**
- **Simplicity:** Avoid unnecessary boilerplate by using Vite’s minimal setup.
- **Maintainability:** Modular folder structure (`components`, `pages`, `styles`) to ensure easy scaling.
- **Performance:** Vite’s ESBuild-based bundling ensures fast development and optimized production builds.
- **Consistency:** Tailwind CSS enforces a consistent design language using utility-first styling.
- **Reusability:** Component-driven architecture to promote reusable UI blocks.

---

## 🧩 Features Implemented

- ✅ Dynamic routing with `React Router`
- ✅ Responsive navigation bar and footer
- ✅ Reusable UI components (buttons, cards, headers, etc.)
- ✅ Theme and color customization using `tailwind.config.js`
- ✅ Global and page-specific styles using Tailwind utilities
- ✅ Error handling and 404 routes
- ✅ Build and deployment-ready configuration

## 📋 Prerequisites

- Node.js (v14.x or higher)
- npm or yarn


## 🛠️ Installation

1. Install dependencies:
  ```bash
  npm install
  # or
  yarn install
  ```

2. Start the server:
  ```bash
  npm run start
  # or
  yarn start
  ```

## 📁 Project Structure

```
/
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Page components
│   ├── styles/          # Global styles and Tailwind configuration
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Application entry point
│   └── Routes.jsx       # Application routes
├── index.html           # HTML template
├── package.json         # Project dependencies and scripts
├── postcss.config.js    # PostCSS configuration for Tailwind
├── tailwind.config.js   # Tailwind CSS configuration
├── vite.config.js       # Vite configuration
```

## 🧩 Adding Routes

To add new routes to the application, update the `Routes.jsx` file:

```jsx
import React from 'react';
import { BrowserRouter as Router, Routes, Route } from 'react-router-dom';

// Import page components
import HomePage from "./pages/HomePage";
import AboutPage from "./pages/AboutPage";

const AppRoutes = () => {
  return (
    <Router>
      <Routes>
        <Route path="/" element={<HomePage />} />
        <Route path="/about" element={<AboutPage />} />
      </Routes>
    </Router>
  );
};

export default AppRoutes;
```

## 🎨 Styling

This project uses Tailwind CSS for styling. The configuration includes:

- Utility-first approach for rapid development
- Custom theme configuration
- Responsive design utilities
- PostCSS and Autoprefixer integration

🌐 Live Demo

🔗 Live Demo: https://iris-student-academic-portal-xyn9k67.public.builtwithrocket.new/
