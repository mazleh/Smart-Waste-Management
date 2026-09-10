Summary of What Was Added:
macOS Prerequisites: Detailed instructions for verifying and installing Node.js (v18+) via Homebrew (brew install node) or nvm, Terminal/iTerm2 setup, and package managers.

IDE Setup Guides:

Visual Studio Code & Cursor: Opening folders, terminal shortcuts (Cmd + O, Ctrl + ` ), and recommended extensions (Tailwind CSS IntelliSense, ESLint, Prettier).

WebStorm / IntelliJ IDEA: Project importing and terminal workflows.

Step-by-Step Execution:

npm install for dependency management.

Setting up environment variables (cp .env.example .env).

Running npm run dev to launch the local Vite development server on http://localhost:3000.

macOS Quick Preview Alternatives:

Using macOS built-in Python server: python3 -m http.server 3000

Direct browser launch via terminal: open index.html

Running with a Python Flask backend (python3 app.py with templates/index.html).

macOS Troubleshooting & Diagnostics:

Resolving port conflicts using lsof -i :3000 and kill -9 <PID>.

Handling macOS AirPlay Receiver port reservation.

Browser Web Audio API autoplay permission guidance
