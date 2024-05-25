# ToDoList React Component

## Description
The `ToDoList` component is a simple React-based to-do list application. It allows users to add tasks, delete tasks, and reorder tasks within the list. The component demonstrates basic state management using React hooks and includes functionality for user interaction through buttons and input fields.

## Features
- **Add Task:** Users can add a new task to the list by entering text into an input field and clicking the "Add" button.
- **Delete Task:** Users can remove a task from the list by clicking the "Delete" button next to the task.
- **Move Task Up:** Users can move a task up in the list by clicking the "👆" button next to the task.
- **Move Task Down:** Users can move a task down in the list by clicking the "👇" button next to the task.

## Code Overview

### State Variables
- `tasks`: An array of tasks (strings) initialized with two default tasks: "eat breakfast" and "take a shower".
- `newTask`: A string representing the new task input by the user.

### Event Handlers
- `handleInputChange(event)`: Updates the `newTask` state with the value entered by the user in the input field.
- `addTask()`: Adds the new task to the `tasks` array if the input is not empty and clears the input field.
- `deleteTask(index)`: Removes the task at the specified index from the `tasks` array.
- `moveTaskUp(index)`: Moves the task at the specified index one position up in the `tasks` array.
- `moveTaskDown(index)`: Moves the task at the specified index one position down in the `tasks` array.

### JSX Structure
- The main component wrapper is a `<div>` with the class name "to-do-list".
- The title of the application is displayed in an `<h1>` tag.
- An input field for adding new tasks is paired with an "Add" button.
- The list of tasks is rendered as an ordered list (`<ol>`), with each task being a list item (`<li>`) containing:
  - The task text.
  - A "Delete" button to remove the task.
  - An "👆" button to move the task up.
  - An "👇" button to move the task down.

## How to Use
1. **Add a Task:** Type a task into the input field and click the "Add" button. The task will be added to the bottom of the list.
2. **Delete a Task:** Click the "Delete" button next to a task to remove it from the list.
3. **Move a Task Up:** Click the "👆" button next to a task to move it one position up in the list.
4. **Move a Task Down:** Click the "👇" button next to a task to move it one position down in the list.

<img width="959" alt="Capture" src="https://github.com/Fidaa2002Shwahna/To-Do-List-using-react/assets/121303770/6f9d265b-2bd0-4500-8ffa-e87249e5f3eb">

