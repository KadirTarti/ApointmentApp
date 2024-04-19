# MIKE-TEC Car Repair Appointment App

https://anappointmentapp.netlify.app/

## Description

In this project, an interactive Appointment Application was developed. On the home page, under the Booking heading, there is the name and image of the repair operation for which an appointment will be made. Below these images is a list of all previously booked appointments.
When you click on any repair operation, previous appointments for that area and a form to create a new appointment are listed.
When the image is clicked again, it directs the user back to the home page.
The app includes data management functions for easy data manipulation and is designed to be responsive providing seamless user experience across devices.

## Outcome 🎥

![ApointmentApp](https://github.com/KadirTarti/KadirTarti/assets/150926891/31db2e16-0367-4c2e-b3e3-701109bab7eb)

##Project Planning & Management 🗺️

1-) View Operations:

- Create a page to display the list of car-repair-service, including their name, specialty and available appointment hours
- Filter repair-service information from Data.js and pass it to the repair-service list page

2-) View Appointments:
- Develop a page to display the selected car-repair appointment list, showing appointment date, time, and patient name
- Retrieve appointment information for the selected car-repair from Data.js and display it on the appointment list page

3-) Add Costumer:
- Design a form page to add a new appointment to a selected car-repair appointments, with fields for costumer name, date, and time selection
- Generate a new appointment using the information from the add costumer form and add it to the appointment list of the selected car-repair-service

4-) Data Management:
- Develop functions to update data, such as adding a new appointment, and set up functions to access Data.js and local storage.
- Implement functions to update both Data.js and local storage when a new appointment is added.


## Project Skeleton  👷


````
Appointment App(folder)
|
├── public
|     ├── index.html
│     └── robots.txt
├── src
│    ├── components
│    │       ├── addPatient
│    │       │        └── AddPatient.jsx
│    │       └── patientList
|    |                └── PatientList.jsx
│    ├── helper
│    │       └── data.jsx
│    ├── images
│    │       └── apointment3.png
│    ├── pages
│    │       └── Home.jsx
│    ├── App.js
│    ├── index.css
│    └── index.js
│
├── .gitignore
├── appointment-app.gif
├── LICENSE
├── package.lock.json
├── package.json
└── README.md

````

## Objective
Build a Hospital Appointment App using ReactJS.

### At the end of the project, following topics are to be covered; 🎯
HTML

CSS

JS

ReactJS

At the end of the project, students will be able to; 💪
improve coding skills within HTML & CSS & JS & ReactJS.

use git commands (push, pull, commit, add etc.) and Github as Version Control System.

Additional Data 📦
data.js
doctors.js
assets
Contributing 🤝
Your insights and contributions greatly enrich my projects! Whether you're bursting with fresh project concepts or have ideas to enhance existing ones, your input is invaluable. Feel free to open an issue to initiate a dialogue about your thoughts, or submit a pull request with your proposed modifications. Every contribution plays a vital role in my growth and improvement, so thank you for being an integral part of my community!


