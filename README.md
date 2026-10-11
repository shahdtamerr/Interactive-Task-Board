# Orbit — Focus in Motion

A responsive, local-first Kanban Lite board built with semantic HTML, CSS, and vanilla JavaScript. No framework or build step is required.

## Features
- Four workflow stages: To do, In progress, In review, Done
- Create, edit, move and delete tasks
- Task title, description, category, priority and due date
- Native HTML drag-and-drop between columns
- Live search and category filtering
- Dynamic task counters and completion metrics
- Browser `localStorage` persistence
- Light/dark theme and keyboard shortcuts (`/` search, `N` new task, `Esc` closes dialogs)
- Responsive desktop, tablet and mobile layouts
- Keyboard focus indicators, semantic labels and reduced-motion support

## Run locally
Open `index.html` in a browser. No npm install or build is needed. Alternatively, from this directory run `python -m http.server 8000` and open `http://localhost:8000`.

## Deploy to GitHub Pages
1. Create a public repository on your GitHub account, e.g. `interactive-task-board`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish. The URL will be `https://YOUR-USERNAME.github.io/interactive-task-board/`.
7. Test adding/editing/deleting tasks, moving cards, searching, category filtering, theme toggle, refresh persistence and mobile layout.

## Data and privacy
Tasks are saved in the current browser's local storage. They do not sync across devices. Clearing the browser's site data may remove saved tasks. No server or account system is used.
