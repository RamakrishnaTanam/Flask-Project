# Task Master - To-Do List Application

**Task Master** is a simple task management application that allows users to create, update, and delete tasks. It is built with **Flask** (a Python web framework) and **SQLite** (a lightweight database).

This project helps you organize and keep track of your tasks efficiently in a user-friendly web interface.

## Features
- **Add Task**: Create new tasks and store them in the database.
- **View Tasks**: View all tasks listed in a table with their creation dates.
- **Update Task**: Edit existing tasks to update their content.
- **Delete Task**: Remove a task from the list permanently.

## Tech Stack
- **Flask**: Python web framework for building the web application.
- **SQLAlchemy**: ORM (Object Relational Mapper) for interacting with the SQLite database.
- **SQLite**: Lightweight relational database to store tasks.

## Installation

Follow these steps to get your environment set up and running:

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/task-master.git
    cd task-master
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:
    - **Windows**: 
        ```bash
        venv\Scripts\activate
        ```
    - **Mac/Linux**: 
        ```bash
        source venv/bin/activate
        ```

4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Initialize the database:
    - Run the following Python commands to create the database and the required table:
        ```bash
        python
        >>> from app import db
        >>> db.create_all()
        ```

6. Run the application:
    ```bash
    python app.py
    ```

7. Open your browser and visit `http://127.0.0.1:5000/` to access the Task Master application.

## Usage

- **Adding a Task**: Enter the task name and click "Add Task" to create a new task.
- **Viewing Tasks**: All tasks will be displayed in a table on the homepage with the option to delete or update them.
- **Updating a Task**: Click on "Update" next to a task, edit the content, and click "Update" to save the changes.
- **Deleting a Task**: Click on "Delete" next to a task to permanently remove it.

        
