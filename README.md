# Exam Seat Allotment Application

## Overview

The Exam Seat Allotment Application is a web-based system built with Java Server Pages (JSP), Spring Boot, and MySQL. It is designed to automate the process of assigning seats to students for examinations, providing a streamlined and efficient way to manage exam logistics.

## Features

- **User Authentication:** Secure login system for administrators, professors, and students.
- **Seat Allotment Algorithm:** Efficient algorithm to assign seats based on predefined rules and constraints.
- **Student Information Management:** Maintain a database of student details, courses, and exam schedules.
- **Interactive User Interface:** Web-based interface using JSP for seamless user interaction.
- **Reports and Analytics:** Generate reports and analytics for exam seat allocation patterns.

## Technologies Used

- **Java Server Pages (JSP):** Front-end technology for dynamic web pages.
- **Spring Boot:** Backend framework for building Java-based enterprise applications.
- **MySQL:** Relational database management system for data storage.

## Project Structure

- `src/main/java/com/example/examseatallotment`: Java source code for the application.
- `src/main/resources`: Configuration files, database scripts, and Spring Boot properties.
- `src/main/webapp`: JSP files and static web resources.
- `src/test`: Test cases for the application.

## Setup and Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/exam-seat-allotment.git
    cd exam-seat-allotment
    ```

2. **Database Configuration:**

    - Create a MySQL database and configure the connection details in `src/main/resources/application.properties`.

3. **Build and Run:**

    ```bash
    ./mvnw spring-boot:run
    ```

    The application will be accessible at `http://localhost:8080`.

## Usage

1. **Login:**
   Access the application using the provided login credentials for administrators, professors, and students.

2. **Seat Allotment:**
   Perform seat allotment for upcoming exams based on predefined rules.

3. **Student Information:**
   Manage student details, courses, and exam schedules.

## Screenshots

Include screenshots of your application to showcase its functionality.

## Contributing

Feel free to contribute to the project by opening issues or creating pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Note:** Replace `your-username` and `exam-seat-allotment` with your actual GitHub username and repository name.
