# SafePassword Generator 🔑
### Modern Desktop Security Tool — JavaFX Application

![Status](https://img.shields.io/badge/status-completed-blue)
![Type](https://img.shields.io/badge/project-security--tool-orange)
![Stack](https://img.shields.io/badge/stack-JavaFX-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

**SafePassword Generator** is a specialized desktop utility developed in **JavaFX** to help users create highly secure, randomized passwords. Unlike basic CLI tools, this application provides a clean graphical interface to make security accessible and easy to manage.

The project demonstrates the use of **event-driven programming** and **JavaFX scene management** to build a functional security utility.

---

## 🎯 **Project Goals**

- **Visual Simplicity:** Create an intuitive GUI that allows anyone to generate a password in seconds.
- **Custom Entropy:** Implement logic to generate passwords based on specific length requirements.
- **Safe Distribution:** Provide a clear visual output of the generated credential.
- **JavaFX Mastery:** Apply core JavaFX concepts like `Stage`, `Scene`, and `Layouts` without complex FXML files.

---

## 🛠️ **Technologies Used**

### **Core Development**
- **Java 17+**: Main language.
- **java.util.Random**: The engine behind the randomized character selection.

### **Frontend (GUI)**
- **JavaFX**: Used for all visual components (Buttons, TextFields, Labels).
- **Event Handling**: To trigger password generation on user click.

### **Patterns & Tools**
- **Single-Class Architecture**: Efficiently managing the UI and logic in a cohesive structure.
- **Git & GitHub**: Version control.

---

## 📦 **Core Features**

### 🔹 **1. One-Click Generation**
- Instantly generates a unique password with a single button press.
- Combines uppercase, lowercase, numbers, and symbols for maximum security.

### 🔹 **2. Modern UI Layout**
- Built using a responsive layout that organizes all elements clearly on the screen.
- Uses JavaFX's native styling for a professional look.

### 🔹 **3. Secure Logic**
- The algorithm ensures that the output is non-deterministic and avoids predictable patterns.

---

## 🧩 **Architecture Overview**

The application is structured to handle everything within the JavaFX lifecycle:

- **The Stage (`start` method)**: Initializes the main window and title.
- **The Scene**: Defines the container for all GUI elements.
- **The Action Logic**: A dedicated event listener that pulls from a secure character pool and updates the UI field in real-time.


---
