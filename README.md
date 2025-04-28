# JobHook - A full-stack web application that connects job seekers with employers

# Technologies Used
- React
- Spring Boot
- MongoDB
- Redux
- Tailwind
- MantineUI
- Tabler Icons

# Features
1. User Registration and Authentication
2. User Profile Management
3. Job Search and Application
4. Employer Functionality
5. Notifications and Alerts
6. Additional Features

# Installation Process
Prerequisites
1. Node.js and npm installed
2. Java 17+ installed
3. MongoDB installed and running locally (or use a cloud MongoDB like Atlas)

Clone the Repository
git clone https://github.com/vanshgoel1/jobhook.git
cd jobhook

Backend Setup (Spring Boot)
cd backend

Create an application.properties file inside src/main/resources/ and add your MongoDB URI and other configurations:

spring.data.mongodb.uri=mongodb://localhost:27017/jobhook
server.port=8080

Run the backend:
./mvnw spring-boot:run
(or use your IDE to run the JobhookApplication.java)

Frontend Setup (React)
cd frontend
npm install

Start the frontend:
npm start
The frontend will run on http://localhost:3000 and will be connected to the backend at http://localhost:8080.


