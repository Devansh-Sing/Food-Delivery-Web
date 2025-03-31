# Food Delivery Website

A comprehensive full-stack Food Delivery App developed with **Spring Boot (Java)** for the backend and **HTML, CSS, and JavaScript** for the frontend. This application enables users to seamlessly browse and order their favorite dishes. items, place orders, and manage authentication.

## Features
- **User Authentication:** Sign up, login
- **Restaurant Browsing:** Filter by cuisine, rating, or distance
- **Menu Display:** Detailed item descriptions with images
- **Order System:** Add items to cart, apply promo codes, checkout
- **Review System:** Rate restaurants and delivery experience



## Technologies Used

### Frontend:
- **HTML** (Structure)
- **CSS** (Styling)
- **JavaScript** (Client-side Logic & API Calls)

### Backend:
- **Java** (Spring Boot)
- **Spring Boot** (REST API)
- **Spring Security** (Authentication & Authorization)
- **MySQL** (Database)
- **Spring Data JPA** (Database Access)
- **Maven** (Dependency Management)

### Tools & Platforms:
- **VS Code** (Code Editor)
- **MySQL Workbench** (Database Management)
- **Git & GitHub** (Version Control)
- **Postman** (API Testing)


## Installation & Setup

### Frontend Setup
1. Open `index.html` in a browser.
2. Ensure `script.js` is correctly calling the backend API.

### Backend Setup (Spring Boot)
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/food-delivery-app.git
   cd food-delivery-app
   ```
2. Configure **application.properties** with your MySQL database credentials.
3. Build and run the application using Maven:
   ```sh
   mvn clean package
   mvn spring-boot:run
   ```
4. API will be available at: `http://localhost:8080`

### Database Setup (MySQL)
1. Create a database in MySQL:
   ```sql
   CREATE DATABASE fooddelivery;
   ```
2. Ensure MySQL is running and update the connection details in **application.properties**.
3. Run the application to automatically create tables.

## API Endpoints
- `GET /api/foods` → Fetch all available food items
- `POST /api/auth/signup` → Register a new user
- `POST /api/auth/login` → Login user
- `POST /api/orders` → Place an order

## Contributing
We welcome contributions from the community!

# Guidelines

- Follow existing code style and patterns
- Keep PRs focused (avoid bundling unrelated changes)
- Update documentation when adding new features

**We appreciate all contributions, big or small! 🚀**

## Contact
**For questions or support:**

Project Lead: Devansh Singh (thakurdevansh165@gmail.com)
---
### Author: Devansh Singh
