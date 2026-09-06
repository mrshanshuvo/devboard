# DevBoard - L1B11A5

A modern and responsive task management dashboard built with HTML5, Tailwind CSS, daisyUI, and vanilla JavaScript.

## Overview

DevBoard is a frontend productivity dashboard for managing development tasks.

Users can view assigned tasks, mark tasks as completed, track completed work through an activity log, and view the current date. The project also includes a dedicated blog page covering fundamental DOM concepts.

## Features

- Task management dashboard
- Assigned task counter
- Completed task counter
- Task completion functionality
- Activity log
- Clear activity history
- Dynamic current date and day display
- Theme/background interaction
- Responsive dashboard layout
- Blog page with DOM concepts
- Mobile-friendly interface
- Modern card-based UI

## Dashboard

The main dashboard includes:

### Task Overview

Displays:
- Number of assigned tasks
- Number of completed tasks
- Current date
- Current day

### Task Cards

Each task card contains:
- Company or project name
- Task title
- Task description
- Deadline
- Completed button

When a task is completed, the assigned-task count decreases and the completed-task count increases.

### Activity Log

Completed tasks are added to the activity log with the completion time.

Users can clear the activity history using the **Clear History** button.

## Blog

The project includes a separate blog page covering important JavaScript DOM concepts:

- DOM element selection
- `innerHTML`
- `innerText`
- `textContent`
- Event delegation
- Event bubbling
- Creating and removing DOM elements

## Tech Stack

- HTML5
- Tailwind CSS
- daisyUI
- Vanilla JavaScript
- DOM API
- Google Fonts

## Project Structure

```text
devboard/
├── assets/
│   ├── logo.png
│   ├── checkbox.png
│   ├── theme-btn.png
│   ├── board.png
│   ├── calender.png
│   └── activity.png
├── scripts/
│   └── script.js
├── blog.html
├── index.html
├── .gitignore
├── LICENSE
└── README.md
