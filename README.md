# 📝 Todo App — Fullstack Project

This is a fullstack **Todo App** built with:

* **Frontend**: React
* **Backend**: Spring Boot
* **Database**: MySQL

---

## 📁 Project Structure

```
todo-app/
├── frontend/    # React app
├── backend/     # Spring Boot app
```

---

## 🚀 Getting Started

### ⚙️ Prerequisites

* Node.js (v18 or above)
* Java 17 (or compatible)
* Maven
* MySQL (or use Docker)

---

### 💥 Run the Frontend

```bash
cd frontend
npm install
npm start
```

* Runs on: `http://localhost:3000`

---

### 🔧 Run the Backend

```bash
cd backend
mvn spring-boot:run
```

* Runs on: `http://localhost:8080`

📉 Make sure you set up your `application.properties` for MySQL:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/todos
spring.datasource.username=username
spring.datasource.password=dummypassword
```

---

## 🔐 Features

* Add / update / delete todos
* Mark todos as completed
* Responsive design
* REST API built with Spring Boot connected to MySQL

---

## 🛠️ Technologies Used

* React
* Spring Boot
* MySQL
* Maven
* Java 17

---



## 👤 Author

* **Esam Al-Shameri**
* GitHub: [Esam-2005](https://github.com/Esam-05-14)

---

## ✅ License

This project is open-source and available under the [MIT License](LICENSE).
