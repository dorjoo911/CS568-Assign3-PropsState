# CS568 - Assignment 3, 4 - Props, State, Event Handler, List, Conditionals
- Implement the Advanced Hello example, both class and functional way.
- Implement the Counter example with increment and decrement, both class and functional (using a hook) way.
- Implement the "buttons" demo in class, both class and functional (using a hook) way.
- Implement the Todo app. All your data is in your App.js. Pass `todoItems` array down to TodoItem component. When click on the delete button, remove the todo item from the todo list.

```
App (tasks, addTask(), deleteTask())
├─ TodoAdd (newTask, addTaskOnClick())
├─ TodoList (isShown)
│  └─ TodoItem
│     ├─ TodoDeleteButton
│     └─ TodoEditButton (extra)
└─ TodoFooter
```
