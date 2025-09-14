# QA Automation Framework Showcase 🚀

This repository is a **portfolio showcase** of a Cucumber Hybrid Framework I built for UI testing.  
It demonstrates my ability to design **scalable, maintainable test automation** using Java, Selenium, and Cucumber.


## 📂 Project Structure

CucumberHybFrameworkDemoCart/
│
├── src/main/java/
│   ├── pages/                           # Page Object classes (UI elements & actions)
│   │   ├── AccountPage.java
│   │   ├── AccountSuccessPage.java
│   │   ├── HomePage.java
│   │   ├── LoginPage.java
│   │   ├── RegisterPage.java
│   │   └── SearchResultPage.java
│   │
│   └── utility/                         # Utility classes (helpers & common methods)
│       ├── CommonUtils.java
│       ├── ConfigReader.java
│       └── ElementUtils.java
│
├── src/test/java/
│   ├── factory/                         # WebDriver factory setup
│   │   └── DriverFactory.java
│   │
│   ├── hooks/                           # Hooks for @Before / @After scenarios
│   │   └── MyHooks.java
│   │
│   ├── runner/                          # Test runner (Cucumber + TestNG/JUnit)
│   │   └── TestRunner.java
│   │
│   └── stepDefinitions/                 # Step definition classes
│       ├── Login.java
│       ├── Register.java
│       └── Search.java
│
├── src/test/resources/
│   ├── config/                          # Configurations (URLs, environment data)
│   │   └── config.properties
│   │
│   └── features/                        # Gherkin feature files (BDD scenarios)
│       ├── Login.feature
│       ├── Register.feature
│       └── Search.feature
│
├── pom.xml                              # Maven build file (dependencies, plugins)
└── README.md                            # Project description (framework details)


---

## 🔹 Tech Stack
- Java  
- Selenium WebDriver  
- Cucumber (BDD)  
- JUnit 
- Maven    
- Cucumber JUnit Reports  

---

## 🔹 Features
- **Hybrid Design** → Combines Data-Driven + BDD approaches  
- **Page Object Model (POM)** → Reusable and maintainable test structure  
- **Reporting** → Integrated with Cucumber JUnit Reports for execution visibility  
 

---

## 🔹 Example Scenarios
- **Login.feature** → Login with valid/invalid credentials  
- **Register.feature** → Register workflow  
- **Search.feature** → Product search workflow  

*(Note: Real project code, data, and business logic are excluded for confidentiality. This repo contains only sample code and structure for demonstration.)*

---

## 🔹 Screenshots
### Cucumber HTML Report
![Cucumber Report](./screenshots/cucumber_report.png)

### Jenkins Pipeline
![Folder Structure Screenshot](./screenshots/Project-structure.png)

---

## 🔹 Why This Repo?
This is **not a full production codebase**, but a **showcase** of:
- Framework design skills  
- Best practices in test automation  


👉 For a full walkthrough, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/your-profile).
