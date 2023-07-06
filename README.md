# Readme

### This program is a simple to-do list manager that allows users to add, remove, update, mark tasks as done, and display tasks. Here's a breakdown of the program's functions:

### 1. Login or Register
#### The program starts by asking the user to login or register. If the user is already registered, they can log in using their username and password. If the user is new, they can register by choosing a username and password. User credentials are stored in a file named "users.txt".

### 2. Add a Task
#### To add a new task, select option 1 from the menu. You will be prompted to enter the task description and the deadline for the task. The deadline should be entered in the format: "Year-Month-Day Hour:Minute:Second". For example, "2023-05-12 14:30:00".

### 3. Remove a Task
#### To remove a task, select option 2 from the menu. Enter the description of the task you want to remove.

### 4. Display Tasks
#### To display all tasks, select option 3 from the menu. The program will show a list of tasks, including their status (done or pending), description, and deadline.

### 5. Change a Task
#### To update an existing task, select option 4 from the menu. Enter the description of the task you want to update, and then enter the new task description.

### 6. Mark a Task as Done
#### To mark a task as done, select option 5 from the menu. Enter the description of the task you want to mark as done.

### 7. Save and Exit
#### To save your tasks and exit the program, select option 6 from the menu. The program will save the tasks to a file named "tasks.pickle" and terminate.

### Note: The program automatically loads the previously saved tasks when started and saves the tasks upon exiting.

### Please make sure to enter the input as instructed to ensure the program functions correctly.

### Example:
#### Here's an example interaction with the program:
```
Enter 1 to login, 2 to register: 2
Choose a username: mohamed
Choose a password: 1234
Registration successful!
Welcome, mohamed!

Choose one:
1. Add task
2. Delete task
3. Display tasks
4. Change task
5. Mark as Done
6. Save and exit

Enter your choice: 1
Add new task: Complete project
Enter the deadline of the task (Year-Month-Day Hour:Minute:Second): 2023-05-15 10:00:00
The task: Complete project with deadline: 2023-05-15 10:00:00.

Enter your choice: 3
1 - [ ] Complete project - Deadline: 2023-05-15 10:00:00

Enter your choice: 6
Tasks saved. Good luck!

```
