# Blue Ocean: Shredded

## Contributors:
  Agnese Castellucci, Andrew Feng, Anthony Chen, Jerry MacPherson, Jesus Solorzano, Sonia Ramlall, Thomas Faddegon
  

## Description
  Shredded is an app for fitness enthusiasts and newbies alike. It is a one-stop shop for both exercise and meal planning that gives users a detailed overview of their upcoming meals and workouts, along with how many calories they’ll be consuming and burning every day.

## Tech Stack
### Front End: 
  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) 
### Back End:
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
### Deployment: 
  ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
### Testing/Utilities: 
  ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)![cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e)
  
## Features
### User authentication:  
  New users are required to create a user account with log-in details. Upon entering a username and password they will be prompted for further information about themselves that will aid in calculations required by the application. User sessions are stored in a PostgreSQL database to allow them to persist across different site visits.
![login](https://user-images.githubusercontent.com/24445744/224448055-73784c3b-a3e9-4b69-9cf1-fea9efa23246.gif)

### Central Dashboard:
  The user will be able to see their workouts and meals for the day. From this dashboard, they can also access the add workout or add meal modals.
  ![navigate](https://user-images.githubusercontent.com/24445744/224450577-4adec2b5-f891-43a4-ab1e-9fd3e534b7e7.gif)
### Workout & Meal Modal:
  The user will be able to see their workouts and meals for the day. From this dashboard, they can also access the add workout or add meal modals.
  ![workoutmodal](https://user-images.githubusercontent.com/24445744/224450930-b2d5205f-c5fe-48a4-bfdc-9a66fa187f5f.gif)
### Calendar:
  The user can access a full-page calendar with each date square showing previews of the workouts and meals for the day. The right half of the screen will have a summary section showing the meals and workouts for the selected day, and clicking on any day in the calendar will display the meals and workouts for that day.
  ![calendar](https://user-images.githubusercontent.com/24445744/224450757-25e0876a-9c1f-4894-9166-f508a5cde9bf.gif)
### Nav Bar: 
  The nav bar will be visible on both the dashboard and the calendar pages, and will have options to add a meal, add a workout, go to the calendar, or go back to the dashboard. 

### Profile Page: 
  The profile page will track personal records and allow the user to see/edit their current information. Personal records will be displayed for every workout. If the user is an admin they can also access admin message posting, and app metrics.
![profileedit](https://user-images.githubusercontent.com/24445744/224449313-e546c28c-bae8-4554-9e62-ad358230dc80.gif)

---------- Gifs/pictures to be moved around --------

![quotesmessages](https://user-images.githubusercontent.com/24445744/224448649-e72ea72b-d450-4cd4-9bc9-005f51a5a1c6.gif)
![adminpanel](https://user-images.githubusercontent.com/24445744/224449303-bd1ae075-f9af-4100-9931-c3b91d6890a6.gif)
![pr](https://user-images.githubusercontent.com/24445744/224449311-10f3a45d-9550-40ed-b2bd-b3e7f2ed066e.gif)
![profileedit](https://user-images.githubusercontent.com/24445744/224449313-e546c28c-bae8-4554-9e62-ad358230dc80.gif)
![calendar](https://user-images.githubusercontent.com/24445744/224450757-25e0876a-9c1f-4894-9166-f508a5cde9bf.gif)
![foodmodal](https://user-images.githubusercontent.com/24445744/224450926-991a6544-b310-4c2d-8c4d-f51aae037cf2.gif)
![workoutmodal](https://user-images.githubusercontent.com/24445744/224450930-b2d5205f-c5fe-48a4-bfdc-9a66fa187f5f.gif)
