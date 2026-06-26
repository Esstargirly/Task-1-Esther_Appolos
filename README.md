# CLI To-Do List App

A simple command-line to-do list app built with Python. Tasks are saved to a JSON file so they persist between sessions.

-----

## Features

- Add new tasks
- Delete tasks
- View all tasks
- Tasks are automatically saved and reloaded on the next run

-----

## Requirements

- Python 3.x

-----

## How to Run

```bash
python todo.py
```

-----

## Usage

On launch, you’ll see a menu:

```
1. Add a new task
2. Delete a task
3. List tasks
4. Quit
```

Pick an option by entering the corresponding number. Tasks are saved automatically after every add or delete.

-----

## How Storage Works

Tasks are stored in a `tasks.json` file in the same folder as `todo.py`. The file is created automatically on first use and loaded every time the app starts.

-----

## Author

**Esther Appolos**