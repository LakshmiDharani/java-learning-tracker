### Java Learning Tracker

The Java Learning Tracker is a simple web application built using Spring Boot and Thymeleaf, designed to help users track their Java learning progress. It allows users to set a preparation time, add topics they have covered, and mark topics as completed. Additionally, a GitHub profile link is displayed in the top right corner for easy access._

#### Features

1. Set Preparation Time: Users can specify the amount of time they plan to dedicate to learning, which is displayed on the main page.
2. Track Covered Topics: Users can add the topics they have covered and mark them as "Covered" once completed.
3. GitHub Profile Link: The application includes a link to the user's GitHub profile in the top right corner of the page. When clicked, it opens the GitHub profile in a new tab.
4. Simple and Intuitive Interface: The application uses Thymeleaf templates to render a user-friendly HTML interface.

#### Technology Stack

1. Backend: Spring Boot (Java 11)
2. Frontend: Thymeleaf for dynamic HTML rendering
3. Database: In-memory H2 database (for demonstration purposes)
4. Build Tool: Gradle
5. Template Engine: Thymeleaf
6. Language: Java 17


#### Project Structure

1. Model: Represents data structures, such as Topic, which stores information about the topic name and its covered status.
2. Service: Provides business logic for managing topics and preparation time.
3. Controller: Handles HTTP requests, maps URLs to view templates, and manages user input.
4. Templates: Contains the Thymeleaf HTML templates for the user interface (e.g., index.html for the main page).

#### How It Works

1. Users navigate to the main page (http://localhost:8080), where they can view the current preparation time and list of topics.
2. They can set or update the preparation time using a form.
3. Topics can be added through an input field and displayed in a list format.
4. Users can mark a topic as "Covered" to keep track of their progress.
5. The GitHub link in the top right corner directs users to their GitHub profile.

#### Getting Started

1. Clone the repository: Clone the project from GitHub.
2. Build the project: Use Gradle to build the project (./gradlew build).
3. Run the application: Start the Spring Boot application using ./gradlew bootRun.
4. Access the application: Open a web browser and go to http://localhost:8080.
