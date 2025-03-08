# 📧 Email Writer - Spring Boot Backend  

## 🚀 Introduction  
The **Email Writer Backend** is a Spring Boot application that provides APIs for generating AI-powered email drafts. It processes requests from the React frontend and delivers email suggestions. This backend is designed to be **fast, scalable, and easy to integrate** with various frontends.

---

## 🛠 Installation & Setup  

 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/surya-vempa/Email-Assistant.git

2️⃣ Navigate to the Backend Directory
bash
Copy
Edit
cd Email-Assistant/email-writer-sb

3️⃣ Configure Environment Variables
Create an .env or application.properties file inside src/main/resources/ to store API keys and configurations.

Example (application.properties):

properties
Copy
Edit
server.port=8080
spring.application.name=email-writer-sb

# Database Configuration (If applicable)
spring.datasource.url=jdbc:postgresql://localhost:5432/email_db
spring.datasource.username=your_username
spring.datasource.password=your_password

# AI API Key (If using external AI services)
ai.api.key=your_api_key_here

4️⃣ Build and Run the Application
Using Maven (Recommended)
bash
Copy
Edit
mvn clean install
mvn spring-boot:run
Using Java (Manual Run)
bash
Copy
Edit
./mvnw spring-boot:run
The backend will start at http://localhost:8080/.

