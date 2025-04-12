# React ToDo App
[Live Code](https://mateuszcieplak.github.io/react_todo-app/)
  
![todoapp](./description/todoapp.gif)

The "React ToDo App" is a simple task manager that allows users to create, edit, delete, and filter tasks. The app is built using React with TypeScript, and its main purpose is to manage a list of tasks, which can be marked as completed, deleted, or edited.

### Key features:
- **Creating tasks**: Users can add new tasks to the list.
- **Filtering tasks**: Tasks can be filtered by status: All, Active, Completed.
- **Task management**: Users can edit or delete tasks and toggle their completion status.
- **State management**: React Context is used for global task management.
- **Data persistence**: Tasks are stored in `localStorage`, meaning the task list is preserved even after refreshing the page.
- **Interactivity**: Inline editing allows users to quickly modify task titles without refreshing the page.

### Additional features:
- **Editing tasks**: Double-clicking on a task title allows inline editing without reloading the page.
- **Clearing completed tasks**: Allows users to delete all tasks marked as completed.
- **Keyboard support**: Task title editing can be completed using the "Enter" key or cancelled with the "Escape" key.

![todoedit](./description/edittodo.gif)
