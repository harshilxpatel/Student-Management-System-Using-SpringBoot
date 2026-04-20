
This is a Student Management System REST API built using Spring Boot.
It provides basic CRUD operations to manage student records such as adding, retrieving, updating, and deleting students.


Tech Stack
✅ Java 17
✅ Spring Boot
✅ Spring Data JPA
✅ MySQL
✅ Maven


⚙️ Features
✔️ Get all students
✔️ Get student by ID
✔️ Add new student
✔️ Update student details
✔️ Delete student


🔗 API Endpoints

📌 Get All Students
GET /students

📌 Get Student by ID
GET /students/{id}

📌 Add Student
POST /students

Request Body (JSON):

{
"id": 4,
"name": "Rahul",
"branch": "IT",
"email": "rahul@gmail.com"
}

📌 Update Student
PUT /students/{id}

📌 Delete Student
DELETE /students/{id}



🗄️ Database Configuration

Update your application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/studentmanagement
spring.datasource.username=root
spring.datasource.password=root
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver



▶️ How to Run
1. Clone the repository:
git clone https://github.com/harshilxpatel/Spring-Security-Basics.git

2. Navigate to project:
cd student-management

3. Run the application:
mvn spring-boot:run

4. Open:
http://localhost:6669/students