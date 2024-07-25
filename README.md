# darkmode
This project demonstrates a simple implementation of dark mode in a React application. It features a toggle button that allows users to switch between light and dark themes, showcasing how to manage theme states and apply corresponding styles dynamically.

# React Dark Mode Toggle

A simple React project demonstrating dark mode implementation using Context API and Tailwind CSS.

## Features

- Toggle between light and dark themes.
- State management with React Context API.
- Smooth CSS transitions.

## Technologies

- React
- Context API
- Tailwind CSS
- Vite

## Getting Started

### Installation

1. Clone the repo:
    ```sh
    git clone https://github.com/your-username/react-dark-mode-toggle.git
    ```

2. Navigate to the project directory:
    ```sh
    cd react-dark-mode-toggle
    ```

3. Install dependencies:
    ```sh
    npm install
    ```

4. Start the development server:
    ```sh
    npm run dev
    ```

### Usage

Visit `http://localhost:5173` in your browser. Use the "Toggle Theme" button to switch themes.

## Project Structure

```plaintext
react-dark-mode-toggle
├── public
│   └── index.html
├── src
│   ├── components
│   │   ├── ThemeBtn.jsx
│   │   └── Card.jsx
│   ├── contexts
│   │   └── theme.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .gitignore
├── package.json
└── README.md
