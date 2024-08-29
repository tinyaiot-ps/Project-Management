# TinyAIoT
Introduction and Project Management of the TinyAIoT Project
<p align="center">
  <img src="Images/TinyAIoT Logo.png" alt="TinyAIoT_Logo" width="500"/>
  <img src="Images/Logo_Universität_Münster.png" alt="Universitaet Muenster_Logo" width="500"/>
</p>

Welcome to the documentation of our TinyAIoT project. This project was developed as part of a project seminar in the Information Systems and Geoinformatics Master's programs at the University of Münster together with the cities of Emsdetten and Laer.

The project is concerned with the development of sensors to advance cities in the smart city sector. On the one hand, a sensor was developed that measures the fill level of public garbage cans, and on the other, a sensor that records and analyzes the volume in an area. This data is collected and displayed in a dashboard, which the cities can then use to send optimized routes for emptying the garbage cans to their specialists, or to track the development of noise levels and, if necessary, develop measures to take action against violations.


# Content
1. [Project management](#Project-Management)
     - [Objectives and Requirements](#Objectives-and-Requirements)
     - [Roles and Responsibilities](#Roles-and-Responsibilities)
     - [Schedule](#Schedule)
     - [Communication and Meetings](#Communication-and-Meetings)
2. [Sensors](https://github.com/tinyaiot-ps/sensor/blob/main/README.md)
3. [Frontend](https://github.com/tinyaiot-ps/frontend/blob/main/README.md)
4. [Backend](https://github.com/tinyaiot-ps/backend/blob/main/README.md)


## Project Management
This section describes various aspects related to project management. It aims to provide a comprehensive overview of the entire project and assist those who wish to integrate the project into their own systems. By understanding our structure and methodologies, readers can adopt successful processes and avoid the pitfalls we encountered.





### Objectives and Requirements

At the start of the project, there was already the idea of equipping waste garbage cans with fill level sensors in order to show these fill levels on a dashboard and thus give cities the opportunity to create dedicated routes for full waste garbage cans so that not all waste garbage cans always have to be collected. The supervisors presented an illustration for this, which served as a leitmotif until the end of the project:
<p align="center">
  <img src="Images/Project start.png" alt="Project start" width="1100"/>
</p>
 Initial discussions with the cities revealed that, in addition to smart trashcans, there was also great interest in a sensor system that measures the noise level at certain times of the day in order to better identify problems such as disturbance of the peace. As a result, in addition to our main project of smart trashcans, we also defined a side project for noise detection, so we differentiated between these projects.

### Identified Problems
Both internally and in the various meetings with the cities, we identified the core problems that set the framework for the overall project:


| Smart Trashcans | Noise Detection |
|:---:|:---:|
|Most Trashcans are not attached to a sensor|Citizens like to use public spaces at night|
|Waste management employees have their fixed routes|Residents at public spaces want to rest|
|Cities do not have an overview on fill levels|Cities have limited law enforcement personnel|
|--> Waste retreival processes are inefficient|--> Citizens and residents are in conflict|

### Project Objectives
To address the challenges identified in the initial phase of the project, we established the following objectives:

| Smart Trashcans | Noise Detection |
|:---:|:---:|
| Create a TinyAIoT prototype for trashcans to measure their fill level| Create a TinyAIoT prototype for noise detection to measure decibel and the likeliness of noise|
| Create a dashboard based on the cities' requirements to display trashcan fill level and offer routing options| Create a machine learning model to identify the source of noise|
| Configure and deploy trashcan sensors and display them in the dashboard| Create a dashboard tab to display noise measurements|

According to the objectives of our project, we divided our team into different groups for the further course of the project.

---


### Roles and Responsibilities
The success of the TinyAIoT project was largely due to the effective collaboration and clear distribution of roles among the team members. The team, consisting of nine Information Systems Master's students, was strategically divided into three main groups, each with specific responsibilities essential to the project's goals. In order to gain further expertise in different subject areas, the students wrote seminar papers on the various topics before the start of the project in order to act as experts in a specific area. While each group focused on their primary tasks, cross-functional support was encouraged to ensure seamless project integration.

#### Sensors:
The Sensors team consisted of Anni, Michael, Shadia, and Philipp. This team dealt with the development and assembly of the prototypes for the two sensors. This included dealing with the individual components and deciding which of the components would ultimately be used. The installation of the corresponding software and, for the noise detection project, the creation of a machine learning program to identify the source of the noise were also part of the work. The process and further information on this can be found in chapter 2  [Sensors](https://github.com/tinyaiot-ps/sensor/blob/main/README.md).

#### Frontend:
The frontend team consisted of Sven and Kashif. This team was responsible for creating the dashboard mockups that were used during the communication with the cities to show actual and target states. The team also worked on implementing these mockups and designing the final dashboard. You can find more information and the corresponding code in chapter 3 [Frontend](https://github.com/tinyaiot-ps/frontend/blob/main/README.md).

#### Backend:
The backend team consisted of Nils and Ahsan. This team designed the corresponding structure and the databases that provided the dashboard with the required information on fill levels and noise levels. Login processes and settings were also processed by this team. A more detailed explanation and the corresponding code can be found in chapter 3 [Backend](https://github.com/tinyaiot-ps/backend/blob/main/README.md).


In addition to the three main groups, the project management area, led by Robin, also played a crucial role in ensuring the project stayed on track. Robin was responsible for coordinating communication between the cities and supervisors, organizing meetings, and preparing materials that were essential for the decision-making process.

---

### Schedule

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.



### Communication and Meetings

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.




