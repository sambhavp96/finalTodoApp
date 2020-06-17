# finalTodoApp
**Final To Do Application.
Android  Studio MVVM: Final Todo Application

The first interface of the application is a login form. The login detail are:

- Username: admin
- Password: password

Once a user has logged in, the user will be redirected to a task inferface, where all the saved tasks are loaded.
The user can add a new task to the application by clicking on a floating action button on the bottom-right side of the application.

Once the floating action button in clicked, a form to add new task is displayed.

The form contains input field for title, description, priority, start date and end date. 
The form also contains two buttons, an Add Task button and a cancel button.
The form also contains validation to ensure title, description and start date fields are not empty.
If the add task button is clicked with empty title, description or start date fields, error messages are displayed.
If cancel button is selected a alert dialog box is shown with options to either return back to task list interface or not.

Once add task button is click with all the fields filled, the todo task is stored in the database.
The user is returned to task list interface, where they can also see their newly added task.

To delete a task, the user can swipe left, while the user can swipe right to edit.

To edit a task, user can also click on a task.

Each task on the tasks list interface contains a checkbox, which can be used to indicate whether a task is complete or not.
By default, when a new task is added, it is saved as incomplete. Checking a task, will save the task a complete, and a short toast message is displayed to the user.

There is also a menu on the top-right corner of the application, which shows list of option to delete all tasks, delete completed tasks, and to logout.
The delete all task menu button will delete all the tasks on the database.
The delete all completed tasks will only delete tasks that have been marked as completed.
While, the logout button will logout the user and redisplay the login page, where the user must login again to continue.
