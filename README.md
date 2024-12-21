# TaskManager Application


## Overview
The **Task Manager Application** is a web-based tool designed to help users organize and manage their tasks efficiently. Built using Java, JSP, and Servlets, this application provides essential features such as task creation, categorization, and progress tracking. The application ensures a smooth user experience with robust authentication and intuitive task management capabilities.

---

## Features

### Core Functionalities
1. **User Authentication and Authorization**
   - Secure registration and login.
   - Role-based access control.

2. **Task Management**
   - Add, edit, delete tasks.
   - Mark tasks as complete or incomplete.
   - Categorize tasks (e.g., Work, Personal).

3. **Task Organization**
   - Search and filter tasks by priority, category, or status.
   - Sort tasks by due date, priority, or creation date.

4. **Task Reminders**
   - Send notifications for upcoming deadlines.

5. **Dashboard View**
   - Display an overview of tasks (e.g., completed vs. pending).

---

## Technologies Used

### Frontend
- **HTML**: For structuring web pages.
- **CSS**: For styling the application.
- **JavaScript**: For client-side interactivity.
- **AJAX**: For asynchronous task updates without page reloads.

### Backend
- **Java**: Core language for business logic.
- **JSP (Java Server Pages)**: For dynamic web content.
- **Servlets**: For request and response handling.

### Database
- **MySQL**: For storing user and task-related data.

### Architecture
- **MVC (Model-View-Controller)**: To separate concerns and ensure maintainability.

---

## Prerequisites

1. **Java Development Kit (JDK)**: Version 8 or above.
2. **Apache Tomcat Server**: Version 9 or above.
3. **MySQL Server**: Version 5.7 or above.
4. **IDE**: IntelliJ IDEA, Eclipse, or any preferred Java IDE.

---

## Installation and Setup

### Clone the Repository
```bash
git clone https://github.com/your-username/task-manager.git
cd task-manager
```

### Configure Database
1. Create a MySQL database named `task_manager`.
2. Run the `schema.sql` file (located in the `database` folder) to set up the required tables.

### Update Configuration
Edit the `db.properties` file to configure the database connection:
```properties
db.url=jdbc:mysql://localhost:3306/task_manager
db.username=your-username
db.password=your-password
```

### Build and Deploy
1. Build the project in your IDE or using a build tool like Maven (if configured).
2. Deploy the `.war` file to the Apache Tomcat server.

---

## Usage
1. Start the Apache Tomcat server.
2. Open a web browser and navigate to `http://localhost:8080/task-manager`.
3. Register or log in to start managing tasks.

---

---

## Future Enhancements
- **Progress Tracking**: Add progress bars to visualize task completion.
- **Recurring Tasks**: Support for creating recurring tasks.
- **Mobile-Friendly Design**: Optimize for better usability on mobile devices.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

