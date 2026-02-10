# Chip-8 Emulator (Java)

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/GUI-Swing%2FJavaFX-red?style=for-the-badge)

## 🎮 Overview
A fully functional **Chip-8 Interpreter** written in **Java**. This project emulates the CPU architecture, memory management, and display logic of the classic COSMAC VIP microcomputer.

It can successfully run standard Chip-8 ROMs like *IBM Logo*, *Pong*, and *Space Invaders*.



https://github.com/user-attachments/assets/2c899619-8582-4858-b357-8fbdd26f56a9


## ⚙️ Key Features
* **Opcode Implementation:** Handled all 35 standard opcodes including arithmetic, graphics, and flow control.
* **Graphics Rendering:** Custom display panel drawing pixels at 60Hz.
* **Input Handling:** Mapped the original hex keypad (0-F) to the modern QWERTY keyboard.

## 🧠 What I Learned
* **Bitwise Manipulation:** Mastered bitwise operators (`&`, `|`, `^`, `>>`) to extract opcodes and manipulate 8-bit/16-bit registers.
* **CPU Architecture:** Implemented the core **Fetch-Decode-Execute** cycle, understanding how a processor interprets machine code.
* **Memory Management:** Managed the Stack, Program Counter (PC), and Index Register (I) to handle function calls and flow control.
* **Graphics Logic:** Learned how to implement **XOR rendering** (exclusive OR) for sprite drawing and collision detection.

## 🕹️ Controls
| Chip-8 Key | Keyboard |
| :--- | :--- |
| **1, 2, 3, C** | **1, 2, 3, 4** |
| **4, 5, 6, D** | **Q, W, E, R** |
| **7, 8, 9, E** | **A, S, D, F** |
| **A, 0, B, F** | **Z, X, C, V** |

## 🚀 How to Run
    * Load a ROM file (e.g., `pong.ch8`) from the `/roms` folder when prompted or via code configuration.
