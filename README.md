# CodeSage

CodeSage is a full-stack AI-powered code review tool. It features a React frontend and a Node.js/Express backend that leverages Google Gemini for intelligent code analysis and feedback.

## Features

- Live code editor with syntax highlighting
- AI-powered code review and suggestions
- Modern React + Vite frontend
- Express backend with Google Gemini integration

## Project Structure

```
CodeSage/
  BackEnd/
    .env
    package.json
    server.js
    src/
      app.js
      controllers/
        ai.controller.js
      routes/
        ai.routes.js
      services/
        ai.service.js
  Frontend/
    package.json
    index.html
    vite.config.js
    src/
      App.jsx
      main.jsx
      App.css
      index.css
```

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm

### Setup

#### 1. Clone the repository

```sh
git clone <your-repo-url>
cd CodeSage
```

#### 2. Set up the Backend

```sh
cd BackEnd
npm install
# Add your Google Gemini API key to .env
# Example:
# GOOGLE_GEMINI_KEY=your_api_key_here
node server.js
```

#### 3. Set up the Frontend

Open a new terminal:

```sh
cd Frontend
npm install
npm run dev
```

The frontend will run on [http://localhost:5173](http://localhost:5173) and the backend on [http://localhost:3000](http://localhost:3000).

## Usage

1. Enter your code in the editor.
2. Click the **Review** button.
3. View AI-generated feedback and suggestions on the right panel.

## License

MIT
