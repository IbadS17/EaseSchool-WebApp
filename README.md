# EaseSchool Web Application

A school management system built with Spring Boot that helps manage students, courses, and administrative tasks.

## Features

- Student registration and management
- Course enrollment system  
- Holiday calendar
- Contact messaging
- User profiles and dashboard
- Responsive design for all devices

## Technologies Used

- Java 17
- Spring Boot 3.3.4
- Spring Security
- PostgreSQL Database
- Thymeleaf Templates
- HTML/CSS/JavaScript
- Bootstrap 5

## Requirements

- JDK 17 or higher
- PostgreSQL 14+
- Maven 3.9+

## Setup & Installation

1. Clone the repository:
```bash
git clone https://github.com/ibads17/easeschool.git
```

2. Create PostgreSQL database:
```sql
CREATE DATABASE easeschool;
```

3. Update database configuration in `application.properties`:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/easeschool
spring.datasource.username=<your-username>
spring.datasource.password=<your-password>
```

4. Build and run the application:
```bash
mvn clean install
mvn spring-boot:run
```

5. Access the application at: `http://localhost:8060`

## Testing

Run unit tests using Maven:
```bash
mvn test
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
