# Clara Whitfield – Portfolio Website

Personal portfolio website for Clara Whitfield, a frontend developer. The site presents her work to two audiences: **recruiters and hiring managers** (who skim) and **potential freelance clients** (who want to know if she can solve their problem).

> **Status:** In development (Sprint 1). Content is placeholder text until the client provides the final copy.

## Goals

- Make a strong first impression and get visitors to her work within a few seconds.
- Support her freelance positioning and make it easy to get in touch.
- Feel fast, polished, and look good on both desktop and phone.

## Tech stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/) (build tool and dev server)
- [Tailwind CSS](https://tailwindcss.com/) (styling)
- Planned for later sprints: React Router, and possibly Next.js

## Features

**Sprint 1 (current)**
- [ ] Home page with intro text and a button that scrolls to the projects
- [ ] Global styles and responsive layout (desktop and phone)
- [ ] Projects section displayed as a 3 × 2 grid
- [ ] Project detail view

**Planned**
- [ ] About section
- [ ] Contact option
- [ ] Downloadable CV
- [ ] Project filtering by technology
- [ ] Dark mode (nice to have)
- [ ] Deployment with a custom domain

## Getting started

### Requirements

- [Node.js](https://nodejs.org/) (current LTS version)
- npm

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd <project-folder>

# Install dependencies
npm install

# Start the development server
npm run dev
```

The site will be available at the local address shown in the terminal (usually `http://localhost:5173`).

### Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build locally |

## Project structure

```
├── node_modules/      # Installed dependencies (not committed)
├── public/            # Static files (favicon, CV, images)
├── src/
│   ├── assets/        # Images and other assets
│   ├── components/    # Reusable components (Home, Projects, About, Contact…)
│   ├── App.jsx        # Root component
│   ├── index.css      # Global styles
│   └── main.jsx       # Entry point
├── .gitignore
├── eslint.config.js   # ESLint configuration
├── index.html
├── package-lock.json
├── package.json
├── README.md
└── vite.config.js     # Vite configuration
```

*The structure may change as the project grows.*

## Design

The color palette and page layout are planned in Figma. Style direction from the client: clean, modern, confident but not cold, with plenty of whitespace and good typography. Animations should stay subtle.

## Content

All text, project descriptions, screenshots, and the CV are provided by the client. Each project links out to its live website.

## Timeline

- **Duration:** 6–8 weeks
- **Working method:** weekly sprints with a plan at the start of the week and a status report at the end

## Author

Built by Gonzalo Salas, frontend developer, for Clara Whitfield.