Name: Tabassum Mallikar

Company: Encryptix

ID: EXM260994

Domain: Python Programming

Duration: Oct to Nov 2024

**Overview of the Project**


**Project: To-Do List Application**

**Objective**

The objective of this project is to develop a simple, command-line based To-Do List application that allows users to manage their tasks efficiently. The application provides basic task management functionality, enabling users to add, view, update, mark tasks as completed, and delete tasks.

**Key Activities**

Task Management: Allows users to add, view, update, complete, and delete tasks, with persistent storage in a JSON file.

Data Persistence: Loads tasks from the file on startup and saves tasks after each operation to ensure task data is maintained across sessions.

User Interaction: Provides a menu-driven interface for users to manage tasks and handles invalid inputs with appropriate feedback.

**Technologies Used**

Python Programming Language:
The core language used for building the to-do list application. It handles user input/output, file handling, and logic implementation.

File I/O (Input/Output):
os Module: Used to check if the tasks.json file exists before attempting to load it (os.path.exists()).
File Handling: The application reads from and writes to a tasks.json file to store and persist the tasks using standard file operations (opening files in read/write mode).

JSON (JavaScript Object Notation):
json Module: Used for serializing and deserializing tasks (converting the task list into JSON format for saving and converting it back into a Python dictionary for usage).

CLI (Command-Line Interface):
The application uses simple console-based interactions where users input their choices and task information via the command line.

**Key Insights**

Task Persistence: Tasks are saved and loaded from a tasks.json file, ensuring data is retained between program runs.

CRUD Operations: Users can perform basic operations—Create, Read, Update, and Delete—on tasks.

Task Status: Tasks can be marked as "Completed" or "Pending" to track progress.

User Interaction: The program provides a simple menu-driven interface, allowing users to easily manage tasks.

Error Handling: Input validation checks for task ID and choice selection to prevent invalid actions.

Data Storage: Tasks are stored as a dictionary with unique task IDs and details (description, status).
