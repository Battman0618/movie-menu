# movie-menu

Software Requirement Specification
Movie List Application
Full Stack Development Course 
Bottega University
2023

Introduction
Scope: 
The application will be a movie list application which allows any user to enter and save a list of movies (such as a top 10, favorites, movies-to-watch, etc.) through a web application interface that displays saved movie items and allows users to input new items, edit existing items, or delete items (including title, MPAA rating, genre, a descriptive image, or any other information you want - try to keep it simple). 

This is a practice group exercise to build a basic full-stack application in a two-day time period. It will be developed locally and code will be written and edited by members of a collaborative student team. It will involve the production of 
an HTML, CSS and JavaScript client 
a Flask backend using Python
a SQLite database for data persistence

Each time will divide up roles according to preference / experience between front / back end.

Audience: 
The application will be used only by developer team members in a collaborative and educational setting, including testing and revision. It will be designed for hypothetical use by an average internet user.

Usage: 
The application will be built with sufficient user interface (UI) design to indicate its functionality without need for additional documentation.



Functional Requirements
The application will need to have:
A client (front-end) UI with functionality for GET, POST, PUT and DELETE requests for movie items (using a tool such as fetch or axios), as well as an organized representation of any stored data to the user.

A server (back-end)  API with endpoints for GET, POST, PUT and DELETE requests from the client, as well as efficient and organized logic to handle these requests. 

The application will not be built with any frameworks unless it is deemed necessary.

The application does not require authentication or any route protection / administrative roles. 

The codebase for the project will make use of version control and be stored on GitHub for collaborative access by team members and review. Each team will appoint a GitHub manager to handle the central repository and branching. 


External Interface Requirements
The application will be developed locally, deployment will not be necessary.

Any use of libraries via continuous delivery networks (CDNs) should be agreed upon by the team and noted in the project repository documentation (Bootstrap, JQuery).  

The application will need a client and server connected via API, as well as use of a SQLite database generated through the Flask library. Every API route / function should be tested and working properly.


Non-functional Requirements
The application does not need to be heavily styled or themed, and the UI design process does not need to be elaborate.

The application should be styled sufficiently for the functionality of the UI to be readily apparent to an average user, and for data to be displayed in an understandable way. 

Any special libraries or functional / design elements should be noted in the repository “readme” file. 




Additional Information
The application will have a two-day time period, after which we will evaluate what went well and what could be improved.
Work together, ask questions, and listen to other people’s ideas.
Ask for help if you get hung up on a particular issue - try to work it out but don’t let it halt all progress.
Keep in mind the minimum viable product (MVP) - make sure that the basic functionality is in place before worrying about additional issues. 
Determine what functionality needs to be implemented, and work step-by-step to achieve it - keep in mind that the app may not be completed in its entirety but the more you tackle, the more experience you gain. 
Don’t be afraid to make mistakes, this is the time and the place to make them!

Resources:

Axios: https://www.npmjs.com/package/axios
Front-end Data Input basics: https://www.freecodecamp.org/news/learn-crud-operations-in-javascript-by-building-todo-app/
Flask: https://www.dailysmarty.com/posts/steps-for-building-a-flask-api-application-with-python-3
