# even-app
this project is built on next.js, react.js and symfony + API Platform

1. MySQL Database 
   Install Xampp server and import mysql database and create new user and password in phpmyadmin

2. Event-Api
   IN event-api folder find .env file and chnage mysql database credentials 
   Open Terminal and locate project directory and run command "symfony server"

3. Event-Booking App (React)
   IN event-booking folder open terminal and run command "npm start"

4. Event-Admin-Dashboard App (Next)
   Locate directory event-admin-dashboard and run command "npm run dev"

For api documentation locate the link http://localhost:8000/api after running event-api

In Event app user can see a list of events on main page and click on even and explore the details of event
after that user can find booking button on click of booking button that will take user to booking page where
user needs to input details and define no of tickets to book the event and if tickets are not available user 
will get the message not enought tickets available and fields are fully validated no empty fields and email 
validation and no of tickets prevent - value or zeros

In dahsboard summary of events can be foud on the top and to login in dashboard

username: admin
password: password

and authentication is working using Next Auth and admin can create new event and update old event and delete booking and delete events 

designs are responsive and react app is designed in simple html and css and next app is desined in tailwind

Note: dont forget to run npm i command in all projects

Thank you for reading :) <3
