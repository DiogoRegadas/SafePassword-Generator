# SafePassword Generator 🔑
### Java Console Application — Logic & Security Study

![Status](https://img.shields.io/badge/status-completed-blue)
![Type](https://img.shields.io/badge/project-logic--study-orange)
![Stack](https://img.shields.io/badge/stack-Java%20Core-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

**SafePassword Generator** is a lightweight Java-based CLI (Command Line Interface) tool designed to generate secure, randomized passwords. This project focuses on string manipulation, loops, and pseudo-random number generation to create credentials with high entropy.

Designed as a core logic exercise, it demonstrates how to handle user input and character sets to meet modern security requirements.

---

## 🎯 **Project Goals**

- **Randomized Logic:** Implement a robust character selection process using `java.util.Random`.
- **User Interaction:** Use `Scanner` to capture user preferences for password complexity.
- **Data Integrity:** Ensure that the generated strings meet the specified length and character requirements.
- **Clean Code:** Maintain a simple, readable, and efficient single-class structure.

---

## 🛠️ **Technologies Used**

### **Core Development**
- **Java 17+**: Core programming language.
- **java.util.Random**: For the random index selection algorithm.
- **java.util.Scanner**: For real-time user input handling.

### **Logic Patterns**
- **String Building**: Efficient concatenation of character sets (Uppercase, Lowercase, Numbers, Symbols).
- **Control Flow**: For-loops and conditional statements to build the final output.

---

## 📦 **Core Features**

### 🔹 **1. Personalized Generation**
- Prompts the user for the desired password length.
- Allows the program to combine different character pools automatically.

### 🔹 **2. High Entropy**
- Uses a diverse set of special characters, digits, and mixed-case letters to prevent brute-force attacks.

### 🔹 **3. Instant Execution**
- Fast and low-resource application that runs directly in any terminal or IDE console.

---

## 🧩 **Logic Breakdown**

The application follows a simple but effective logic flow:
1. **Input:** The user specifies the password length via the terminal.
2. **Pool Creation:** The program initializes a string containing all possible secure characters.
3. **Randomization:** A loop runs for 'N' iterations, picking a random character from the pool in each step.
4. **Output:** The final secure password is printed to the standard output.



---
