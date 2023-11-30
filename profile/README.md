# Polyjob Season Pack Project

This project was developed as part of the course "Internet and Web Architecture (IWA)" during the 5th year at Polytech Montpellier.
## Project Description

Polyjob Season Pack is an application designed for seasonal worker recruiters and an admin user. It provides essential functions for managing recruiters, seasonal job offers, candidate recommendations, recruitment processes, and feedback.

### Main Functionalities

1. **Recruiters Management**: Create, read, update, and delete recruiters' profiles with various details, including subscription formulas, establishment information, and supporting documents.
2. **Seasonal Job Offers**: CRUD operations for job offers with detailed information about job roles, periods, benefits, and establishments.
3. **Candidate Access**: Access to candidates based on subscription packages (Free, Silver, Gold, Platinum) offering varying levels of candidate information.
4. **Instant Messaging (Chat)**: Contact candidates via instant messaging within the application.
5. **Recruitment Validation**: Validate or invalidate a candidate's selection/recruitment for a job.
6. **Candidate Feedback**: Record notes and opinions on candidates at the end of their missions.

### Technology Stack

- **Frontend**: React Native with Expo platform and Redux for global state management.
- **Backend**: Microservices architecture with Spring Boot (Recruiter, Job, Offer, Authentication, Subscription, Candidate, Rating, Gateway), Kotlin (Candidate), and Webflux (RecruiterInfo).
- **Database**: PostgreSQL databases, one for each microservice.
- **Message Broker**: Kafka for inter-microservice communication.
- **Security**: Spring Security for authentication and authorization.
- **Build Tool**: Maven for dependency management.
- **Containerization**: Docker and Docker-compose for containerization and orchestration.
- **CI/CD**: GitHub CI for continuous integration and continuous deployment.

## Branches

The project repository includes at least two main branches: `dev` and `prod` for each microservice, allowing for development and production-ready code separation.

## Usage

The project comprises various microservices each responsible for different aspects of the application. Detailed documentation and instructions for running each microservice can be found within their respective directories.

The application has a frontend built in React Native and can be tested on the Android platform. The user interface is available in both French and English.

## Project Structure

- `Candidate`, `Rating`, `Offer`, `Authentication`, `RecruiterInfo`, `Gateway`, `Subscription`, `Job`, `Recruiter`: Individual microservices handling specific functionalities.
- `Frontend`: React Native application built with Expo and Redux.

## Team

The team comprises Alexis FONDARD MARTIN, Dorian CORREIA-MATEUS & Laura BENAITON.
