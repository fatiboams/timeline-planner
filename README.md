# Timeline Planner

A responsive, local-first project timeline planner built with HTML, CSS and vanilla JavaScript.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Open_Planner-2563eb?style=for-the-badge)](https://fatiboams.github.io/timeline-planner/)
[![License: MIT](https://img.shields.io/badge/License-MIT-0f172a?style=for-the-badge)](LICENSE)
[![Built with HTML, CSS and JavaScript](https://img.shields.io/badge/Built_with-HTML%20%7C%20CSS%20%7C%20JavaScript-1d4ed8?style=for-the-badge)](#technology)

![Timeline Planner application preview](docs/timeline-planner-preview.png)

## Overview

Timeline Planner helps users organize tasks and milestones on a visual project schedule. It supports drag-to-reschedule, progress tracking, search, filters, local browser storage and JSON import/export without requiring an account or backend.

## Features

- Add, edit and delete project tasks
- Create dated milestones
- Set start and end dates
- Track status, priority and progress
- Drag task bars and milestones horizontally to reschedule them
- Search tasks by title or description
- Filter by status, priority and item type
- View project statistics
- Duplicate existing tasks
- Jump directly to today on the timeline
- Automatically save project data in the browser
- Import and export project data as JSON
- Switch between light and dark mode
- Responsive desktop and mobile layout
- No account, database or backend required

## Live demo

Open the hosted application:

**https://fatiboams.github.io/timeline-planner/**

## How it works

1. Add a task or milestone from the task editor.
2. Select dates, status, priority and progress.
3. Review the item on the visual timeline.
4. Drag it horizontally to move the schedule by whole days.
5. Use filters and search to focus on specific project items.
6. Export the project as JSON for backup or transfer.

## Data and privacy

Project data is stored locally in the browser using `localStorage`. The application does not intentionally upload project data to a server.

Clearing browser storage may remove locally saved project data, so important projects should be exported regularly.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Start adding tasks and milestones.

No package installation, account or build command is required.

## Project structure

```text
timeline-planner/
├── assets/
│   ├── app.js
│   └── styles.css
├── docs/
│   └── timeline-planner-preview.png
├── index.html
├── .gitignore
├── LICENSE
└── README.md
```

## Technology

- Semantic HTML
- Responsive CSS
- Vanilla JavaScript
- Browser `localStorage`
- Pointer Events API
- File and Blob APIs
- GitHub Pages

## JSON portability

The planner can export the current project into a JSON file and later import it into the same application. Imported data is validated and normalized before use.

## Roadmap

- [ ] Resize task duration by dragging task edges
- [ ] Add task dependencies
- [ ] Support multiple projects
- [ ] Add weekly, monthly and quarterly zoom levels
- [ ] Add undo and redo
- [ ] Add CSV import and export
- [ ] Add printable project reports
- [ ] Add automated browser tests

## Contributing

Bug reports, improvement ideas and pull requests are welcome. Please avoid publishing confidential project information in public issues.

## License

Released under the [MIT License](LICENSE).
