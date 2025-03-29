# Marketplace App

A modern marketplace application built with React 19, TypeScript, Vite, and Ant Design.

## Features

- Built with React 19 using the latest features including the `use` hook
- TypeScript for type safety
- Vite for fast development and optimized builds
- Ant Design for UI components
- ESLint for code linting
- Prettier for code formatting
- Responsive design for all devices

## Project Structure

```
market-place/
├── client/           # React frontend application
│   ├── public/       # Public assets
│   ├── src/          # Source files
│   │   ├── assets/   # Static assets
│   │   ├── App.tsx   # Main App component
│   │   ├── App.css   # App-specific styles
│   │   ├── main.tsx  # Entry point
│   │   └── index.css # Global styles
│   ├── .eslintrc.cjs # ESLint configuration
│   ├── .prettierrc   # Prettier configuration
│   └── ...
└── README.md         # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (v18.0.0 or later)
- npm or yarn

### Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/market-place.git
cd market-place
```

2. Install dependencies

```bash
cd client
npm install
```

3. Start the development server

```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Builds the app for production
- `npm run lint` - Runs ESLint to check for code issues
- `npm run format` - Formats code using Prettier
- `npm run format:check` - Checks if all files are properly formatted
- `npm run preview` - Preview the production build locally

## License

This project is licensed under the MIT License - see the LICENSE file for details.
