

# Todo List Web Application

## Overview

This is a simple Todo List web application that allows users to add tasks with a name, due date, and due time. Users can view their tasks in a structured format and delete tasks when needed.

## Usage

1. Open the `index.html` file in a web browser.
2. Enter the task name in the "Todo name" input field.
3. Choose the due date and due time using the date and time input fields.
4. Click the "Add" button to add the task to the Todo List.
5. The Todo List will display the tasks along with their due dates and times.
6. To delete a task, click the "Delete" button next to the task.

## Files

- `index.html`: The main HTML file containing the structure of the Todo List.
- `todo-list.css`: The CSS file for styling the Todo List elements.
- `todo-list.js`: The JavaScript file containing the logic for managing the Todo List.
- `README.md`: This file providing an overview and instructions.

## Todo Object Structure

A task in the Todo List is represented by an object with the following structure:

```javascript
{
  name: "Task Name",
  dueDate: "2022-12-31",
  duetime: "12:00"
}
```

## Functions

- `renderTodoList`: Renders the Todo List on the web page.
- `addTodo`: Adds a new task to the Todo List.

## Developer Notes

- The Todo List is managed using the `todoList` array.
- Tasks are displayed with their name, due date, and due time.
- Deletion of tasks is handled through the "Delete" button.
