# Employee Tracker - DMS Phase 4 (Spring Boot + SQLite)
📎 Author
Minh Tran
Module 10: DMS Phase 4


This is a **Data Management System (DMS) Project - Phase 4** for the course **CEN 3024C**. The application allows users to **perform full CRUD operations** on employee records via a **GUI**, with all data persisted in a **SQLite database**.

---

## ✅ Features Implemented

- ✅ Dynamic SQLite database loading via user input
- ✅ Full **CRUD operations** (Create, Read, Update, Delete)
- ✅ Input **validation** and **exception handling**
- ✅ GUI using **Thymeleaf + Spring Boot**
- ✅ Custom Feature: **Tenure Report** (Groups employees by years worked)
- ✅ Includes a **sample database** with **20+ employee records**

---

## 🧑‍💻 Technologies Used

- Java 17
- Spring Boot 3.x
- SQLite (via JDBC)
- Thymeleaf
- Maven
- IntelliJ IDEA

---

## 🗂️ Project Structure

src </br>
└── main</br>
├── java</br>
│ └── com.addingdatabase.assigment_dms_phase4</br>
│ ├── model</br>
│ ├── controller</br>
│ ├── service</br>
│ ├── repository</br>
│ └── config</br>
└── resources</br>
├── templates</br>
├── static</br>
└── application.properties</br>

---

## 🚀 How to Run the Application

### ✅ Prerequisites

- Java 17
- Maven
- IntelliJ IDEA
- SQLite (no installation needed, just the `.db` file)

### ✅ Steps to Run

1. **Clone this repository:**

```bash
git clone https://github.com/YOUR-USERNAME/employee-tracker-dms-phase4.git
cd employee-tracker-dms-phase4

2. Open in IntelliJ IDEA

File → Open → Select the project folder

3. Run the Application
In the main() method of AssigmentDmsPhase4Application.java, you'll be prompted to enter a path to the SQLite database:
Enter SQLite file path: /Users/yourname/Desktop/dms.db
4. Access the GUI in browser
After running, open your browser and go to:
👉 http://localhost:8080

📂 Sample Database File
Included: dms.db

Contains: 20+ employee records

Schema: employees (id, name, position, salary, hire_date, department, active)

🧪 Custom Feature
Tenure Report groups employees into:

1–5 years

5+ years

You can access it at:
http://localhost:8080/tenure
</br>
⚠️ Notes
❌ Do not hardcode any database file path. It's dynamically collected via terminal prompt.</br>

✅ Input validation ensures invalid or empty fields cannot crash the app.</br>

💾 Changes made via GUI are immediately stored in the database.</br>

📸 Screenshots (Optional)
Add here if needed: employee form, list, and tenure report views.</br>

👨‍🏫 Instructor Notes
Please test using the sample dms.db file provided.

No login/authentication is required.

You can test all CRUD + Custom feature through the GUI.








