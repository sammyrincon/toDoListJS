To-Do List App

A simple, interactive To-Do List application built with HTML, CSS, and JavaScript. This project allows users to add, complete, and delete tasks, with persistent data stored in localStorage to maintain tasks across sessions.

Features

Add Tasks: Users can add new tasks by typing into an input box and clicking the "Add" button.
Complete Tasks: Clicking on a task toggles its completion state, visually marking it as completed.
Delete Tasks: Each task has a delete icon, allowing users to remove individual tasks.
Persistent Storage: Tasks are saved in localStorage, ensuring they persist across page reloads.
Responsive and User-Friendly UI: Styled using CSS for an engaging, easy-to-use experience.
Project Structure
index.html: The main HTML file containing the structure of the To-Do List.
style.css: The CSS file defining the layout and styles for the app, including:
Task list styling
Delete icon positioning and hover effects
script.js: The JavaScript file that implements functionality such as:
Adding, completing, and deleting tasks
Saving and retrieving tasks from localStorage
Event listeners for user interactions


How It Works
Adding Tasks: When a user enters text in the input box and clicks "Add", a new task is created and added to the list. If the input is empty, an alert is triggered to prompt the user to enter something.

Completing and Deleting Tasks:

Clicking on a task toggles a "checked" state, adding a line-through effect to visually mark it as completed.
Each task has a delete icon (span), positioned in the top-right corner, allowing for easy removal of tasks.
Saving and Loading Tasks:

When tasks are added, completed, or deleted, the list is saved to localStorage using saveData().
On page load, tasks are retrieved from localStorage via showTask() to display the user's previous tasks.
Installation and Setup


Clone the Repository:

git clone https://github.com/yourusername/your-repo.git


Usage
Add a Task: Type a task in the input box and click "Add".
Complete a Task: Click on any task to mark it as completed (strikethrough effect).
Delete a Task: Click the delete icon on any task to remove it.
Reload the Page: Tasks remain in the list even after reloading the page, thanks to localStorage.
Screenshot

Technologies Used
HTML: Structure of the To-Do List application.
CSS: Styling for layout, task completion, and delete icon effects.
JavaScript: Functionality to handle user interactions, task management, and local storage integration.
Future Improvements
Edit Tasks: Add functionality to edit existing tasks.
Clear All: Provide an option to clear all tasks at once.
Categories or Tags: Allow users to categorize or tag tasks for better organization.
Due Dates and Reminders: Add support for setting due dates and reminders for tasks.
