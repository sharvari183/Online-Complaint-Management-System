# Online Complaint Management System

A Java-based desktop application designed to manage complaints through an interactive graphical user interface.

The system provides a centralized dashboard where users can register complaints, view complaint records, search complaints using a unique Complaint ID, and update complaint statuses.

## Features

### Dashboard UI

* Interactive dashboard interface
* Complaint statistics cards
* Total Complaints
* Registered Complaints
* In Progress Complaints
* Resolved Complaints

### Register Complaint

* Enter complainant name
* Add complaint subject
* Add detailed complaint description
* Generate a unique Complaint ID

### View Complaints

* View all registered complaints
* Display complaint details including:

  * Complaint ID
  * Name
  * Subject
  * Description
  * Status

### Search Complaint

* Search complaints using a unique Complaint ID
* Display complete complaint details

### Update Complaint Status

* Update complaint status to:

  * Registered
  * In Progress
  * Resolved

### Dynamic Dashboard

* Automatically update complaint statistics based on complaint status
* Track total, registered, in-progress, and resolved complaints

## Technologies Used

* Java
* Java Swing
* Object-Oriented Programming
* ArrayList
* Event-Driven Programming
* GUI Development

## Project Structure

```text
Online Complaint Management System
│
├── src
│   └── model
│       └── service
│           └── repository
│               └── utility
│                   └── exception
│                       └── main
│                           └── Dashboard.java
│
├── out
│
└── README.md
```

## How to Run

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Open the Project

Open the project folder in Visual Studio Code or any Java-supported IDE.

### 3. Compile the Project

Run the following command from the project root folder:

```bash
javac -d out src/model/service/repository/utility/exception/main/Dashboard.java
```

### 4. Run the Application

```bash
java -cp out main.Dashboard
```

## Application Workflow

```text
Open Dashboard
      ↓
Register Complaint
      ↓
Complaint ID Generated
      ↓
View Complaint
      ↓
Search Complaint Using ID
      ↓
Update Complaint Status
      ↓
Dashboard Statistics Updated
```

## Learning Outcomes

Through this project, I strengthened my understanding of:

* Java GUI development using Swing
* Object-oriented programming concepts
* Event handling and action listeners
* Managing data using ArrayList
* Creating interactive desktop applications
* Implementing CRUD-style complaint management operations
* Designing a user-friendly dashboard interface

## Future Improvements

* Database integration using MySQL
* User authentication and login system
* Admin and user roles
* Persistent complaint storage
* Email notifications
* Complaint priority levels
* Complaint history tracking
* Web-based version using Spring Boot

## Author

**Sharvari Patangrai**

---

If you found this project useful, feel free to explore the repository and provide feedback.

