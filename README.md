# Task-Manager

## Overview
The **Task Manager** is a simple GUI-based application built using Python and Tkinter that allows users to manage their tasks efficiently. The application features user authentication, enabling users to register, log in, and securely manage their tasks. Tasks are stored persistently using JSON file handling.

## Features
- **User Authentication**
  - User Registration with unique username and hashed password storage
  - Secure Login system
- **Task Management**
  - Add tasks with unique Task ID
  - View all tasks
  - Mark tasks as completed
  - Delete tasks
- **Persistent Storage**
  - User credentials and tasks are stored in JSON files
- **Interactive GUI**
  - User-friendly interface using Tkinter
  
## Installation
### Prerequisites
- Python 3.x installed
- Required Python modules: `tkinter`, `json`, `hashlib`, `os`

### Steps
1. Clone or download the repository.
2. Navigate to the project directory.
3. Run the following command:
   ```bash
   python task_manager.py
   ```

## How to Use
1. **Login/Register**
   - Enter a unique username and password to register.
   - Use the registered credentials to log in.
2. **Manage Tasks**
   - **Add Task**: Enter a task description and save.
   - **View Tasks**: See all tasks with their status.
   - **Mark Task as Completed**: Enter Task ID to update status.
   - **Delete Task**: Enter Task ID to remove a task.
3. **Logout**
   - Exit the session and return to the login screen.

## File Structure
```
📁 Task Manager
│-- task_manager.py          # Main application file
│-- credentials.json         # Stores user login credentials
│-- tasks.json               # Stores tasks for each user
│-- README.md                # Project documentation
```

## Security Measures
- Passwords are stored using **SHA-256 hashing**.
- User-specific task storage ensures privacy.
