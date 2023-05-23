# SDI-17-todo
SdI-17-todoList
Utilizing HTML to provide structure for the webpage
Utilizing JavaScript to make the page dynamic
Utilizing CSS to style the page
We first select the form, input field, and list from the HTML using document.getElementById.

We initialize an empty array todos to hold our todo items.

We add an event listener to the form that calls the addTodo function when the form is submitted.

In the addTodo function, we get the value of the input field, create a new list item with this text, add a click event listener to the list item that calls the toggleTodo function, and append the list item to the list.

The toggleTodo function toggles strikethrough style on the list item when it's clicked, indicating completion or pending status of the todo item.
