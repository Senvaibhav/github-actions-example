# GitHub Actions Example

This is a Spring Boot project integrated with GitHub Actions for CI/CD pipeline automation.

## Project Description

This project demonstrates how to:

* Build a Spring Boot application
* Run automated tests using Maven
* Use GitHub Actions for Continuous Integration
* Prepare the project for Continuous Deployment (CI/CD)

## Tech Stack

* Java 17
* Spring Boot
* Maven
* Git
* GitHub Actions
* Jenkins (optional for advanced CI/CD)

## Project Structure

```text
src/
 ├── main/
 │    ├── java/
 │    └── resources/
 └── test/
      └── java/
.github/
 └── workflows/
      └── main.yml
pom.xml
README.md
```

## How to Run the Project

### Clone the repository

```bash
git clone https://github.com/Senvaibhav/github-actions-example.git
```

### Move to project folder

```bash
cd github-actions-example
```

### Build the project

```bash
mvn clean install
```

### Run the application

```bash
mvn spring-boot:run
```

## GitHub Actions Workflow

The workflow automatically performs:

* Code checkout
* Java setup
* Maven dependency installation
* Project build
* Test execution

Workflow file location:

```text
.github/workflows/main.yml
```

## Future Improvements

* Docker integration
* Jenkins pipeline integration
* Deployment to AWS / Azure / Render
* Kubernetes deployment

## Author

Developed by Sanu Dev
