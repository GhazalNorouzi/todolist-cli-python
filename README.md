# To-Do CLI App

A simple command-line task management program using Python and SQLite.

---

## Features

- Add a new task
- Show all tasks
- Edit an existing task
- Delete a task
- Store tasks in SQLite database

---

## Project Structure

```
.
 
├── db.py # Database management and connection
├── task.py # Tasks class with CRUD methods
├── cli.py # Command-line interface
├── main.py # Entry point of the program
└── README.md # Project documentation

```

---

## Installation & Usage

1. **Clone the repository**

```bash
git clone <REPO_URL>
cd <REPO_FOLDER>
```

2. **Check Python installation**
   
```bash
python --version
```

3. **Create the database table**
   
```python
from db import create_table
create_table()
```

4. **Run the program**

```bash
python main.py
```

5. **Use the CLI**

Enter the option number (1-5) to interact with the program.

**Example CLI:**

```text
1. Add Task
2. Show Tasks
3. Edit Task
4. Delete Task
5. Exit
```


## Technical Notes


Database: SQLite

Data management: Through the Tasks class

User Interface: CLI (Command-Line Interface)

Operations: All CRUD operations implemented via class methods




## How to Upload Project via Git (if using local repo)

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <REPO_URL>
git push -u origin main
```
