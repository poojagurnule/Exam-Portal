

<h1 align = "center"> Exam-Portal </h1>
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.0.5-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>

The Exam Portal Project provides a comprehensive and user-friendly platform for managing exams efficiently. By embracing digital solutions, it empowers educators and students to engage in a more dynamic and effective learning environment. The project's focus on security, accessibility, and analytics ensures a seamless and rewarding experience for all stakeholders involved in the examination process.





## Requirements
* Spring Boot as Backend
* Angular as Frontend
### Spring Boot Requirements
* Spring Web
* JPA
* My SQL
* Secutity
* JWT
### Frontend
* HTML
* CSS
* BOOTSTRAP
* Angular Material
* Sweetalert2

## Here Two Roles Based Authentication
* Admin Panel
* User Panel
### Admin Panel:- 
* Admin can add categories And View categories
* Admin can add quiz,update quiz,delete quiz And View quizzes 
* Admin Can add Questions,update questions,delete questions And View questions
### User Panel:-
* User can attempt quizzes
* User Can View category And quizzes
* User Can acces active quizzes

## Local Setup of Project

1. Create a New Folder and clone both Frontend and Backend Repositories inside that folder.

2. Open cmd, go inside the frontend folder and execute following commands : <br>
   a). `npm install -g @angular/cli` <br>
   b). `npm install --scripts-prepend-node-path=auto` <br>
   c). `ng serve` (Runs frontend app) <br>

Frontend angular application started at `http://localhost:4200/`

3. Open MySQL Workbench and create a new database by executing `create database database_name`.

4. In the backend folder and change database connection details in `/src/main/resources/application.properties` file. <br>
   a). spring.datasource.url = jdbc:mysql://localhost:3306/`database_name`?serverTimezone=UTC <br>
   b). spring.datasource.username = `root` <br>
   c). spring.datasource.password = `password` <br>

5. Open cmd, go inside the backend folder and execute following commands : <br>
   a). `mvn install` <br>
   b). `mvn spring-boot:run` (Runs backend app) <br>

Backend Springboot application started at `http://localhost:8080/`

#### Navigate to `http://localhost:4200/`. <br>
![Screenshot 2023-08-02 200424](https://github.com/poojagurnule/Exam-Portal/assets/102051371/393e1378-46e1-42f4-935e-ed55c8d39886)
![Screenshot 2023-08-02 200442](https://github.com/poojagurnule/Exam-Portal/assets/102051371/0fe3b388-08b8-43e3-b3db-624188147f5d)




