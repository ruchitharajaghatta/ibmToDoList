# To-Do list application
## Introduction
To Do List with a ReactJS UI that allows users to input "To Do" items with due dates, and a backend which saves previous to-do items, and backend services which returns all past to-dos, displays them in the UI, and allows for the user to query previous to-dos.

## Features
+ Personalized About Page providing brief explanation of app and background about creator
+ Takes in and displays items, validates no duplication
+ Displays the date and time of item addition
+ Allow users to mark items as complete, and removes completed items from list
+ Provide the due date for the task, and change the color of overdue tasks
+ Express application (Backend), with connection between backend and frontend and json file representing database of to-dos
+ **POST** request to submit data to a json file
+ Backend service to handle a GET request to return all todo lists
+ Backend service to handle a GET request to return todo lists that match the name sent as a parameter to this request
+ Front-end call the back-end service to get all todo lists currently stored when a user opens the Home page
+ UI components in the front-end to facilitate searching stored items

## Starting Up
Have NodeJS and npm installed then run the following commands in the terminal:
```
    npm install
    npm start
```