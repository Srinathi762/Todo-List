# Todo List

A simple, interactive Todo List web application built with vanilla HTML, CSS, and JavaScript.

## Features

- ✅ **Add Todos** - Add tasks with a name and due date
- ✏️ **View Todos** - See all your tasks displayed in a grid layout
- 🗑️ **Delete Todos** - Remove completed or unwanted tasks
- 📅 **Due Dates** - Assign due dates to each todo item

## Project Structure

```
Todo-List/
├── todo-list.html          # Main HTML file
├── styles/
│   └── todo-list.css       # Styling
├── scripts/
│   └── todo-list.js        # JavaScript functionality
└── README.md               # This file
```

## Files Overview

### `todo-list.html`
The main HTML file that provides the structure:
- Input fields for todo name and due date
- Add button to create new todos
- Container for displaying the todo list

### `styles/todo-list.css`
Styling for the application:
- Grid layout for organizing todos and input fields
- Button styling (green "Add" button, dark red "Delete" button)
- Input field styling

### `scripts/todo-list.js`
Core functionality using vanilla JavaScript:
- `todoList` array - stores todo objects with name and dueDate properties
- `renderTodoList()` - displays todos dynamically using DOM manipulation
- `addTodo()` - captures input and adds new todos to the list

## How to Use

1. Open `todo-list.html` in your web browser
2. Enter a task name in the input field
3. Select a due date from the date picker
4. Click the **Add** button to add the todo
5. Click **Delete** to remove any todo item

## Initial Data

The app comes with two sample todos:
- "learn javascript" - due 2025-12-22
- "learn react" - due 2025-12-22

## Technologies Used

- HTML5
- CSS3 (Grid Layout)
- Vanilla JavaScript (ES6+)

---

**Author:** Srinathi762  
**Created:** May 2026
