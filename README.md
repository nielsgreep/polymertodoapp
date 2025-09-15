# Polymer To-Do App

This is a simple to-do list application built using the Polymer library. It allows users to add, edit, and complete tasks.

## Features

*   **Add new tasks:** Enter a task and a username to add a new item to the to-do list.
*   **Complete tasks:** Mark tasks as complete by checking the box next to them. Completed tasks are moved to a separate list.
*   **Edit tasks:** Click the edit button to modify the text of a task.
*   **Real-time updates:** The application is designed to support real-time updates (though the backend is not fully implemented in this version).

## Application Structure

The application is built with three main files:

*   **`index.html`**: The main entry point for the application. It loads the necessary Polymer libraries and the main `todo-app` element.
*   **`elements/todo-app.html`**: The main application component. It manages the list of to-do items, handles adding new tasks, and organizes completed tasks.
*   **`elements/todo-element.html`**: Represents a single to-do item. It includes the task description, the user who created it, and controls for editing and completing the task.

## How to Run

To run this application, you need a simple web server. You can use Python's built-in HTTP server for this purpose.

1.  Make sure you have Python installed on your system.
2.  Open a terminal or command prompt in the root directory of this project.
3.  Run the following command:

    ```bash
    python -m SimpleHTTPServer 8000
    ```

    If you are using Python 3, the command is:

    ```bash
    python -m http.server 8000
    ```
4.  Open your web browser and navigate to `http://localhost:8000`.

The to-do application should now be running in your browser.
