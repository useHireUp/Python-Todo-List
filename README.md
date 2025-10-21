# Console To‑Do List App 

Welcome! This assessment asks you to build a simple **To‑Do List** application that runs entirely in the console (terminal). It’s designed for beginners and focuses on core programming skills.

---

## Objective
Create a console app that manages a list of tasks. Users should be able to add, view, complete, and delete tasks.

---

## Learning Goals
- Work with Python **lists** and **dictionaries**  
- Write and call **functions** to structure your program  
- Use loops to create interactive console menus  
- Handle **user input validation** and errors  
- (Optional) Work with file input/output for persistence

---

## Requirements (Detailed)

Your program must:

1. **Display a menu** with at least the following options:
   ```
   1) Add task
   2) List tasks
   3) Mark task complete
   4) Delete task
   5) Exit
   ```
2. **Add task**: Prompt for a task title (required) and an optional description. Add the task to an in-memory list with a "pending" status.  
3. **List tasks**: Show all tasks with an index number and status indicator:
   - Example: `1. [ ] Buy groceries` (pending) or `2. [x] Read chapter 3` (completed)  
4. **Mark task complete**: Allow the user to specify the task number to mark as completed. Update the status accordingly.  
5. **Delete task**: Allow the user to remove a task by number.  
6. **Input validation**: Gracefully handle invalid choices and non-numeric task numbers.  
7. **Exit**: Cleanly exit the program.  
8. **(Optional bonus)**: Implement one or more of:
   - Save and load tasks to/from a file (persist across runs)  
   - Edit an existing task’s title/description  
   - Add due dates or priority levels and sort/filter tasks  
   - Display task counts (e.g., `3 pending, 2 completed`)

---

## Running the Program

1. Save your work as:
   ```
   todo.py
   ```
2. Open a terminal in the project folder.
3. Run:
   ```bash
   python todo.py
   ```
   or
   ```bash
   python3 todo.py
   ```

---

## Example Interaction

```
To-Do List
1) Add task
2) List tasks
3) Mark task complete
4) Delete task
5) Exit
Enter choice: 1
Enter task title: Walk the dog
Enter description (optional): Park at 6pm
Task added!

Enter choice: 2
1. [ ] Walk the dog - Park at 6pm

Enter choice: 3
Enter task number to mark complete: 1
Task 1 marked as completed.

Enter choice: 2
1. [x] Walk the dog - Park at 6pm

Enter choice: 5
Goodbye!
```

---


## Bonus Ideas
- Save tasks to a JSON or text file so tasks persist between runs  
- Add an **edit** option to change title/description  
- Add **due dates** and sort tasks by date or priority  
- Add a **search/filter** to find tasks by keyword

---

## Submission

When finished:
```bash
git add todo.py
git commit -m "Complete todo assessment"
git push origin main
```

If you use a different filename, mention it in your submission message.

---

## Resources
- [Python Official Tutorial](https://docs.python.org/3/tutorial/)
- [Working with Files in Python](https://docs.python.org/3/tutorial/inputoutput.html)

---

> *Part of the HireUp Beginner Series — the goal is to test core skills with a short, practical task.*
