# SimpleGantt

A modern, lightweight Gantt chart web application built with vanilla JavaScript and Bootstrap 5.

**[Live Demo](https://krlz-dev.github.io/mygantt/)**

![SimpleGantt Screenshot](https://img.shields.io/badge/Status-Live-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue)

## Features

### Core Functionality
- **Interactive Timeline** - Day/month view with weekend highlighting and today marker
- **Task Management** - Add, edit, and delete tasks, groups, and milestones
- **Drag & Drop** - Move task bars horizontally to change dates
- **Resize** - Drag left/right edges of bars to adjust duration
- **Dependencies** - Visual arrows showing task relationships
- **Progress Tracking** - Visual progress bars on tasks

### Data Management
- **Auto-Save** - Changes automatically saved to browser local storage
- **Export JSON** - Download project data as JSON file
- **Import JSON** - Load project from JSON file
- **Export SVG** - High-quality vector image export
- **Export PNG** - Raster image export (2x resolution)

### UI Features
- Clean, modern design inspired by TeamGantt
- Color-coded task bars (6 color options)
- Assignee avatars with initials
- Group/phase headers with collapsible style
- Milestone markers (diamond shape)
- Responsive scrolling with synced sidebar

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/krlz-dev/mygantt.git
cd mygantt
```

2. Open `index.html` in your browser, or serve locally:
```bash
python -m http.server 8000
```

3. Visit `http://localhost:8000`

## Usage

| Action | How |
|--------|-----|
| Add task | Click **+ Add Task** button |
| Edit task | Hover row → click pencil icon, or double-click bar |
| Delete task | Open edit modal → click Delete |
| Move task | Drag the task bar left/right |
| Change duration | Drag left or right edge of bar |
| Set dependency | In task modal, select "Depends On" |
| Export image | Gear menu → Export as PNG/SVG |
| Save/Load project | Gear menu → Export/Import JSON |

## Tech Stack

- **HTML5** - Single-file application
- **CSS3** - Custom styles with CSS variables
- **JavaScript** - Vanilla ES6+, no frameworks
- **Bootstrap 5** - UI components and grid
- **Bootstrap Icons** - Icon library

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Project Structure

```
mygantt/
├── index.html          # Single-file application
├── README.md           # This file
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Pages deployment
```

## License

MIT License - feel free to use for personal or commercial projects.

---

Made with Claude Code
