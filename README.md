TITLE : AI Crop Yield Prediction

An AI-powered web application that predicts crop yield using Machine Learning. The application is built using **Spring Boot** for the backend, **HTML, CSS, JavaScript, and Bootstrap** for the frontend, and **MySQL** for storing user and prediction data.


 Project Overview

The AI Crop Yield Prediction System helps farmers and agricultural researchers estimate crop yield based on environmental and agricultural factors such as rainfall, temperature, humidity, soil type, and fertilizer usage.

The system provides an intuitive web interface where users can enter crop-related information and receive accurate yield predictions.

 Features

- User-friendly web interface
- Crop yield prediction using Machine Learning
- Secure user login and registration
- Store prediction history
- Responsive design
- Fast and reliable prediction

 Technology Stack

 Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap

Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- REST APIs

 Database
- MySQL

 Machine Learning
- Python
- Scikit-learn
- Pandas
- NumPy

 Project Structure

AI-Crop-Yield-Prediction
│
├── src
│   ├── main
│   │   ├── java
│   │   ├── resources
│   │   └── templates
│   │
│   └── test
│
├── static
│   ├── css
│   ├── js
│   └── images
│
├── database
│   └── crop_prediction.sql
│
├── pom.xml
├── README.md
└── application.properties

 Database

The project uses **MySQL** as the relational database.

Example tables:

- Users
- Crop Details
- Prediction History

 Installation

Clone the Repository

git clone https://github.com/mithravsb/AI-Crop-yield-prediction.git

 Navigate to the Project

cd AI-Crop-yield-prediction

Configure MySQL

Create a database named:

CREATE DATABASE crop_prediction;

Update the **application.properties** file:

properties
spring.datasource.url=jdbc:mysql://localhost:3306/crop_prediction
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

 Run the Application

Using Maven:
mvn spring-boot:run

Or run the main Spring Boot application from your IDE.

Open your browser:

http://localhost:8080

 Prediction Workflow

1. User logs into the system.
2. Enter crop details.
3. Enter environmental parameters.
4. Submit the form.
5. Spring Boot processes the request.
6. Machine Learning model predicts crop yield.
7. Prediction is displayed and stored in MySQL.

Future Enhancements

- Weather API Integration
- Live Soil Analysis
- Multiple Machine Learning Models
- Dashboard with Charts
- Cloud Deployment
- Mobile Application Support

 Applications

- Smart Agriculture
- Crop Production Planning
- Government Agricultural Schemes
- Research and Development
- Farmer Decision Support

 Author

Mithra

GitHub: https://github.com/mithravsb

 License

This project is developed for educational and research purposes.


⭐ If you like this project, please give it a **Star** on GitHub!
