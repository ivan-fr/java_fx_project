# JavaFX Project

A simple JavaFX application built with Java 21 and Maven.

## Prerequisites

- Java 21 (OpenJDK 21)
- Maven 3.9+
- macOS (or adjust JAVA_HOME path for other systems)

## Project Structure

```
java_fx_project/
├── pom.xml
├── README.md
└── src/main/java/com/project/
    └── Main.java
```

## How to Run

1. Set JAVA_HOME to Java 21:
   ```bash
   export JAVA_HOME=/opt/homebrew/opt/openjdk@21
   ```

2. Run the application:
   ```bash
   mvn clean javafx:run
   ```

## What it does

The application displays a simple window with:
- A welcome label
- A button that changes the label text when clicked

## Dependencies

- JavaFX 21.0.1 (javafx-controls and javafx-fxml)
- Maven JavaFX Plugin 0.0.8
