# Task Management App

This project is a Task Management Application built using JavaScript, HTML, and CSS. It allows users to create, edit, delete, and manage tasks. The app also supports searching tasks by ID or description and marking tasks as complete.

## Features

- Add new tasks with a description.
- Edit tasks by ID or description.
- Delete tasks.
- Mark tasks as complete.
- Search tasks by ID or description.
- List all tasks with details such as start date, completion date, and status.

## Project Structure

- `index.html`: The main landing page for the app, where users can manage tasks.
- `Listar.html`: A page that displays all tasks and allows searching and managing tasks.
- `main.js`: Backend functionality to manage tasks through the console.
- `todoList.js`: Contains functions for task management, including creating, editing, deleting, and listing tasks.
- `scripts.js`: Manages the task list dynamically and updates the user interface.
- `style.css`: Styling for the user interface.
- `package.json` and `package-lock.json`: Define the project dependencies, such as `prompt-sync` for user input in the console.

## Dependencies

- `prompt-sync`: Used for taking input in the console in `main.js`.
  - Install it with: 
    ```bash
    npm install prompt-sync
    ```

## How the App Works

- **Add a Task**: Input a description, and a new task will be added to the list.
- **Edit a Task**: You can edit tasks by their ID or description.
- **Delete a Task**: Select a task by ID and delete it from the list.
- **Mark as Complete**: You can mark any task as complete, and the completion date will be recorded.
- **Search**: Search for tasks by ID or part of the description.

## Task Data Structure

Each task in the system has the following properties:

```json
{
  "id": 1,
  "description": "Buy milk",
  "startDate": "2023-10-01, 10:00:00",
  "completionDate": null,
  "status": false
}
```

- **id:** Unique identifier for the task.
- **description:** A brief description of the task.
- **startDate:** The date and time when the task was created.
- **completionDate:** The date and time when the task was marked as complete (if applicable).
- **status:** Whether the task is completed (true) or pending (false).

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributors
- Alan
- Daniella
- Lucas
- Samir

This project was developed as part of the ADA Tech Backend course.