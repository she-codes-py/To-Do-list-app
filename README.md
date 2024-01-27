Importing Required Modules:
        *import os*
This line imports the os module, which provides a way to interact with the operating system, 
particularly for handling files and directories.

Constants:
        *TASKS_FILE = "tasks.txt"*
This line defines a constant TASKS_FILE with the filename where the tasks will be stored.
It's set to "tasks.txt" in this example

Function Definitions:

load_tasks(): Reads tasks from the file and returns a list of tasks.
save_tasks(tasks): Writes tasks to the file.
display_tasks(tasks): Displays the current list of tasks.
add_task(tasks, new_task): Adds a new task to the list and saves it to the file.
remove_task(tasks, task_index): Removes a task at the specified index and saves the updated list to the file.

In summary, this script provides a simple console-based to-do list application with 
basic functionality like adding and removing tasks. The tasks are stored in a text file for persistence between program runs. 
You can run this script, follow the menu prompts, and interact with your to-do list.
