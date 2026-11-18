# Paper Trading Platform

A full-stack paper trading platform that simulates stock trading using virtual money. Users will be able to manage investment portfolios, execute simulated trades, monitor stock prices and track portfolio performance without risking real money.

## Project Status

🚧 Currently in Development.

## Technology Stack

### Backend
- Java 21
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Lombok
- Maven
- Bean Validation

### Frontend
- React
- Vite
- JavaScript
- React Router
- Axios
- Tailwind CSS
- Lucide React
- Recharts
- Oxlint

## Project Architecture

The project follows a separate frontend and backend architecture.

```text
paper-trading-platform/
│
├── paper-trading-api/
│   └── Spring Boot Backend
│       ├── config/
│       ├── controller/
│       ├── service/
│       ├── repository/
│       ├── entity/
│       ├── dto/
│       ├── exception/
│       └── security/
│
└── paper-trading-frontend/
    └── React + Vite Frontend
        └── src/
            ├── assets/
            ├── components/
            ├── pages/
            ├── services/
            ├── context/
            └── layouts/
```

## Planned Features

### 1. User Management
- User registration
- User profile management
- Account management

### 2. Authentication and Security
- JWT authentication
- Password encryption
- Role-based access control

### 3. Stock Management
- Stock listings
- Stock search by ticker symbol
- Stock price management
- External market data integration

### 4. Portfolio Management
- Create investment portfolios
- Virtual cash allocation
- Track stock holdings
- Calculate portfolio value
- Monitor profit and loss

### 5. Trading Engine
- Simulated buy orders
- Simulated sell orders
- Transaction history
- Balance validation
- Stock quantity validation

### 6. Dashboard
- Portfolio overview
- Stock market overview
- Portfolio performance charts
- Investment statistics

## Getting Started

### Prerequisites

- Java JDK 21
- Node.js and npm
- MySQL Server
- Maven
- IntelliJ IDEA
- Visual Studio Code
- Postman

### Backend Setup

**1. Navigate to the backend**

```bash
cd paper-trading-api
```

**2. Create the database**

```sql
CREATE DATABASE paper_trading_db;
```

**3. Configure MySQL**

Update `src/main/resources/application.properties`:

```properties
spring.application.name=paper-trading-api

spring.datasource.url=jdbc:mysql://localhost:3306/paper_trading_db
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

**4. Run the backend**

```bash
mvn spring-boot:run
```

### Frontend Setup

**1. Navigate to the frontend**

```bash
cd paper-trading-frontend
```

**2. Install dependencies**

```bash
npm install
```

**3. Start the development server**

```bash
npm run dev
```

## Development Objectives

This project aims to develop practical full-stack engineering skills, including:

- RESTful API development
- React component-based development
- Frontend and backend integration
- Relational database design
- Authentication and authorization
- Business logic implementation
- API testing
- Exception handling
- Software architecture
- Version control with Git

## Disclaimer

This application is intended for educational purposes only. All transactions use virtual money and do not involve actual financial investments.

## Author

**Tshepho Maimela**

GitHub: [MAMORARO](https://github.com/MAMORARO)

---

Built with React, Vite, Java and Spring Boot.
