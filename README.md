```markdown
# TO DO List 

This Django project is a simple Task Manager web application that allows users to manage tasks, mark tasks as completed, and perform various actions related to tasks. This project is created on account of an assigment in SWE course in Phitron

## Getting Started

Follow these steps bellow to run this project.



## Setting Up a Virtual Environment

It's recommended to use a virtual environment to manage your project's dependencies. Here's how to set it up:

### Prerequisites

- Python (3.10.12 recommended)
- Django (4.2.3)
- Django Crispy Forms

### Installation

1. Install `virtualenv` if you don't have it:

   ```bash
   pip install virtualenv
   ```

2. Create a new virtual environment:

   ```bash
   virtualenv venv
   ```

3. Activate the virtual environment:

   On Windows:

   ```bash
   .\venv\Scripts\activate
   ```

   On macOS and Linux:

   ```bash
   source venv/bin/activate
   ```

### Running the Project

After activating the virtual environment, you can proceed with the installation and running steps mentioned in the main section of the readme.

### Deactivating the Virtual Environment

When you're done working on the project, you can deactivate the virtual environment:

```bash
deactivate
```

Remember to activate the virtual environment again whenever you work on the project to ensure you're using the correct dependencies.
```

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mojnomiya/todo_list.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo_list
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:

   ```bash
   python manage.py migrate
   ```

5. Run the development server:

   ```bash
   python manage.py runserver
   ```

6. Access the application in your web browser at http://127.0.0.1:8000/

## Features

- View all tasks on the home page.
- Add new tasks with title and description.
- Edit existing tasks, including marking them as completed.
- View task details.
- View completed tasks separately.
- Mark tasks as completed or pending.
- Delete tasks.

## Usage

1. Access the homepage to see the list of all tasks.
2. Click on a task to view its details.
3. Add a new task by filling out the form on the "Add Task" page.
4. Edit a task by clicking the "Edit" button and making changes.
5. Mark a task as completed or pending using the respective buttons.
6. View completed tasks by navigating to the "Completed Tasks" page.
7. Delete a task by clicking the "Delete" button and confirming.



## License

```
