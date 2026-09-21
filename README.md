
# Spring Boot Example Application

A sample Spring Boot application integrated with automated code analysis and CI/CD quality gates using **SonarQube Cloud** and **GitHub Actions**.

---

## 🛡️ Code Quality & Security Status

| Metric | Status / Rating |
| :--- | :--- |
| **SonarCloud Status** | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=randilu619_springboot-example&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=randilu619_springboot-example) |
| **Security Rating** | [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=randilu619_springboot-example&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=randilu619_springboot-example) |
| **Reliability Rating** | [![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=randilu619_springboot-example&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=randilu619_springboot-example) |
| **Maintainability Rating** | [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=randilu619_springboot-example&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=randilu619_springboot-example) |

---

## ⚙️ Tech Stack & Tools

* **Framework:** Spring Boot / Java 17
* **Build Tool:** Apache Maven
* **CI/CD Pipeline:** GitHub Actions
* **Code Analysis:** SonarQube Cloud

---

## 🚀 CI/CD Integration

The repository is configured with GitHub Actions to trigger an automated code quality scan on every `push` and `pull_request` to the `main` branch.

### Workflow Configuration
The pipeline is located at `.github/workflows/build.yml` and executes the following steps:
1. Checks out the code.
2. Sets up the JDK environment.
3. Caches Maven dependencies.
4. Runs `mvn verify sonar:sonar` to execute test coverage and static code analysis with SonarCloud.

---

## 📊 Live Analysis

View full analysis reports, debt overview, and code metrics on [SonarQube Cloud](https://sonarcloud.io/project/overview?id=randilu619_springboot-example).
