
# KYUCampusGrade

A distributed grading service developed for SPC 2401
(Distributed Operating Systems), Kirinyaga University.

## Overview

KYUCampusGrade provides remote grading services through
Java Remote Method Invocation (RMI).

The system supports:

- Lecturer mark submission.
- Student mark retrieval.
- Publication of marks.
- Student subscriptions and notifications.
- Concurrent remote requests.
- Failure handling and retry mechanisms.

## Technology Stack

- Java 21
- Java RMI
- Apache Maven
- JUnit 5
- Git / GitHub

## Project Structure

- `src/main/java`: Application source code.
- `src/test/java`: Automated tests.
- `tests`: Test plans and testing documentation.
- `docs`: Analysis, diagrams and final report.
- `evidence`: Logs, screenshots and test results.

## Prerequisites

- JDK 21+
- Maven
- Git

## Build

```bash
mvn clean package
```

## Run Tests

```bash
mvn test
```

## Running the Application

Instructions for starting the RMI registry,
server and lecturer/student clients will be added
once the implementation is complete.

## Contributors

See [TEAM.md](TEAM.md).
