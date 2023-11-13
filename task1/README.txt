HTML (index.html):

The HTML file defines the structure of the to-do list.
It contains a container (div) to hold the list of tasks.
Inside the container, each task is represented as a div with two parts: the task info and the task date.
The task info section contains the task name and a placeholder description.
The task date section displays the date and time.
CSS (styles.css):

The CSS file is used for styling the to-do list. You can define fonts, colors, spacing, and other visual elements in this file.
JavaScript (script.js):

The JavaScript file adds interactivity to the to-do list.
It listens for a click event on the "Add Task" button.
When the button is clicked, it reads the task name from the input field with the id "taskName."
It then creates a new task element dynamically using document.createElement and populates it with the task name and a default description. It also includes the current date and time.
The new task element is inserted into the container using container.insertBefore(newTask, addTaskButton).
The input field for task name is cleared after adding the task.
The getCurrentDateTime function is used to get the current date and time in a specified format.
