# LinkedIn App - A Professional Networking Platform

### Overview
LinkedIn App is a professional networking platform designed to connect individuals, foster collaboration, and facilitate career growth. Built with a microservices architecture, the platform enables users to create profiles, post updates, engage with content, and receive notifications.

### Features
- **User Management**: User registration, authentication, and profile management.
- **Post Service**: Create, update, and interact with posts.
- **Notification System**: Real-time notifications using Kafka.
- **Microservices Architecture**: Independently scalable services deployed via Docker.
- **Containerized Deployment**: Uses Docker and Docker Compose for easy deployment.

### Tech Stack
- **Backend**: Java, Spring Boot
- **Build Tool**: Maven
- **Messaging**: Apache Kafka
- **Containerization**: Docker, Docker Compose
- **Database**: PostgreSQL (or MySQL, as needed)
- **Authentication**: JWT-based authentication

### Services Overview
| Service        | Description |
|---------------|-------------|
| **User Service** | Manages user registration, authentication, and profiles. |
| **Posts Service** | Handles creation, updating, and retrieval of posts. |
| **Notification Service** | Uses Kafka to send real-time notifications. |

### Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/ojasgulati/linkedin-clone.git
   cd linkedin-clone
   ```
2. Start the application using Docker Compose:
   ```sh
   docker-compose up -d
   ```
3. Access the services:
   - API Gateway: `http://localhost:8080`
   - User Service: `http://localhost:8081`
   - Posts Service: `http://localhost:8082`
   - Notification Service: `http://localhost:8083`

### Contribution Guidelines
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes and push them.
4. Create a Pull Request.

### License
This project is licensed under the Apache 2.0 License.
