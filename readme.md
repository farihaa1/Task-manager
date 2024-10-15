# Task Manager App (To-Do List)

## Objective
The **Task Manager App** is a simple and efficient to-do list application where users can add, edit, and remove tasks. The app includes features like task filtering, sorting, and data persistence using local storage to maintain tasks even after browser refresh.

## Features

### 1. Add New Task
- Users can input a task name, description, priority level (e.g., Low, Medium, High), and an optional due date.
- Tasks are dynamically displayed in the task list using DOM manipulation.

### 2. Edit and Remove Tasks
- Each task has "Edit" and "Delete" buttons for easy management.
- JavaScript array methods like `map()` and `filter()` are used to update or remove tasks from the list.

### 3. Filter Tasks by Priority
- Users can filter tasks based on priority (e.g., show only "High" priority tasks).
- The `filter()` and `map()` methods are utilized to display the filtered tasks.

### 4. Sort Tasks by Due Date
- Users can assign a due date to each task and sort tasks by the nearest or farthest due date.
- The `sort()` method arranges tasks in ascending or descending order based on their due dates.

### 5. Save Tasks to Local Storage
- Task data is stored in `localStorage`, ensuring that tasks persist even after the browser is closed or refreshed.
- Tasks are saved to and retrieved from `localStorage` for persistent data management.

## Advanced Features

### 1. Search Bar
- Users can search for tasks by name using a search bar.
- The `filter()` method is employed to display tasks that match the search term.

### 2. Task Categories
- Tasks can be categorized (e.g., Work, Personal) for better organization.
- Users can filter tasks based on their selected categories.

### 3. Task Completion
- Each task has a checkbox to mark its completion status.
- Completed tasks can either be struck through or moved to a "Completed" section.

## Technologies Used
- **HTML/CSS**: For structuring the layout and applying styling to the user interface.
- **JavaScript**: For task management, DOM manipulation, usage of array methods, and handling data persistence with `localStorage`.