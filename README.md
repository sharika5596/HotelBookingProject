# HotelBooking API Test Automation Project

Welcome to the **HotelBooking** RestAssured automation framework. This project is designed to automate and validate the RESTful web services of a hotel booking system using industry-standard tools and best practices.

---

## 🚀 Tech Stack

- **Java** (JDK 22+)
- **RestAssured** – API automation library
- **TestNG** – Test orchestration and configuration
- **Apache POI** – Excel data-driven testing
- **AssertJ** – Advanced assertions
- **Jackson API & GSON** – JSON parsing and serialization
- **Maven** – Build and dependency management
- **Log4j** – Logging
- **Allure Report** – Rich, customizable test reports
- **Jenkins** – CI/CD pipeline
- **Hybrid Folder Structure** – Clean and scalable project structure

---

## 📁 Project Structure

HotelBooking/
│
├── src/
│ ├── main/
│ │ └── java/
│ │ └── utils/ # Utility classes (e.g., JSON parsers, Excel readers)
│ ├── test/
│ │ ├── java/
│ │ │ ├── tests/ # Test classes
│ │ │ ├── base/ # Base test setup
│ │ │ ├── data/ # Test data models (POJOs)
│ │ │ └── endpoints/ # API endpoint classes
│ │ └── resources/
│ │ ├── config.properties # Configuration settings
│ │ └── testdata.xlsx # Excel test data
│
├── logs/ # Log files generated via Log4j
├── allure-results/ # Allure report results
├── Jenkinsfile # Jenkins pipeline config
├── pom.xml # Maven project descriptor
└── README.md


---

## ✅ Features

- Hybrid framework with modular, reusable components
- Data-driven testing using Excel via Apache POI
- Clean reporting with Allure integration
- Strong assertion mechanism using AssertJ
- Logging using Log4j for traceability and debugging
- Configurable and extensible structure
- Integrated CI/CD pipeline with Jenkins

---

## 🛠️ Setup & Execution

### Prerequisites

- JDK 22 or higher
- Maven 3.6+
- IntelliJ IDEA / Eclipse
- Allure CLI (for generating reports)
- Jenkins (optional for CI/CD)

### Steps

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/HotelBooking.git
cd HotelBooking

2.**Run tests using Maven**

```bash
mvn clean test

3.**Generate AllureReport**
Allure report is generated in the allure-results folder and can be viewed using:

```bash
allure serve allure-results

This will start a local server and open a browser window with the report dashboard.



4. **Run via Jenkins**
Set up a Maven job.

Use the provided Jenkinsfile for pipeline execution.

5. **Configuration**
Config file: Located in src/test/resources/config.properties

Test data: Located in testdata.xlsx under resources

 **Contribution**
Feel free to fork the repository, raise issues or pull requests


**License**
This project is open-source and available under the MIT License.
