# expense_tracker
Full-stack Expense Tracker application built using Spring Boot, MySQL, REST APIs, and JavaScript frontend.


# Expense Tracker

A full-stack Expense Tracker application built using Java Spring Boot, MySQL, REST APIs, and a simple HTML/CSS/JavaScript frontend.

## Features

- Add Expense
- Update Expense
- Delete Expense
- View All Expenses
- Total Expense Calculation
- Category Filtering
- External API Integration
- RESTful APIs
- MySQL Database Integration

---

## Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Data JPA
- Maven
- MySQL

### Frontend
- HTML
- CSS
- JavaScript

### Tools
- VS Code
- Postman
- Git & GitHub

---

## Project Structure

```text
src/main/java/com/example/expensetracker

├── controller
├── service
├── repository
├── entity
├── exception
```

---

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | /api/expenses | Add expense |
| GET | /api/expenses | Get all expenses |
| GET | /api/expenses/{id} | Get expense by ID |
| PUT | /api/expenses/{id} | Update expense |
| DELETE | /api/expenses/{id} | Delete expense |
| GET | /api/expenses/total | Get total expense |

---

## Run the Project

### Clone Repository

```bash
git clone https://github.com/yourusername/expense-tracker.git
```

### Configure Database

Create MySQL database:

```sql
CREATE DATABASE expense_tracker;
```

Update:

```properties
src/main/resources/application.properties
```

### Run Application

```bash
mvn spring-boot:run
```

Backend runs on:

```text
http://localhost:8080
```

---

## Frontend

Open:

```text
frontend/index.html
```

using Live Server extension in VS Code.

---

## Future Improvements

- JWT Authentication
- Swagger Documentation
- React Frontend
- Docker Deployment
- Charts & Analytics

---

## Author

Aneesh Denny
