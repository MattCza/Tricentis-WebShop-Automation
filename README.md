# 🧪 Tricentis Demo Web Shop - Web Automation Testing Project

This project is a web automation testing suite for the [Tricentis Demo Web Shop](http://demowebshop.tricentis.com/), designed to demonstrate best practices in UI test automation using Java, Selenium, Maven.

## 🔍 Overview

The goal of this project is to automate key user flows of the Tricentis Demo Web Shop, including:

- User registration and login
- Product search and browsing
- Adding items to the cart
- Checkout and order placement
- Order confirmation and validation

The automation suite focuses on reliability, maintainability, and reusability by implementing clean code principles and structured test components.

## ⚙️ Tech Stack

- **Language:** Java  
- **Testing Framework:** TestNG / JUnit  
- **Automation Tool:** Selenium WebDriver  
- **Build Tool:** Maven / Gradle  
- **Design Pattern:** Page Object Model (POM)  
- **Reporting:** Allure / ExtentReports  
- **CI/CD:** GitHub Actions / Jenkins (optional)  
- **Test Data:** JSON / CSV (if applicable)

## 📁 Project Structure


```
├── src/test/java
│   ├── tests         # Test classes
│   ├── pages         # Page Object classes
│   └── utils         # Utility classes and helpers
├── test-data         # Test data files (JSON/CSV/etc.)
├── reports           # Generated test reports
├── pom.xml           # Maven build configuration
└── README.md         # Project documentation
```

## ✅ Features

- Modular Page Object Model for better maintainability
- Cross-browser execution support
- Externalized test data
- CI-friendly setup with easy integration
- Interactive and comprehensive test reports

## 🚀 Getting Started

Clone the repository and run tests locally:

```bash
git clone https://github.com/MattCza/tricentis-webshop-automation.git
cd tricentis-webshop-automation
mvn clean install
