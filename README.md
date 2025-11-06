# Bike Club OKC

Frontend development for [Bike Club OKC.](https://www.bikeclubokc.com/home)

### Background

---

Bike Club OKC is a nonprofit organization that offers extracurricular activity to students in the Oklahoma City Public Schools district that leads groups of students on organized bicycle rides.

### Minimum Viable Product

---

Use there current website to add the features and functionality to better organize a method for parents of children to apply for program participation as well as for volunteers to apply to participate as well.

Create a web app that allows parents, volunteers, and facilitators to login and access a dashboard that provides information based on their user roles. This will allow facilitors to create, read, update, and delete the organized rides for different groups. Also, to better track which volunteers are assigned to which groups of student riders to better serve where the needs of volunteers will be best utilized.

Volunteer dashboards will show which assignment they will have, whether it be participating directly in a ride or serving some other needed labor like building out bicycles or picking up food and refreshments for events. The dashboard will also include a list of all the students in the orgranized ride that will have link for each student to access information to contact student's parent and other emergency contact information. They will also be able to check-in and start a ride as it begins that will potentially "track" a ride's time and route to be shared with facilitators and parents.

Parent dashboard will show schedules of organized rides and will "check-in" their child to confirm their participation in the organized ride that will be scheduled by a facilitator. Dashboard will also include information about the ride, specifically time and location of a ride's end to know when and where to pick there child up.

### Stretch Goal Features

---

- To create push notifications to parents and volunteers about upcoming organized rides as well as notifications about a rides end.

- To use a mapping API that shares location of volunteers within the app with facilitators and parents to track organized rides in real time.

- Add switch button to switch to Spanish translation.

## Project Management

Project will be managed and tracked through Jira. Scrum tickets will be created and assigned on project board in Jira.

## API Endpoints

1. **/users**

- /parents/login
- /volunteers/login
- /facilitator/login

2. **/parents**

- /table_info
- /student/:id
- /student/:id/table_info
- /calender
- /events
- /events/:id/table_info

3. **/volunteer**

- /calender
- /events
- /events/:id
- /events/:id/table_info
- /events/:id/students

4. **/facilitator**

- /school
- /calender
- /events
- /events/:id
- /events/:id/table_info
- /events/:id/students
- /notifications/:id/users
