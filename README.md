# FlowMate

A simple productivity web app that turns meeting notes into manageable tasks.

## Project Overview

FlowMate is a personal learning project designed to help users organize meeting notes and track their tasks.

The long-term goal is to build an AI-powered workflow assistant.

**Current version:** v0.2 (Day 2)

## Features

- Convert meeting notes into a task list
- Mark tasks as completed
- Assign a task owner
- Select a due date
- Automatically save tasks using localStorage
- Restore saved tasks after refreshing the page
- Responsive layout for mobile screens

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Browser localStorage
- GitHub Pages

## How to Use

1. Open the FlowMate website.
2. Enter meeting notes.
3. Click the task creation button.
4. Assign an owner and due date to each task.
5. Check tasks when completed.
6. Refresh the page to verify that tasks remain saved.

## Current Limitations

- Tasks are created by splitting text at periods and line breaks, not by AI.
- Task owners and due dates must be entered manually.
- Data is saved only in the current browser and site origin.
- Tasks cannot yet be edited or deleted individually.
- Duplicate tasks may be created.
- There is no account system or cross-device synchronization.

## Development Roadmap

- [x] Build the first webpage
- [x] Deploy with GitHub Pages
- [x] Generate tasks from meeting notes
- [x] Add completion checkboxes
- [x] Add owner and due date fields
- [x] Save tasks with localStorage
- [ ] Add task deletion and editing
- [ ] Prevent duplicate tasks
- [ ] Improve task extraction
- [ ] Integrate an AI API through a secure backend
- [ ] Add user accounts and database storage

## Development Log

### Day 1 — Initial Web App

- Created the GitHub repository
- Built the first webpage using HTML, CSS, and JavaScript
- Deployed the project with GitHub Pages
- Tested basic task generation

### Day 2 — Task Management and Persistence

- Learned JavaScript variables, arrays, objects, and functions
- Added task completion checkboxes
- Added owner and due date fields
- Implemented localStorage persistence
- Tested core features and browser refresh behavior

## Security and Privacy

This is a learning project. Do not enter sensitive or confidential meeting information. Browser localStorage is not encrypted application storage.

## License

No open-source license has been selected yet.
