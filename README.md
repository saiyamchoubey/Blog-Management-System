# 📝 Blogging Platform (Spring Boot)

A simple yet powerful blogging platform built with **Spring Boot**, created as a learning project while exploring the Spring Framework.

🔗 **[Live Demo (FreeBSD 12)](https://tomcat.skaringa.dev/spring-blog-app/)**  

---

## ✨ Features

- 👀 **Anonymous Users**
  - View all blog posts and comments.

- 🔐 **Registered Users**
  - Create new blog posts ✍️  
  - View, edit, and delete only their own posts (CRUD functionality).  
  - Add comments to any post (own or others).  

- ✅ **Validation**
  - Title must be at least 7 characters.  
  - Body must not be empty.  
  - Additional validation rules to ensure content quality.  

- 🛡 **Security**
  - Spring Security authentication and authorization.  
  - Users can edit/delete **only their own posts**.  

- 🎨 **Frontend**
  - Built with Thymeleaf templates for clean, responsive UI.  

- 💡 **Code Quality**
  - Emphasis on **clean OOP principles**: separation of concerns, encapsulation, and extensibility.  

---

## 🛠 Tech Stack

- **Java 8**  
- **Spring Boot v2.2.6**  
- **Spring Web**  
- **Spring Data JPA**  
- **Spring Security**  
- **H2 in-memory Database**  
- **Lombok**  
- **Thymeleaf**  
- **Maven**  

---

## 🚀 Getting Started

### 1️⃣ Run the Application
```bash
./mvnw clean spring-boot:run
```
### 2️⃣ Access the Application
```bash
Open your browser and visit:
👉 http://localhost:8080
```
---

## 📂 Project Structure
spring-boot-blog-app/
├── src/                 # Source code
│   ├── main/
│   │   ├── java/        # Java source files
│   │   └── resources/   # Thymeleaf templates, application.properties
├── .mvn/                # Maven wrapper
├── pom.xml              # Maven configuration
├── mvnw / mvnw.cmd      # Maven wrapper scripts
└── README.md


