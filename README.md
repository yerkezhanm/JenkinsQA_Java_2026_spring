# Jenkins UI Test Automation — Java

## About the Project

Collaborative training project at RedRover School focused on automated UI testing of Jenkins.

**Tech Stack:** Java, Selenium WebDriver, TestNG, Maven, Page Object Model, Allure.

## My Contributions

I developed automated UI tests for Jenkins authentication and Freestyle Project management.

### Authentication — SignInTest.java

- Successful login with valid credentials.
- Negative tests for invalid usernames and passwords.
- Login validation with an empty username.
- Verification of authentication error messages and text color.

### Freestyle Projects — FreestyleProjectTest.java

- Creation, renaming, and deletion of Jenkins projects.
- Build configuration, execution, and triggers.
- Git repository and branch configuration.
- Positive and negative test scenarios.

## Automation Approach

- Page Object Model and shared BaseTest infrastructure.
- TestNG assertions.
- Reusable page methods and fluent method chaining.
- Allure annotations for test metadata.

## My Test Classes

- [SignInTest.java](src/test/java/school/redrover/SignInTest.java)
- [FreestyleProjectTest.java](src/test/java/school/redrover/FreestyleProjectTest.java)

## Attribution

This repository is a fork of a collaborative RedRover School training project. Other test classes and shared framework components were developed by multiple contributors.
