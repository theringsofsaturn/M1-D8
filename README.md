
# JavaScript Challenge

# Module 1 / Day 8 at Strive School (EPICODE)
# Answers in the homework.html file

<!DOCTYPE html>
<!--
ASSIGNMENT RULES
- The solution must be pushed to the repository and be available for the tutors by the end of the day
- You can ask for tutor's help
- You can google / use StackOverflow BUT we suggest you to use just the material provided
- To test the page, just open it with your default browser.

ASSIGNMENT TOPIC
You are building a task list website.
The user should be able to see the list of tasks, add new ones, delete existing ones or sort them all alphabetically.
-->
<html lang="en">
  <head>
    <!-- EXERCISE 1:
    Specify the title, the charset (UTF-8) and the viewport of the page.
    -->
    <style>
      /* EXERCISE 2:  
       Create a CSS class for the task list with a different background color
       Create a CSS class for the task list item with a border, a bold text and a bigger font size
       Style every button of the page to be bigger
    */
    </style>
  </head>
  <body>
    <h1>Welcome to your personal Task List!</h1>
    <br />

    <span
      >You can add any task you like by writing it in the specified field and
      then press "Add new task"</span
    ><br /><br />

    <input type="text" id="newTask" />
    <input type="button" value="Add new Task" onclick="addNewTask()" />

    <!-- EXERCISE 3
        Create a button "Remove Last Task" to trigger the method "removeLast"
        -->

    <!-- EXERCISE 4
        Create a button "Remove First Task" to trigger the method "removeFirst"
        -->

    <ul id="myTaskList"></ul>

    <hr />

    <input type="color" placeholder="Color" id="colorPicker" />
    <input
      type="button"
      value="Change task background"
      onclick="changeTaskBackgroundColor()"
    />

    <hr />

    <input type="button" value="Sort" onclick="bubblesort()" />

    <script>
      /* EXERCISE 5: 
                Add a new task to the list.
                Suggestion:
                - Use document.getElementById to get the UL item and the input text
                - Use the document.createElement to create the new List Item
                - Append the LI child to the UL
            */

      /* EXERCISE 6: 
                Create a method "removeLast" which removes the last item from the task list
            */

      /* EXERCISE 7: 
                Create a method "removeFirst" which removes the first item from the task list
            */

      /* EXERCISE 8: 
               Create a method "getTasksAsArray" which returns, and prints to the console an array containing the tasks as strings
            */

      /* EXERCISE 9:
               Create a method "changeTaskBackgroundColor" which takes the color from the color picker with an 
               onchange event listener ad applies it as background to every list item
            */

      /* EXTRA */

      /* EXERCISE 10: 
               Create a method "bubbleSort()" which sorts the task list alphabetically using the bubble sort algorithm
            
               Use your spare time to beautify your task list with CSS.

               Suggestion:
               - Break the code into many function for semplicity 
               - Reuse the functions previously created
            */
    </script>
  </body>
</html>
