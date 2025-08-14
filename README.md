# vehicle-booking-system-backend
Spring Boot REST API for vehicle booking and rental management — includes JWT authentication, PDF invoice generation, file uploads, and booking history tracking.

# Features
🔑 JWT-based authentication & role-based access
🚗 Vehicle booking CRUD APIs
📄 PDF invoice generation for completed bookings
📤 License file uploads for user verification
📜 Booking history with filtering
🐳 Docker Compose setup for quick deployment

# Tech Stack
Java 17
Spring Boot 3.x
Spring Security (JWT)
MySQL
Docker & Docker Compose
Apache PDFBox (or iText) for PDF generation

# Setup & Run
git clone https://github.com/yourusername/vehicle-booking-system-backend.git
cd vehicle-booking-system-backend
mvn clean install
docker-compose up -d

# API Documentation
Swagger UI available at: http://localhost:8080/swagger-ui.html

# Sample Screenshots 📸
Swagger screenshot
Postman request/response for license upload
PDF invoice example

# Future Features
Redis caching
Email notifications on cancel
Payment gateway integration
Multi-language support
