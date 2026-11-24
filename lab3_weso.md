# Software Development and Documentation Lab - Task 3

* **Name:** Waseem Gber
* **Student ID:** 202230017
* **Topic:** README File & Getting Started Guide

---

## Part 1: Create a Project
**Project Name:** To-Do List

---

## Part 2: Write README

### Project Title: To-Do List CLI App

#### Description
A lightweight, clean, and efficient command-line task management application built in Python. This app allows users to easily add, view, complete, and delete daily tasks with persistent JSON storage, ensuring your tasks are saved even after closing the application.

#### Features
* **Task Management:** Add new tasks with descriptions and priority levels.
* **Persistent Storage:** Automatically saves tasks to a local `tasks.json` file.
* **Interactive CLI:** Simple and intuitive command-line interface with status indicators.
* **Task Completion:** Toggle tasks between pending and completed states.

#### Technologies Used
* **Language:** Python 3.8+
* **Standard Libraries:** `json`, `os`, `sys`

---

## Part 3: Getting Started Section

### Installation
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/username/todo-cli-app.git
cd todo-cli-app
```

### Requirements
* Python 3.8 or higher installed on your system.
* No external third-party packages are required (uses Python built-in libraries only).

### Running the Project
Execute the main script using Python:
```bash
python app.py
```

### Usage
Once the application is running, you will be presented with an interactive main menu:
* **View Tasks:** Displays your current list of tasks and their completion status.
* **Add a Task:** Prompts you to enter a title for your new task.
* **Mark Task as Complete:** Enter the corresponding task number to finish it.
* **Delete a Task:** Permanently removes a task from your storage.

---

## Reflection Questions

### 1. Why is a README important?
In my opinion, a README is essential because it serves as the frontline and introduction to any software project. I realized that it gives anyone visiting the project an immediate snapshot of what it does and why it matters without needing to read through all the code lines. It saves time for users and developers alike and gives the project a polished, professional touch.

### 2. What is the difference between README and documentation?
Through working on this, I found that a README acts as a high-level summary designed to get a user up and running in just a few minutes with quick setup and basic usage steps. On the other hand, full documentation is a much deeper, multi-page reference manual that covers architectural designs, API specifications, and troubleshooting. Simply put, I see the README as the project's trailer, while the documentation is the full movie.

### 3. What was the most challenging part of writing the Getting Started section?
The toughest part for me was avoiding the "curse of knowledge," meaning I had to consciously step back and not assume that the reader already knows the environment setup or background steps as well as I do. It was challenging to make sure I included every vital prerequisite (like Python versions or directory paths) without making the guide too cluttered or difficult to follow.