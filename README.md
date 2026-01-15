# Selenium Java Framework

![Java](https://img.shields.io/badge/Java-17%2B-orange?style=for-the-badge&logo=java)
![Selenium](https://img.shields.io/badge/Selenium-4.x-green?style=for-the-badge&logo=selenium)
![TestNG](https://img.shields.io/badge/TestNG-7.x-red?style=for-the-badge)
![Maven](https://img.shields.io/badge/Maven-3.x-blue?style=for-the-badge&logo=apache-maven)


## 🔹 Overview
A **modern Selenium Java framework** for UI automation using **TestNG** and **Page Object Model (POM)** design.  
This framework is designed to be **scalable, reusable, and CI/CD-ready**, making it ideal for showcasing in interviews or as a professional portfolio.

---

## 🔹 Tech Stack
- **Java**: 17+  
- **Selenium**: 4.9+  
- **TestNG**: 7.7+  
- **Maven**: Project management and dependency management  
- **Reporting**: TestNG HTML reports (optional Extent/Allure)  
- **CI/CD**: GitHub Actions (optional)  

---

## 🔹 Features
- Page Object Model (POM) design for maintainable tests  
- Reusable helper classes and utilities in `components/`  
- Supports **Chrome**, **Firefox**, and remote browsers  
- Environment-based configuration (dev, staging)  
- Test data management using `resources/`  
- Generates HTML test reports  
- Structured for interview/demo purposes  

---

selenium-java-framework/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ ├── components/ # Base classes, reusable helpers
│ │ │ └── pageobjects/ # Page Object Models
│ │ └── resources/ # Configuration files
│ └── test/
│ ├── java/
│ │ └── tests/ # Test scripts organized by feature
│ └── resources/ # Test data (CSV, YAML, JSON)
├── reports/ # TestNG / HTML reports
├── pom.xml # Maven dependencies
├── README.md
└── .gitignore


---

## 🔹 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/snnarangsumit/selenium-java-framework.git
cd selenium-java-framework

2. Build the project
mvn clean install

3. Run all tests
mvn clean test

4. Run a specific test
mvn clean test -Dtest=LoginTest

5. View test reports

TestNG reports are generated in test-output/ or reports/ (if added)
## 🔹 Folder Structure

