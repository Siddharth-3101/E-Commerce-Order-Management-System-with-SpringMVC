# 🛒 E-Commerce Order Management System

## 📌 Overview

This is a simple **Spring MVC-based web application** that manages customer orders.
It allows users to perform **CRUD operations** such as adding, viewing, updating, and deleting orders.

The project is built using **Java, Spring MVC, JSP, and MySQL**, following the **MVC architecture** for better structure and maintainability.

---

## 🚀 Features

* ➕ Add new orders
* 📋 View all orders
* ✏️ Update existing orders
* ❌ Delete orders
* 🎨 Simple UI with CSS styling

---

## 🛠️ Technologies Used

* Java (JDK 8/15)
* Spring MVC
* JSP & JSTL
* MySQL Database
* Maven
* Apache Tomcat

---

## 📁 Project Structure

```
EcommerceOrderApp/
│
├── src/main/java/com/ecommerce/
│   ├── controller/
│   ├── model/
│   ├── repository/
│   ├── service/
│   └── util/
│
├── src/main/webapp/
│   ├── WEB-INF/
│   │   ├── view/
│   │   ├── web.xml
│   │   └── spring-servlet.xml
│   └── css/
│
└── pom.xml
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/EcommerceOrderApp.git
```

### 2️⃣ Import into Eclipse

* Open Eclipse
* File → Import → Existing Maven Project
* Select the project folder

### 3️⃣ Configure Database

* Create database:

```sql
CREATE DATABASE ecommerce1;
USE ecommerce1;

CREATE TABLE orders (
  orderid INT PRIMARY KEY AUTO_INCREMENT,
  customername VARCHAR(100),
  productname VARCHAR(100),
  quantity INT,
  price DOUBLE
);
```

* Update DB credentials in:

```
DBUtil.java
```

---

### 4️⃣ Run the Project

* Start Apache Tomcat server
* Right-click project → Run on Server

Open browser:

```
http://localhost:8080/EcommerceOrderApp/
```

---

## 📸 Screens

* Add Order Page
* View Orders Page
* Update Order Page

---

## 🎯 Learning Outcomes

* Understanding Spring MVC architecture
* Implementing CRUD operations
* Database connectivity using JDBC
* Working with JSP and controllers

---

## 👨‍💻 Author

**Sid**

---

## ⭐ Note

This project is created for academic purposes and learning Spring MVC fundamentals.
