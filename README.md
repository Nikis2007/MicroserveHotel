## 🚀 Technologies

- Java 17
- Spring Boot 3.x
- Spring Cloud
- Maven
- Eureka Service Discovery
- Spring Cloud Gateway

## 🔧 Getting Started

```bash
# Clone repository
git clone git@github.com:Nikis2007/MicroserveHotel.git
cd MicroserveHotel

# Build all services
mvn clean install

# Run Eureka Server first
cd eureka-server
mvn spring-boot:run

# Then run other services...
