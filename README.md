# Adaptive Tourism Recommendation Platform

## Team Details

| Team Member | ID Number  |
| ----------- | ---------- |
| G. Sirisha  | 2420030091 |
| Y. Yamini   | 2420030264 |
| A. Srinivas | 2420030136 |

**Supervisor:** Rajkumar Patil

---

## Abstract

The **Adaptive Tourism Recommendation Platform** is a web-based application designed to provide personalized tourism recommendations based on users' interests, preferences, budget, and travel requirements. Traditional tourism platforms generally provide common recommendations to all users without considering their individual needs. This project aims to overcome this limitation by adapting recommendations according to the preferences and requirements provided by each user.

The system allows users to register and log in, explore different tourist destinations, view destination details, and provide their preferences such as travel type, budget, location, and preferred activities. Based on these inputs, the platform recommends suitable destinations, helping users make better travel decisions.

The application is developed using **React.js** for the frontend, **Spring Boot** for the backend, and **MySQL** for database management. React.js provides an interactive and user-friendly interface, while Spring Boot handles the application logic and REST APIs. MySQL stores user details, destination information, preferences, and recommendation data.

The main objective of the project is to make tourism planning simpler, faster, and more personalized by providing recommendations that adapt to individual user requirements.

---

## Technologies Used

* **Frontend:** React.js
* **Backend:** Spring Boot
* **Database:** MySQL

---

## Project Objectives

* To develop a user-friendly tourism recommendation platform.
* To provide personalized destination recommendations.
* To consider user preferences, interests, and budget.
* To store and manage tourism-related information efficiently.
* To make travel planning easier and more convenient.
* To demonstrate the principles of adaptive software through personalized recommendations.

---

## Key Features

* User Registration and Login
* User Profile Management
* Tourist Destination Search
* Destination Details
* Preference-Based Recommendations
* Budget-Based Recommendations
* Travel Type Selection
* Favorite Destinations
* Personalized Tourism Suggestions
* Database Management

---

## Setup and Execution Instructions

### Prerequisites

Make sure the following software is installed:

* Node.js and npm
* Java JDK
* Maven
* MySQL
* Git
* Visual Studio Code / IntelliJ IDEA

---

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <project-folder>
```

---

### 2. Frontend Setup

Navigate to the React frontend directory:

```bash
cd frontend
```

Install the required dependencies:

```bash
npm install
```

Start the React application:

```bash
npm start
```

If the project uses Vite:

```bash
npm run dev
```

---

### 3. Database Setup

Open MySQL and create the project database:

```sql
CREATE DATABASE tourism_db;
```

Configure the database connection in the Spring Boot application.

File:

```text
src/main/resources/application.properties
```

Example configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/tourism_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Replace `your_password` with your MySQL password.

---

### 4. Backend Setup

Navigate to the Spring Boot backend directory:

```bash
cd backend
```

Run the Spring Boot application using Maven:

```bash
mvn spring-boot:run
```

The backend will start on the configured server port.

---

### 5. Run the Application

Start both the **Spring Boot backend** and **React frontend**.

Then open the frontend URL displayed in the terminal/browser.

The React frontend communicates with the Spring Boot backend through REST APIs, while Spring Boot connects to the MySQL database.

---

## Project Structure

```text
Adaptive-Tourism-Recommendation-Platform/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       └── resources/
│   ├── pom.xml
│   └── ...
│
└── README.md
```

---

## Current Phase Status

### Phase 1 – Project Planning and Requirement Analysis

**Status: In Progress**

### Completed

* [x] Team formation
* [x] Project topic selection
* [x] Problem identification
* [x] Project objectives defined
* [x] Abstract prepared
* [x] Technology selection
* [x] Initial project planning

### In Progress

* [ ] Requirement analysis
* [ ] Functional requirement identification
* [ ] System architecture design
* [ ] Database design
* [ ] UI design
* [ ] Project repository setup

### Upcoming

* [ ] React frontend development
* [ ] Spring Boot backend development
* [ ] MySQL database integration
* [ ] User authentication
* [ ] Recommendation module development
* [ ] Frontend-backend integration
* [ ] Testing and debugging
* [ ] Final deployment
* [ ] Project documentation

---

## Team

**G. Sirisha** — 2420030091
**Y. Yamini** — 2420030264
**A. Srinivas** — 2420030136

**Supervisor:** Rajkumar Patil
