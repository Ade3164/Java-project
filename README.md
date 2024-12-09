# Java Security Scanning Project

This project is designed to demonstrate the use of **Trivy** and **Snyk** to scan multiple popular Java libraries for security vulnerabilities. The goal is to generate security reports for these libraries and ensure they are up-to-date and secure.

---

## Objective

The primary objective of this project is to:

1. Integrate **Trivy** and **Snyk** tools into a Java project.
2. Scan the following libraries for vulnerabilities:
   - Spring Boot
   - Hibernate
   - Log4j
   - Gson
   - JUnit
   - Apache Commons Lang
   - Jackson Databind
   - Guava
   - SLF4J
   - Retrofit
   - OkHttp
   - Lombok
   - Joda-Time
   - Logback
   - Spring Security
   - Apache POI
   - Apache HttpComponents Client
   - Maven Shade Plugin
   - Jersey
3. Generate security reports with details of any identified vulnerabilities.

---

## Libraries Used

The project scans the following libraries for vulnerabilities:

| Library                        | Purpose                                          |
|--------------------------------|--------------------------------------------------|
| Spring Boot                    | Application framework for building Java apps.   |
| Hibernate                      | Object-relational mapping (ORM) library.        |
| Log4j                          | Logging framework.                              |
| Gson                           | JSON parsing and serialization.                 |
| JUnit                          | Unit testing framework.                         |
| Apache Commons Lang            | Utilities for strings, numbers, etc.           |
| Jackson Databind               | JSON processing.                                |
| Guava                          | Core utilities for Java.                        |
| SLF4J                          | Logging facade for Java.                        |
| Retrofit                       | HTTP client for REST APIs.                      |
| OkHttp                         | HTTP client for efficient networking.           |
| Lombok                         | Simplifies Java coding with annotations.        |
| Joda-Time                      | Advanced date and time API.                     |
| Logback                        | Logging framework compatible with SLF4J.        |
| Spring Security                | Authentication and access control.              |
| Apache POI                     | Work with Microsoft Office files.               |
| Apache HttpComponents Client   | HTTP client for making requests.                |
| Maven Shade Plugin             | Dependency management and packaging.            |
| Jersey                         | RESTful web services framework.                 |

---

## Prerequisites

- Java JDK 11 or later
- [Maven](https://maven.apache.org/) or [Gradle](https://gradle.org/)
- [Trivy](https://aquasecurity.github.io/trivy/)
- [Snyk](https://snyk.io/)

---

## Setup

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-directory>
