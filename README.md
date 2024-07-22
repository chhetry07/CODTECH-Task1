# To-Do list

## Overview

This Task Management Application is designed to help users keep track of their tasks seamlessly. With features to add, edit, delete, and filter tasks, users can efficiently manage their to-do lists. The interface is built using HTML, CSS (leveraging Tailwind CSS and DaisyUI), and JavaScript, with data persistence via localStorage.

## Key Features

- **Task Addition**: Users can add new tasks with optional due dates.
- **Task Editing**: Users can modify existing tasks.
- **Task Deletion**: Users can remove individual tasks or clear all tasks.
- **Status Toggle**: Users can mark tasks as completed or revert them to pending.
- **Task Filtering**: Users can filter tasks by their status (all, pending, completed).
- **Responsive Design**: The application adapts to various screen sizes.
- **LocalStorage**: Ensures tasks persist across browser sessions.

## Technology Stack

- **HTML**
- **CSS**
  - Tailwind CSS
  - DaisyUI
- **JavaScript**
- **Boxicons**

## File Breakdown

- `index.html`: Defines the structure of the application.
- `style.css`: Contains custom styling for the application.
- `script.js`: Includes the logic for task operations and UI updates.

## Usage Instructions

1. **Add a Task**:
   - Type a task into the input field.
   - Optionally, select a due date.
   - Click the add button (plus icon) to add the task.

2. **Edit a Task**:
   - Click the edit button (pencil icon) next to the desired task.
   - Update the task in the input field.
   - Click the check button to save changes.

3. **Delete a Task**:
   - Click the delete button (trash icon) next to the task to remove it.

4. **Toggle Task Status**:
   - Click the check button to mark the task as completed or pending.

5. **Clear All Tasks**:
   - Click the "Delete All" button to remove all tasks.

6. **Filter Tasks**:
   - Click the filter button and choose the desired filter (All, Pending, Completed) to view tasks by status.

## Code Summary

### HTML

- `index.html` provides the structure, including sections for the header, input fields, filters, and task list.

### CSS

- `style.css` includes custom styles to enhance the appearance.
- Utilizes Tailwind CSS and DaisyUI for additional styling and components.

### JavaScript

- `script.js` handles task management logic.
- **Classes**:
  - `TodoItemFormatter`: Handles task formatting (name, due date, status).
  - `TodoManager`: Manages task operations (add, edit, delete, toggle status, filter, save to localStorage).
  - `UIManager`: Manages UI interactions (event listeners, task display, alerts).

## Author

Developed by [Bhoomi Chhetry]
