Author: nhatruong379

# RestfulAPI-example
An example of using RestfulAPI: display undone and done tasks of a user

Topic: Implementing an interface screen has the following components:
• Select user. List of users taken from API https://jsonplaceholder.typicode.com/users
• When selecting a user, call the API to get a list of that user's tasks according to userId, then displayed on the interface.
• Get task list from API https://jsonplaceholder.typicode.com/users/${userId}/todos
• When displayed, arrange unfinished tasks (completed = false) to the top, tasks completed (completed = true) are listed below.
• There is a button to mark unfinished tasks as done, calling the PATCH API https://jsonplaceholder.typicode.com/todos/${taskId}, body {"completed": true}
• Display the number of tasks completed/total number of tasks of the user at the bottom of the list.
• When clicking on the Mark done button, the loading status is displayed on the button itself, then, until the API request is made successfully, update the status of
task according to the response returned.

1. My approach (libraries/tools I use to implement) and reasons:
My approach is to utilize HTML, combining with CSS and JavaScript. Reasons: HTML and CSS are the front-end programming languages I use to build a simple, neat, and logical UI in order to display all necessary data and information on the screen. JavaScript is utilized as a back-end programming language to fetch the JSON data from API, then display those data on screen using JavaScript with a combination of HTML and CSS to fulfil the requirements.

2. How to run this project?
In summary: run file "index.html" the same as how normal HTML file runs on your computer.
In particular: You can download this repository or just download the file "index.html" to your IDE (e.g: Visual Studio Code, NetBeans, etc.). After that, run this "index.html" file on a web browser (e.g: Microsoft Edge, Mozilla Firefox, etc.) using your localhost. 

Self-assssment:
1. Runs with correct logic, no bugs: Well done
2. Neat UI with reasonable colors: Average
3. Source code is clearly organized, without misspellings: Well done
4. Disadvantages: most (about 80%) of the codes are not self-coded, they were taken from ChatGPT, and from the sample test webpage.
5. What can be improved: should self-code "index.html", and should try to self-code all JSON file with given data.

