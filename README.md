# Todo-Management-System-
A simple **Java Spring Boot web application** to manage your daily tasks.  
This project is created for learning and practicing **Spring Boot and MySQL integration**.

---

## 🚀 Features

- ➕ Add new tasks  
- 📋 View all tasks  
- ✏️ Update existing tasks  
- ❌ Delete tasks  
- 💾 Persistent storage using MySQL database

---

## 🛠 Tech Stack

- Java  
- Spring Boot  
- Spring MVC  
- Spring Data JPA  
- MySQL  
- Thymeleaf (if used for front-end)

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/todo-management-system.git
Open in your IDE (IntelliJ / Eclipse / VS Code)

Configure MySQL Database

Create a new database, e.g. todo_db

Update the application.properties file:

properties
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/todo_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
Run the application

Run the main class (TodoManagementSystemApplication.java)

Access the app at: http://localhost:8080

📁 Project Structure
css
Copy code
src
├── main
│   ├── java
│   │   └── com.example.todo
│   │       ├── controller
│   │       ├── model
│   │       ├── repository
│   │       └── service
│   └── resources
│       ├── application.properties
│       └── templates
└── test
📌 Purpose
This project is built as a practice project to understand the basics of Spring Boot, CRUD operations, and connecting a Java application with a MySQL database.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to open an Issue or Pull Request.
