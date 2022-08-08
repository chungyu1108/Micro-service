# <CS361 GROUP24 LEARNING STUDY MICROSERVICE>
As a microservice, my partner could make something that takes in many strings as input, and creates a .csv file from it.

My program sends to my partner microservice a request ("give me a list of videos about algebra") and my microservice gives a simple reply back to me program


## Description

GOAL:
Refactor our old webpage interface to achieve better conversion and interaction on the login page with users.

Basically, when the user request the service from the webpage, my microservice manages its own data to the microservices principle. A single data store shouldn't be shared by two services. Instead, each service is in charge of maintaining its own private data stores, which other services are unable to directly access. Therefore, when the user request the ask question, first the server will find the answer and explanation for the database, than if the database did’t have the answer, the server will sent the request to the expert for the response.

final-project-team-bjy-final-project created by GitHub Classroom

Idea: Barbershop Website

Project Description: For our final project, we are creating a website that allows clients to book an appointment with a barber through a user interface. On our website there will be a calendar with the barber’s availability and the user will be able to select a certain date to book. For each date they select, certain time slots will be available on the slide down select. The user will choose a certain day of the week, and also what time they want (military time). Everytime the user wants to press the “Book appointment” button, they will have a pop up that tells them :

Their full name
Their cell phone number
Their email
what type of haircut they want
what day they want the haircut
what time they want the haircut
After the user has entered this information, their appointment will show up on the Google calendar like graph. Each haircut will be 1 hour long and depending on what time they choose, it will start at that time and one hour after that. After the user chooses this time, the time slot for that day will disappear from the dropdown menu.

For the nav bar, we are including a home page, an about page, a booking page, and a contact page. The home page will include pictures of recent work on a slide show using an NPM. On the about page, we will include the barber’s mission statement and descriptions of the team. The booking page will have the calendar and also allow users to make an appointment with the barber. Finally, the contact page will have the contact information of the barber and where to reach out.



## Features
example of the webpage look like
![Screen Shot 2022-08-01 at 11 23 06 PM](https://user-images.githubusercontent.com/91305697/182306195-be8155c9-e3c1-4103-b9dc-741efb4409c7.png)


## How to Contribute

If you created an application or package and would like other developers to contribute it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them here.
