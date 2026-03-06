# SafePassword Generator 🛡️
### Desktop Security Tool — Java Swing Application

![Status](https://img.shields.io/badge/status-completed-blue)
![Type](https://img.shields.io/badge/project-utility-orange)
![Stack](https://img.shields.io/badge/stack-Java--Swing-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

**SafePassword Generator** is a functional desktop utility designed to create high-entropy, secure passwords. Built with **Java Swing**, the application allows users to customize the complexity of their credentials to meet modern security standards (uppercase, lowercase, numbers, and special characters).

This project focuses on **algorithmic logic**, **event-driven programming**, and **UI/UX design** using Java's native toolkit.

---

## 🎯 **Project Goals**

- **Entropy Control:** Implement a robust algorithm to generate truly random character strings.
- **User Customization:** Provide a flexible interface to toggle different character sets (symbols, numbers, etc.).
- **Clipboard Integration:** Enable seamless "Copy to Clipboard" functionality for immediate use.
- **Visual Feedback:** Use real-time UI updates to show the generated password to the user.
- **Clean Swing Implementation:** Apply proper Layout Managers and Event Listeners to ensure a responsive GUI.

---

## 🛠️ **Technologies Used**

### **Core Development**
- **Java 17+**: Core language and logic.
- **java.util.Random**: For the pseudo-random generation algorithm.
- **java.awt.datatransfer**: To manage the system clipboard integration.

### **Frontend (GUI)**
- **Java Swing**: Main framework for windows and components.
- **AWT**: For layout management and event handling.
- **Custom Iconography**: To enhance the visual identity of the tool.

### **Patterns & Tools**
- **Modular Logic**: Separation between the UI layout and the string generation logic.
- **Git & GitHub**: Version control and documentation.

---

## 📦 **Core Features**

### 🔹 **1. Dynamic Generation**
- Custom password length selection.
- Multi-criteria generation (Mix of symbols, numbers, and letters).
- Instant "Generate" button for quick credential creation.

### 🔹 **2. One-Click Copy**
- Integrated "Copy to Clipboard" feature that saves the password to the system's buffer, ready to be pasted into any service.

### 🔹 **3. Intuitive UI**
- Clean and centralized layout designed for efficiency.
- Error handling to prevent generating passwords with zero length or no selected characters.

---

## 🧩 **Architecture Overview**

The application follows a modular structure within the Swing framework:

- **UI Layer (`Interface.java`)**: Manages the frame, buttons, checkboxes, and the display field.
- **Logic Layer**: Handles the character pools (Arrays/Strings) and the loop-based selection of random characters.
- **Event Handling**: Uses `ActionListener` to trigger the generation and copy functions without freezing the main thread.



---
