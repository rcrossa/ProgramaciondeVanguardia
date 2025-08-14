# Vanguard Programming — Java Educational Project




---

## Overview
This repository contains coursework for the subject **Vanguard Programming**. It focuses on modern Java development practices, testing, automation, and documentation.

## Features
- Clear project structure
- Reproducible setup
- Linting and testing ready
- CI/CD friendly

## Prerequisites
- Java >= 17 (recommended: IntelliJ IDEA)

## Installation
Clone the repository:
```sh
git clone https://github.com/rcrossa/ProgramaciondeVanguardia
```

Open in your preferred IDE (IntelliJ IDEA recommended).

## Build & Run
- **Java (Maven):**
  ```sh
  mvn clean verify
  ```

## How to Run the Project

1. Open a terminal in the project root directory.

2. Run the following command to start the server:

```bash
mvn spring-boot:run
```

Alternatively, you can build and run the JAR:

```bash
mvn clean package
java -jar target/programacion_de_vanguardia-0.0.1-SNAPSHOT.jar
```

The server will start on port 8090 (you can change this in `src/main/resources/application.properties`).

## How to Configure IntelliJ IDEA to Run the Executable

1. Open the project in IntelliJ IDEA.
2. Go to **Run > Edit Configurations...**
3. Click the "+" button and select **Spring Boot**.
4. Set the main class to `com.example.DemoApplication`.
5. Apply and run the configuration.

## Development Workflow

For each new exercise or code implementation, follow these steps:

1. **Create a new branch from `develop`:**
   ```sh
   git checkout develop
   git pull
   git checkout -b feature/your-feature-name
   ```
2. **Develop your changes on the new branch.**

3. **When finished, merge your branch into `develop` using a squash commit:**
   ```sh
   git checkout develop
   git pull
   git merge --squash feature/your-feature-name
   git commit -m "Describe the exercise or implementation"
   git push
   ```
4. **Do not delete the feature branch after merging.**

This workflow keeps the commit history clean and makes it easy to track what was implemented for each exercise or feature.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## License
Distributed under the MIT License.
