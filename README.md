# Frontend AI Capstone

A frontend web development capstone project built with HTML, CSS, and JavaScript. This repository documents the project setup, development workflow, and deliverables for the Frontend AI Capstone assignment.

## Table of Contents

- [Status](#status)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Development Guidelines](#development-guidelines)
- [Git Workflow](#git-workflow)
- [License](#license)
- [Author](#author)

## Status

🚀 This project is actively being developed as part of the Flyrank AI Frontend Development Internship.

## Tech Stack

| Layer      | Technology        |
| ---------- | ----------------- |
| Markup     | HTML5             |
| Styling    | CSS3              |
| Scripting  | Vanilla JavaScript|
| Editor     | [Cursor](https://cursor.com) |

## Project Structure

```
frontend-ai-capstone/
├── index.html          # Main entry point
├── css/                # Stylesheets
├── js/                 # JavaScript modules
├── assets/             # Images, icons, and static files
├── README.md
├── LICENSE
├── CLAUDE.md           # AI assistant context and conventions
└── .gitignore
```

> Folder structure will evolve as the project grows. Keep files organized by concern (markup, style, behavior, assets).

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- [Node.js](https://nodejs.org/) (optional, for tooling such as live reload or linting)
- [Cursor](https://cursor.com) or any code editor

### Local Development

1. Clone the repository:

   ```bash
   git clone https://github.com/noorcodes393/frontend-ai-capstone.git
   cd frontend-ai-capstone
   ```

2. Open `index.html` in your browser, or use a local dev server:

   ```bash
   npx serve .
   ```

3. Edit files and refresh the browser to see changes.

## Development Guidelines

- Write **semantic HTML** with accessibility in mind.
- Use **responsive design** — mobile-first layouts and flexible units.
- Keep **JavaScript modular** and avoid unnecessary dependencies.
- Follow **Conventional Commits** for all commit messages.
- Add comments only where logic is non-obvious.

See [CLAUDE.md](./CLAUDE.md) for detailed conventions used with AI-assisted development in Cursor.

## Git Workflow

| Commit type | When to use                          |
| ----------- | ------------------------------------ |
| `feat`      | New feature or user-facing addition  |
| `fix`       | Bug fix                              |
| `docs`      | Documentation only                   |
| `style`     | Formatting, no logic change          |
| `refactor`  | Code change without feature/fix      |
| `chore`     | Build, tooling, or maintenance tasks |

Example:

```bash
git commit -m "feat: add responsive navigation bar"
```

## License

This project is licensed under the [MIT License](./LICENSE).

## Author

**Noor** — [GitHub](https://github.com/noorcodes393)
