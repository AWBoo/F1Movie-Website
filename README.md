F1 Page Backend

This repository contains the backend for the F1 Movie Page, providing APIs to manage and retrieve data related to Formula 1.
Features

    Manage Movie
    Magage Reveiws

Technologies Used

    Java
    Spring Boot
    MongoDB

Getting Started
Prerequisites

    Java 11 or higher
    Maven
    MongoDB

Installation

    Clone the repository:

    bash

git clone https://github.com/yourusername/f1-page-backend.git
cd f1-page-backend

Configure environment variables in application.properties:

properties

spring.data.mongodb.uri=your_mongodb_uri
jwt.secret=your_jwt_secret

Build and run the application:

bash

    mvn clean install
    mvn spring-boot:run

API Endpoints
    
    GET /api/drivers - Retrieve all drivers
    GET /api/teams - Retrieve all teams
    GET /api/races - Retrieve all races
    POST /api/auth/login - User login
    POST /api/auth/register - User registration
    this is an example and not the actual endpoint to avoid mass spamming
