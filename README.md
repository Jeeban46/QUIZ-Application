# Online Quiz Application

## Description 
The Online Quiz Application is a Java-based platform that allows users to take quizzes on various topics. It includes features for user authentication, quiz management, and progress tracking, providing immediate feedback on quiz performance. The application uses JavaFX for a user-friendly interface and MySQL for data persistence.

## Features
- **User Authentication:** Secure login and registration with password hashing and salting.
- **Quiz Management:** Admin functionality to create, edit, and delete quizzes and questions.
- **Quiz Taking:** Users can select and take quizzes, with immediate feedback on answers.
- **Progress Tracking:** Records and displays user quiz attempts and scores.
- **User Interface:** Developed using JavaFX for a smooth user experience.
- **Data Persistence:** MySQL database with JDBC for CRUD operations.

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- MySQL database
- JavaFX SDK

### Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/online-quiz-application.git
    ```
2. **Set up the database:**
    - Create a MySQL database named `quiz_app`.
    - Run the SQL scripts in the `sql` folder to create the necessary tables.
3. **Configure the database connection:**
    - Update the `DatabaseUtil.java` file with your MySQL database credentials.

4. **Build the project:**
    - Use your preferred IDE (like IntelliJ IDEA or Eclipse) to build the project.

### Usage
1. **Run the application:**
    - Launch the main class `QuizApp.java` to start the application.

2. **Register and Login:**
    - Users can create an account or log in with existing credentials.

3. **Admin Functions:**
    - Admins can create, edit, and delete quizzes and questions.

4. **Taking Quizzes:**
    - Users can select quizzes, answer questions, and get immediate feedback.

### File Structure
- `src/main/java`: Contains the Java source code.
- `src/main/resources`: Contains FXML files for JavaFX.
- `sql`: Contains SQL scripts to set up the database.

### Contributing
1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Contact
For questions or feedback, please contact jeebanranjand@gmail.com.
You can contact [LinkedIn](www.linkedin.com/in/jeeban-ranjan-das) also.

