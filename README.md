# Binary Arithmetic Operations (Java Swing)

A desktop application built with **Java Swing** to perform basic arithmetic operations on **binary numbers**.  
The app supports:

- Binary **Addition**
- Binary **Subtraction**
- Binary **Multiplication** (using **Booth’s Algorithm**)
- Binary **Division** (quotient + remainder)

The goal of this project is to visualize and understand how binary arithmetic works, not only at integer level but also at algorithmic level (Booth multiplication).

---

## 1. Features

- Graphical User Interface (GUI) using **Swing**
- Input fields for:
  - `Binary Number 1`
  - `Binary Number 2`
- Operation selection using a combo box:
  - Addition, Subtraction, Multiplication, Division
- Result shown in **binary** form
- Multiplication implemented using a custom **Booth** inner class
- Simple error handling for invalid operations (e.g., division by zero)

---

## 2. Technologies Used

- **Language:** Java  
- **GUI Toolkit:** Swing (`JFrame`, `JPanel`, `JButton`, `JComboBox`, `JTextField`, `JLabel`)  
- **Layout Managers:** `BorderLayout`, `FlowLayout`, `GridLayout`  

---

## 3. Project Structure

Main file:

- `ArithmeticOperationsGUI.java`  
  - Contains:
    - `ArithmeticOperationsGUI` class (extends `JFrame`)
    - Inner `Booth` class implementing Booth’s multiplication algorithm

Key components:

- `binaryNum1Field`, `binaryNum2Field` – input fields  
- `resultBinaryField` – output field (read-only)  
- `operationComboBox` – select operation  
- `calculate()` / `performOperation()` – core control logic  

---

## 4. How to Run

1. Make sure you have **JDK 8+** installed and added to your PATH.
2. Save the source code as:

   ```text
   ArithmeticOperationsGUI.java


## Contact

Created by: MD SAKIB HASAN EMON

You can customize this README if you want different wording, a project badge, screenshots, or CI instructions. Tell me what to add and I will update it.
