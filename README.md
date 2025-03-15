# College Management System

## Overview
The **College Management System** is a Java-based desktop application designed to manage student records efficiently. The project features a **frontend built using Java Swing** for a user-friendly interface and a **backend powered by MySQL** to store and manage data securely.

## Features
✅ **Student Registration** – Add new students with details like name, department, and registration number.  
✅ **Search Functionality** – Find students using **Registration No, Name, or Department** dynamically.  
✅ **Update Records** – Modify existing student details and reflect changes in the database.  
✅ **Delete Records** – Remove student information securely.  
✅ **Database Connectivity** – Uses **JDBC with MySQL** for seamless data operations.  
✅ **User-Friendly UI** – Built with **Java Swing**, providing an interactive and responsive interface.  

## Technologies Used
- **Frontend:** Java Swing (GUI)
- **Backend:** MySQL (Database)
- **Database Connectivity:** JDBC
- **Version Control:** Git & GitHub

## Setup Instructions
### 1️⃣ Clone the Repository
```
git clone https://github.com/your-username/College-Management-System.git
cd College-Management-System
```

### 2️⃣ Configure MySQL Database
- Create a MySQL database named `java`.
- Execute the following SQL query to create the required table:

```sql
CREATE TABLE college (
    Registration_no INT PRIMARY KEY,
    name VARCHAR(100),
    department VARCHAR(100)
);
```

### 3️⃣ Configure JDBC Connection
- Open the project in **NetBeans**.
- Update **MySQL credentials** in the database connection section of your code:
```java
Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/java", "root", "your-password");
```

### 4️⃣ Run the Application
- Open NetBeans and build the project.
- Run the main class to launch the **College Management System**.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a **Pull Request**.

## License
This project is **open-source** and available under the **MIT License**.

---
Developed with ❤️ by **Nishant55559**

