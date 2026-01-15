# Project2 
## Task 2 – Spring Boot REST API Application

## 📝 Project Description

This project is Task 2 for the Spring Framework Apps assignment. The goal of this task is to create a fully functional REST API using Spring Boot. The application supports CRUD operations, exception handling, Swagger documentation, and an in-memory H2 database.

## 🛠 Technologies Used

- Java
- Spring Boot
- Spring Web (REST)
- Spring Data JPA
- H2 Database
- Swagger / OpenAPI
- Maven

## 🚀 How to Run the Application

1. Open the project in IntelliJ IDEA
2. Reload Maven dependencies
3. Run `Project2Application.java`
4. Application runs on port 8080

## 📡 API Endpoints

- `POST /api/v1/products` – create product
- `GET /api/v1/products/{id}` – get product by id
- `GET /api/v1/products` – get all products
- `PUT /api/v1/products/{id}` – update product
- `DELETE /api/v1/products/{id}` – delete product

## 💾 H2 Database

**URL:** http://localhost:8080/console

**JDBC URL:** `jdbc:h2:mem:testdb`

**User:** `sa`

**Password:** (empty)

<img width="1194" height="906" alt="H2 Console" src="https://github.com/user-attachments/assets/75843142-fa47-434f-b5d1-2be0d8970be5" />

## 📚 Swagger UI

**URL:** http://localhost:8080/swagger-ui/index.html

<img width="2188" height="1333" alt="Swagger UI Overview" src="https://github.com/user-attachments/assets/e4e46690-9724-49ef-8c49-676aabde83cd" />

<img width="2263" height="1421" alt="Swagger API Documentation" src="https://github.com/user-attachments/assets/2dd06021-d093-4fb7-b45c-b6c39ec91891" />

## 🏗 Application Architecture

- **Controller** – handles HTTP requests
- **Service** – business logic
- **Repository** – database access using JPA
- **Mapper** – maps request and response objects

## ⚠️ Exception Handling

Custom exception handling is implemented using `@ControllerAdvice`. When a product is not found, the API returns HTTP 404 with a descriptive error message.

## 🎥 Presentation

### H2 Database Console

<img width="1194" height="906" alt="H2 Database Interface" src="https://github.com/user-attachments/assets/68131772-61f6-49ad-9ac4-9a2d7f832478" />

### API Testing

<img width="1268" height="881" alt="API Test 1" src="https://github.com/user-attachments/assets/3bc73d2e-5b24-4f97-a968-42dc2e55cd6b" />

<img width="1178" height="929" alt="API Test 2" src="https://github.com/user-attachments/assets/d559a725-2973-4bb0-a07d-9b578c6f5359" />

<img width="802" height="490" alt="API Test 3" src="https://github.com/user-attachments/assets/37c6645e-dc0c-4102-b438-19683dbb34a2" />

<img width="1126" height="790" alt="API Test 4" src="https://github.com/user-attachments/assets/5ea98a5c-17e8-4fa4-bb0a-0d31d48abffd" />

<img width="1178" height="929" alt="API Test 5" src="https://github.com/user-attachments/assets/3591192e-f43a-410c-adcd-3b894fb89e1c" />

## 👨‍💻 Developer

**Abdulkhakim Murotaliev**

Vistula University of Finance and Business

Spring Framework Course

Task 2

January 2026

## 📄 License

This project was prepared for educational purposes.

## 🔗 Resources

- [Spring Boot Official Documentation](https://spring.io/projects/spring-boot)
- [Spring Data JPA Documentation](https://spring.io/projects/spring-data-jpa)
- [H2 Database Documentation](https://www.h2database.com/)
- [Swagger/OpenAPI Documentation](https://swagger.io/docs/)
- [Maven Documentation](https://maven.apache.org/)
