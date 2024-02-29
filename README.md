# Portfolio Analysis Project

## Overview

The Portfolio Analysis project provides a system for traders to upload a CSV file and analyze their portfolio in real-time. It consists of features such as managing positions, calculating market values, and analyzing option prices.

## Technologies Used

- Spring Boot
- Gradle
- H2 Database
- OpenCSV
- Apache Commons Math

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/atibrewal98/Crypto_JAVA_Challenge.git
```

2. Navigate to the project directory:

```
cd Crypto_JAVA_Challenge
```

3. Unzip the project directory and navigate into the directory:

```
cd PortfolioAnalysis
```

4. Build the project using Gradle:

```
gradlew build 
```

5. Test the project using Gradle:

```
gradlew test 
```

6. Run the application:

```
gradlew bootRun
```

7. Access the H2 application console in your web browser at [http://localhost:8080/h2-console](http://localhost:8080/h2-console).

## Project Structure

- `src/main/java`: Contains the main Java source files.
- `src/main/resources`: Contains configuration files and static resources.
- `src/test/java`: Contains test cases for the application.

## License

This project is licensed under the [MIT License](LICENSE).
