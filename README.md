Java Learning Tracker
The Java Learning Tracker is a simple web application built using Spring Boot and Thymeleaf, designed to help users track their Java learning progress. It allows users to set a preparation time, add topics they have covered, and mark topics as completed. Additionally, a GitHub profile link is displayed in the top right corner for easy access.

Features
Set Preparation Time: Users can specify the amount of time they plan to dedicate to learning, which is displayed on the main page.
Track Covered Topics: Users can add the topics they have covered and mark them as "Covered" once completed.
GitHub Profile Link: The application includes a link to the user's GitHub profile in the top right corner of the page. When clicked, it opens the GitHub profile in a new tab.
Simple and Intuitive Interface: The application uses Thymeleaf templates to render a user-friendly HTML interface.
Technology Stack
Backend: Spring Boot (Java 11)
Frontend: Thymeleaf for dynamic HTML rendering
Database: In-memory H2 database (for demonstration purposes)
Build Tool: Gradle
Template Engine: Thymeleaf
Language: Java 11
Project Structure
Model: Represents data structures, such as Topic, which stores information about the topic name and its covered status.
Service: Provides business logic for managing topics and preparation time.
Controller: Handles HTTP requests, maps URLs to view templates, and manages user input.
Templates: Contains the Thymeleaf HTML templates for the user interface (e.g., index.html for the main page).
How It Works
Users navigate to the main page (http://localhost:8080), where they can view the current preparation time and list of topics.
They can set or update the preparation time using a form.
Topics can be added through an input field and displayed in a list format.
Users can mark a topic as "Covered" to keep track of their progress.
The GitHub link in the top right corner directs users to their GitHub profile.
Getting Started
Clone the repository: Clone the project from GitHub.
Build the project: Use Gradle to build the project (./gradlew build).
Run the application: Start the Spring Boot application using ./gradlew bootRun.
Access the application: Open a web browser and go to http://localhost:8080.
