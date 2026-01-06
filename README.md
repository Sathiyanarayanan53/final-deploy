# 🎓 Faculty Portal (Ant Build)

A web-based application developed to manage faculty data efficiently. This project demonstrates core Java web capabilities using **JSP** and **Servlets**, built and managed using **Apache Ant**. It includes advanced features like bulk emailing and Excel data parsing.

🔗 **Live Demo:** [https://final-deploy-production.up.railway.app/](https://final-deploy-production.up.railway.app/)

## 🚀 Features

* **CRUD Operations:** Create, Read, Update, and Delete faculty/student records securely.
* **Bulk Mail Facility:** Send automated emails to multiple recipients simultaneously.
* **Excel Data Import:** Upload `.xlsx` or `.xls` files to populate the database automatically.
* **User Authentication:** Secure login for administrators and faculty.
* **Responsive Design:** Clean interface using JSP and CSS.

## 🛠️ Tech Stack

* **Language:** Java (JDK 8+)
* **Web Technologies:** JSP, Servlets, JDBC
* **Build Tool:** Apache Ant
* **Database:** MySQL
* **Server:** Apache Tomcat 9 (or compatible)
* **Libraries:** Apache POI (Excel), JavaMail API (Email), JSTL

## 📂 Project Structure

```text
FacultyPortal/
├── src/                  # Java source files
├── WebContent/           # JSP, CSS, JS, and WEB-INF
│   ├── WEB-INF/
│   │   └── lib/          # External JARs (POI, MySQL Connector, etc.)
├── build.xml             # Apache Ant build script
├── README.md             # Project documentation
└── database.sql          # SQL initialization script
