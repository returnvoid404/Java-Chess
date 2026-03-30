# Java Chess Game

A desktop chess application built in **Java** using **Swing** for the user interface and **Guava 33.3.1** for core utilities.

## 🧠 Overview

This project simulates a complete chess game with interactive UI and full game logic including move validation, check/checkmate detection, and undo functionality.

## 📦 Features

- Interactive chessboard and piece movement using **Java Swing**  
- Complete chess rules enforced programmatically  
- Game state management with undo functionality  
- Utilizes **Guava 33.3.1** for efficient data structures and immutability  

## 🛠 Technology Stack

- **Java SE** (JDK 8 or higher recommended; Guava 33.3.1 compatible with Java 8+)  
- **Java Swing** for GUI  
- **Guava 33.3.1** (JAR included in `/assets`)  

## 📁 Project Structure
/assets
└── guava-33.3.1.jar # Guava library
/src
└── JChess.java # Main application file with entry point
└── ... other source files

## ⚙️ Running the Project

1. Copy `guava-33.3.1.jar` from `/assets` into your Java project’s `libs` folder (or any folder your IDE references for libraries).  
2. Make sure the IDE (IntelliJ IDEA or similar) includes the JAR in the project structure/classpath.  
3. Run the program from `JChess.java` which contains the `main` method.  

## 📌 Notes

- The project is designed as a learning exercise in Java UI development and algorithmic game logic.  
- All dependencies are included manually; no external build tools are required.  
