# Task Management Application for Final Project

## Description
A simple and intuitive task management application that allows users to create, manage, and track tasks and lists effectively. Built with Angular for the frontend and Node.js with Express and MongoDB for the backend. You can create an account in /login 
and then you can access your lists and tasks. You are able to create an account or sign in.

###Technologies Used
cd task-manager
cd api
npm install (install frontend dependencies)
npm start
cd frontend
ng generate component pages/task-view
ng generate component pages/signup-page
ng generate component pages/new-task
ng generate component pages/new-list
ng generate component pages/login-page
ng generate component pages/edit-task
ng generate component pages/edit-list
Web Request interceptors and Routing was implemented
npm install express
nodemon app.js
Postman was used to test the backend before connecting it successfully to the frontend.
npm install mongoose to install Database
for user authentication we used access tokens, jwt webtokens, crypto and bcrypt
Middleware and CORS headers were used

####Usage
Create an account or log in
add, delete and edit lists
add, delete and edit tasks
Mark tasks as completed by clicking it
/login to log in
/signup to sign up

###Features
user authentication
create, edit and delete tasks
Organize tasks into lists
mark tasks as complete
responsive design with bulma

#####Acknowledgments
Bulma for the CSS framework
Angular for the frontend framework
Node.js and Express for the backend
MongoDB for the database


######Problems encountered Along the way
CORS headers
router outlet
appcomponent standalone
compatible versoins
httpclient
buttons not redirecting correctly
buttons deleting the information
redirecting to login when first loading the page


