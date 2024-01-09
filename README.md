# ToDoList

A simple and efficient ToDo list web application built with Django. Manage your tasks seamlessly with an easy-to-use interface. Add, edit, and mark tasks as completed to stay organized 
and productive.

## Description

ToDoList is designed to streamline your task management process. It is accessible only to registered users, ensuring a personalized and secure experience. Whether you're organizing daily
chores, work-related tasks, or personal goals, this application provides a hassle-free solution. With its intuitive design, you can quickly add new tasks, update them as needed, and mark them as completed when finished.

The application is built on the Django framework, ensuring reliability and robustness. ToDoList emphasizes a clean user experience, allowing you to focus on your tasks without unnecessary complexities. It's a perfect tool for individuals looking for a straightforward and effective way to stay on top of their to-do lists.

## Features

- **User Registration:** Access ToDoList by registering for an account.
- **Add New Tasks:** Easily add new tasks with descriptions to the list.
- **Edit and Update:** Modify task details or update them as needed.
- **Mark as Completed:** Keep track of completed tasks with a simple mark.

## Installation

Before running ToDoList, make sure you have the following installed:

- [Python](https://www.python.org/)
- [pip](https://pip.pypa.io/en/stable/installation/)
- [Django](https://www.djangoproject.com/)
- Any IDE (e.g., [VS Code](https://code.visualstudio.com/))

Follow these steps to set up ToDoList on your local machine:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/todolist.git
    ```

2. Navigate to the project directory:

    ```bash
    cd todolist
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:

    ```bash
    python manage.py migrate
    ```

5. Create a superuser account:

    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

7. Access the application at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Usage

1. Register for an account on the application.
2. Log in with your credentials.
3. Add, edit, and mark tasks as completed as needed.

