# Python_To_Do_List_Application
 
## Overview

The To-Do List is a graphical user interface (GUI) application that allows users to add, delete, and manage tasks. The application uses the Tkinter library for the interface and saves the tasks to a text file.

## Features

- Add new tasks to the to-do list.
- Delete tasks from the to-do list.
- Tasks are saved to a text file for persistence.

## How It Works

### Main Screen

- Task Entry: Enter the task you want to add to the to-do list.
- Add Button: Click to add the entered task to the list.
- Listbox: Displays the list of tasks.
- Delete Button: Click to delete the selected task from the list.

### Adding a Task:

- Enter the task in the text entry box.
- Click the "ADD" button.
- The task is added to the list and saved to tasklist.txt.

### Deleting a Task:

- Select the task from the listbox.
- Click the delete button.
- The task is removed from the list and deleted from tasklist.txt.

### Task Persistence:

- Tasks are saved to tasklist.txt in the application directory.
- On startup, the application reads tasks from tasklist.txt and displays them in the listbox.

## Code Explanation:

### Imported Libraries:
- tkinter: Used for the graphical user interface.

### Function:

- addTask(): Adds the entered task to the list and saves it to tasklist.txt.
- deleteTask(): Deletes the selected task from the list and removes it from tasklist.txt.
- openTaskFile(): Reads tasks from tasklist.txt and displays them in the listbox on startup.

### GUI Elements

- Task Entry: An entry widget for entering new tasks.
- Add Button: A button to add tasks to the list.
- Listbox: A listbox widget to display the tasks.
- Delete Button: A button to delete selected tasks from the list.


### Notes

- The application saves tasks to tasklist.txt in the same directory as the script.
- The application requires the image files (task.png, topbar.png, dock.png, delete.png) to be in an images directory in the same directory as the script.

### Example

- Open the application.
- Enter "Buy groceries" in the text entry box.
- Click the "ADD" button.
- The task "Buy groceries" is added to the list.
- Select "Buy groceries" from the list.
- Click the delete button.
- The task "Buy groceries" is removed from the list.
