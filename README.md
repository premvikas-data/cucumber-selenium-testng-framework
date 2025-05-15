# Cucumber Selenium TestNG Framework 🚀

This project is a full-featured SDET automation framework built using **Selenium WebDriver**, **Cucumber (BDD)**, **TestNG**, and **Maven**, following industry best practices for modularity, maintainability, and CI/CD readiness.

---

## ✅ Key Features

- 🧪 **Cucumber BDD**: Write readable Gherkin test scenarios
- 🧩 **TestNG Integration**: Easy runner config, parallel execution
- 🎯 **Page Object Model**: Clean separation of test logic and UI locators
- 🔄 **Dependency Injection**: Shared test context using **Picocontainer**
- 🧵 **Parallel Test Execution**: Speed up execution via TestNG XML
- 📸 **Screenshots on Failure**: Auto capture with Extent Reports
- 📊 **Reporting**: Beautiful ExtentReports integration
- ⚙️ **Maven & Jenkins Ready**: Trigger test execution via CI/CD
- 🧹 **Reusable Utility Classes**: Common methods and hooks
- 📁 **Data-Driven Testing**: Using feature file examples or external sources

---

## 📁 Folder Structure

- `features/` – Gherkin scenarios
- `stepDefinitions/` – Step implementations
- `pageObjects/` – UI abstraction
- `utils/` – Base classes, config readers
- `runner/` – TestNG/Cucumber runner classes
- `reports/` – HTML reports and screenshots

