

# 🚍 Mangalore Bus Route Guide

### Java Servlet + JSP + MySQL Web Application

The **Mangalore Bus Route Guide** is a dynamic web application designed to help users quickly **search and view Mangalore city bus routes**, stops, timings, and estimated travel durations.

The project is built using:

* **Java Servlets**
* **JSP**
* **JDBC (MySQL database)**
* **HTML, CSS, JavaScript**
* **Apache Tomcat**

---

# ✨ Features

### 🔹 User Features

* Register a new account
* Login with username and password
* Search for buses using a dropdown list (destination selection)
* View route descriptions, stops, and travel time

### 🔹 Backend Features

* Java Servlets handle all form submissions
* JDBC used for database communication
* Server-side validation
* MySQL-based route storage

### 🔹 Frontend Features

* Clean and responsive JSP interface
* Organized static assets (CSS, JS, Images)
* Simple and intuitive UI

---

# 📂 Project Structure

```
Mangalore_bus_route_guide/
│
├── database/
│   ├── create_tables.sql
│   └── insert_routes.sql
│
├── src/
│   └── main/
│       ├── java/
│       │   └── bus/
│       │       └── registration/
│       │           ├── login.java
│       │           ├── logout.java
│       │           ├── RegistrationServlet.java
│       │           └── SearchBus.java
│       │
│       └── webapp/
│           ├── assets/
│           │
│           ├── css/
│           │   ├── index-styles.css
│           │   ├── style.css
│           │   └── style.css.map
│           │
│           ├── fonts/
│           │   (your font files here, if any)
│           │
│           ├── images/
│           │   ├── abhiBus.jpeg
│           │   ├── abhibus3.jpeg
│           │   ├── abhibus2.jpeg
│           │   ├── busp.jpg
│           │   ├── bussss.jpg
│           │   ├── localbus.jpg
│           │   ├── mybus.jpg
│           │   ├── ourbus.jpg
│           │   ├── signin-image.jpg
│           │   └── signup-image.jpg
│           │
│           ├── js/
│           │   ├── main.js
│           │   └── scripts.js
│           │
│           ├── META-INF/
│           │   
│           │
│           ├── scss/
│           │   
│           │
│           ├── WEB-INF/
│           │   └── web.xml     
│           │
│           ├── index.jsp
│           ├── login.jsp
│           └── registration.jsp
│
├── .gitignore
└── README.md
```

---

# 🛢 Database Setup (MySQL)

### 1️⃣ Create Database & Tables

Run:

```
database/create_tables.sql
```

### 2️⃣ Insert Bus Route Data

Run:

```
database/insert_routes.sql
```

### 3️⃣ User Table Note

User records are inserted automatically upon registration.

---

# 🔧 Update Database Connection in Java

Inside your servlet files (`login.java`, `RegistrationServlet.java`, etc.), update:

```java
String url = "jdbc:mysql://localhost:3306/mangalore_bus_routes";
String username = "root";
String password = "YOUR_MYSQL_PASSWORD";
```

Ensure the **MySQL Connector/J** JAR is added to:

```
WEB-INF/lib/
```

---

# ▶ Running the Project (Tomcat)

1. Import project into **Eclipse**
2. Add **Apache Tomcat 9/10** server
3. Run the project:

   ```
   http://localhost:8080/Mangalore_bus_route_guide/
   ```

---

# 🧰 Technologies Used

| Category | Technology                   |
| -------- | ---------------------------- |
| Backend  | Java, Servlets, JSP          |
| Database | MySQL, JDBC                  |
| Frontend | HTML, CSS, JS                |
| Server   | Apache Tomcat                |
| Tools    | Eclipse IDE, MySQL Workbench |

---

# 👩‍💻 Developer

**Aishwarya H S**


---
