Phase 5 - Final Project


Project Pitch:


A platform to bring the classroom online. Teachers will be able to interact and assess their students’ performances as well as communicate with them. Students will be able to submit assignments as well as communicate with the class. 

User Story:

- As a teacher, I want to be able to create an account so I can log in and use the app.
- As a teacher, I want to be able to see my students and their grades
- As a teacher, I want to be able to create assignments for my students
- As a teacher, I want to be able to link assignments to GitHub or google docs
- As a teacher, I want to be able to organize a grade book based on weighted categories
- As a teacher, I want to be able to message my class or my students individually
- As a teacher, I want to be able to search for students by name
- As a teacher, I want to be able to create discussion posts

- As a student, I want to be able to create an account so I can log in and use the app.
- As a student, I want to be able to submit assignments 
- As a student I want to be able to message the teacher
- As a student I want to be able to contribute to discussion posts


Models and Relationships



Teacher

A Teacher has many Students

- id 
- full_name
- username
- password
- image_link
- grade_level

A Student belongs to a Teacher

- full_name
- username
- password
- image_link
- grade_level
- grade
- teacher_id

API

GET/api/teachers

{
	id: 1
	full_name: “Sam Shearer”
	username: “Mr. Shearer”
	password: “flatiron”
	image_link: “”
	grade_level: “10th grade”
}





Wireframe:

App

	Main Page
		- Login 
			- Username
			- Password			
      - Login button 

	Dashboard 
		- Your Profile
		- Your Classes
		- Search by student

	- Classes 
			- Students 
				- grades
			- Create assignment
			- Grade assignment
			- Create discussion
			- Send message
			- Edit settings

	

