🎬 CineVault
A Modern Movie Discovery & Watchlist Application
Discover, explore, and organize your favorite movies with a beautiful, responsive interface

🌐 Live Demo | 📱 Mobile Optimized | ⚡ Fast & Responsive

React Vite TailwindCSS React Router JavaScript ESLint

License Version

🌟 About CineVault
CineVault is a modern, responsive movie discovery application that allows users to explore the latest and greatest films. Built with cutting-edge web technologies, it provides an intuitive interface for browsing movies, filtering by genres, and maintaining a personalized watchlist.

🎯 Key Highlights
🔍 Smart Search - Instantly search through thousands of movies
🎭 Genre Filtering - Browse movies by your favorite genres
⭐ Personal Watchlist - Save movies to watch later with persistent storage
📱 Responsive Design - Seamless experience across all devices
⚡ Performance Optimized - Fast loading with modern build tools
🎨 Modern UI/UX - Beautiful, intuitive interface with smooth animations
🚀 Quick Start
Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v18.0.0 or higher)
npm or yarn
Installation
Clone the repository

git clone https://github.com/your-username/cinevault.git
cd cinevault
Install dependencies

npm install
# or
yarn install
Start the development server

npm run dev
# or
yarn dev
Open your browser Navigate to http://localhost:5173

🎉 You're all set! Start exploring movies right away.

🌐 Live Demo
Experience CineVault in action: https://cinevault-beta.vercel.app/

✨ Features
🎬 Core Functionality
Movie Discovery - Browse trending and popular movies
Advanced Search - Find specific movies with real-time search
Genre Filtering - Filter movies by Action, Comedy, Drama, Horror, and more
Detailed Movie Cards - View ratings, release dates, and movie posters
Watchlist Management - Add/remove movies from your personal watchlist
Persistent Storage - Your watchlist is automatically saved locally
🎨 User Experience
Responsive Design - Optimized for desktop, tablet, and mobile devices
Smooth Animations - Engaging hover effects and transitions
Intuitive Navigation - Easy-to-use interface with React Router
Fast Performance - Optimized with Vite for lightning-fast loading
Modern UI - Clean design with Tailwind CSS
🛠️ Tech Stack
Frontend Framework
React

React 19 - Latest React version with improved performance and features
React Hooks - State management with useState, useContext, and useEffect
React Icons - Beautiful icon library for enhanced UI
Routing & Navigation
React Router

React Router DOM v7 - Client-side routing for seamless navigation
Styling & UI
TailwindCSS PostCSS

Tailwind CSS - Utility-first CSS framework for rapid UI development
PostCSS - CSS processing and optimization
Autoprefixer - Automatic vendor prefixing for browser compatibility
Build Tools & Development
Vite ESLint

Vite - Next-generation frontend build tool with HMR
ESLint - Code linting and formatting for maintainable code
ES Modules - Modern JavaScript module system
External APIs
TMDB

The Movie Database (TMDB) API - Comprehensive movie data and imagery
📁 Project Structure
cinevault/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── GenreFilter.jsx      # Genre filtering component
│   │   └── Moviecard.jsx        # Individual movie card component
│   ├── context/
│   │   └── WatchListContext.jsx # Global state for watchlist
│   ├── pages/
│   │   ├── Home.jsx             # Main movie discovery page
│   │   ├── Navbar.jsx           # Navigation component
│   │   └── WatchList.jsx        # User's saved movies page
│   ├── App.jsx                  # Main application component
│   ├── App.css                  # Global styles
│   ├── index.css                # Tailwind imports and base styles
│   └── main.jsx                 # Application entry point
├── eslint.config.js             # ESLint configuration
├── index.html                   # HTML template
├── package.json                 # Dependencies and scripts
├── postcss.config.js            # PostCSS configuration
├── tailwind.config.js           # Tailwind CSS configuration
└── vite.config.js               # Vite configuration
�️ Screenshots
🏠 Home Page
Browse popular and trending movies with smooth animations

Home Page

🔍 Search & Filter
Find specific movies and filter by genres

Search Results

⭐ Personal Watchlist
Manage your saved movies with persistent storage

Watchlist

🎮 Usage Guide
🔍 Discovering Movies
Browse Popular Movies - Scroll through trending movies on the home page
Search for Specific Films - Use the search bar to find particular movies
Filter by Genre - Click on genre buttons to explore specific categories
View Movie Details - Each card shows ratings, release date, and synopsis
⭐ Managing Your Watchlist
Adding Movies - Click the heart icon (❤️) on any movie card
Viewing Your List - Navigate to the "Watchlist" page via the navbar
Removing Movies - Click the filled heart icon to remove from watchlist
Persistent Storage - Your watchlist automatically saves to local storage
📱 Mobile Experience
Responsive Design - Optimized for all screen sizes
Touch-Friendly - Large click targets for mobile users
Fast Loading - Optimized images and lazy loading
🔧 Development
Available Scripts
# Start development server with hot reload
npm run dev

# Build for production
npm run build

# Run ESLint for code quality
npm run lint

# Preview production build locally
npm run preview
🛠️ Development Setup
Fork the repository
Clone your fork
git clone https://github.com/YOUR_USERNAME/cinevault.git
Create a feature branch
git checkout -b feature/amazing-feature
Make your changes
Test your changes
npm run dev
npm run lint
Commit and push
git commit -m "Add amazing feature"
git push origin feature/amazing-feature
Create a Pull Request
🔧 Configuration
Environment Variables
Create a .env file in the root directory:

VITE_TMDB_API_KEY=your_tmdb_api_key_here
VITE_TMDB_BASE_URL=https://api.themoviedb.org/3
Tailwind CSS Customization
Modify tailwind.config.js to customize the design system:

export default {
  content: ['./index.html', './src/**/*.{js,ts,jsx,tsx}'],
  theme: {
    extend: {
      // Add custom colors, fonts, etc.
    },
  },
  plugins: [],
}
🤝 Contributing
We welcome contributions from the community! Whether you're fixing bugs, adding features, or improving documentation, your help is appreciated.

🚀 Quick Contribution Guide
⭐ Star this repository - Show your support!
🍴 Fork the project - Create your own copy
🌟 Create a feature branch - git checkout -b feature/AmazingFeature
� Commit your changes - git commit -m 'Add some AmazingFeature'
📤 Push to the branch - git push origin feature/AmazingFeature
🔄 Open a Pull Request - Submit your contribution
🐛 Bug Reports & Feature Requests
Found a bug? Open an issue
Have an idea? Request a feature
Want to discuss? Start a discussion
📋 Contribution Guidelines
Follow the existing code style and conventions
Add tests for new features when applicable
Update documentation for any new functionality
Ensure your code passes ESLint checks
Test your changes thoroughly before submitting
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

MIT License

Copyright (c) 2025 CineVault

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
🙏 Acknowledgments
Special thanks to the amazing open-source community and the following projects:

React - For the incredible UI library
The Movie Database (TMDB) - For providing comprehensive movie data
Tailwind CSS - For the utility-first CSS framework
Vite - For the lightning-fast build tool
React Icons - For the beautiful icon library
React Router - For seamless client-side routing
🎬 Ready to Start Your Movie Journey?
🚀 Get Started • 🌐 Live Demo • 🖼️ View Screenshots • 🐛 Report Issues • ⭐ Star on GitHub

💡 "Every great film deserves to be discovered"
Built with ❤️ by movie enthusiasts, for movie enthusiasts

🌐 Try it now: cinevault-eta-umber.vercel.app

GitHub stars GitHub forks GitHub issues

⭐ Don't forget to star this repository if you found it helpful! ⭐
