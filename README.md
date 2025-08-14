# Programación de Vanguardia — Java Educational Project




---

## Overview
This repository contains coursework for the subject **Programación de Vanguardia**. It focuses on modern Java development practices, testing, automation, and documentation.

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

# Cómo ejecutar el proyecto

1. Abre una terminal en la raíz del proyecto.

2. Ejecuta el siguiente comando para iniciar el servidor:

```bash
mvn spring-boot:run
```

O bien, puedes compilar y ejecutar el JAR:

```bash
mvn clean package
java -jar target/programacion_de_vanguardia-0.0.1-SNAPSHOT.jar
```

El servidor se iniciará en el puerto 8090 (puedes cambiarlo en `src/main/resources/application.properties`).


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## License
Distributed under the MIT License.
