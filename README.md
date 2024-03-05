# EZSplit

EZSplit is an Expense Splitting Application built with Spring Boot and MySQL.

## Description

This application allows users to split expenses among a group of people. It's perfect for roommates, travel buddies, family members, and more.

## Features

- Create and manage groups of users
- Add expenses and split them among group members
- View individual balances within a group

## Getting Started

### Prerequisites

- Java 17
- MySQL

### Installation

1. Clone the repository

```sh
git clone https://github.com/yourusername/EZSplit.git
```

2. Navigate to the project directory

```sh
cd EZSplit
```

3. Install the dependencies

```sh
mvn install
```

4. Configure your MySQL database connection in `src/main/resources/application.properties`

5. Run the application

```sh
mvn spring-boot:run
```

## Usage

Once the application is running, you can interact with it through the exposed REST API endpoints. You can use tools like Postman or curl for testing.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
