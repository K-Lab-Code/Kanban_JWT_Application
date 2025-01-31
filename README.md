# Kanban_JWT_Application

## Description

This project is a simple kanban board project that lets you create and edit task that fall under Todo, in Progress, and Done. The application requires the user though to login with username and password to access the task board. All users for this app have the same board but can set task to say there for them specificy. The reason I made this project was for practice creating websites with jwt tokens for permission to access the site. I highly recommend anyone trying create a login feature for there webstie use jwts tokens to help secure there site.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

- Use this link [https://my-weather-app-uieh.onrender.com/](https://my-weather-app-uieh.onrender.com/) to get to deployed sit or if you want to use it on your own machine use following steps below.
- copy either all the files from the repository to your computer or use your git bash terminal to clone the repository down to your own machine. 
- make sure you have [node js](https://nodejs.org/en) and the package manager that comes with it.
- run the following command in project folder terminal: npm install. This will download all the needed dependencies for the project.
- make sure you have a postgress you can access for project and set up the .env file and fill out all the variables.
- you will also want to run the npm run seed command as before starting your project if your database is empty for project.

## Usage

- After installing the project run in the terminal for project: "npm run start:dev" (don't include the quotation marks). This will compile the type script files and start the project.
- The program some times will auto open the website in your browser but if not just put the following url in your browser: [http://localhost:3000/](http://localhost:3000/)
- once on the website you should see a prompt to login to create & view tickets for task that need to be done.
- click on the login button and it will take you to a login screen, fill out the username and password and click submit.
- if an invalid username or password is typed the login won't proceed further, but if you do get right it will take you to the ticket board.
- if you use the basic seed data with this project there will be three usernames JollyGuru, SunnyScribe, and RadiantComet all with password password. type any of those in to login same with link to deployed project.
- once on the ticket board you can look at the task in the three diffrent categories: Todo, In Progress, & Done.

![Pic of TIcket Board](./images/ScreenshotTicketBoard.png)

- click on the edit of the task and you can change the info of the ticket including its Name, which category its in, its desription of the task and the User that the task is for.
- once your done editing the ticket hit the submit button.
- The same menu can also be seen when you hit the make new ticket button, fill the info out and hit submit to make the new ticket.
- On any task you want to remove just hit the delete button and it will get removed from the board.
- If you dont have a token or token is expired after an hour and you try use the application to try and change the tickets it will kick you back to main screen.
- For a walkthrough of how to use the application [Click Here](https://drive.google.com/file/d/1ZHoSkD0CW5YdDofwclK1MyJvoU3Pe7Bc/view).

## Credits

Project Designer: Kalab Smith
- [K-Lab-Code](https://github.com/K-Lab-Code)
- [kalabsb@me.com](mailto:kalabsb@me.com)

## License

Distributed under the MIT License. See LICENSE.txt for more information.
