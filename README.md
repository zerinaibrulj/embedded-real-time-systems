# Embedded & Real-Time Systems

This repository contains practical examples and mini-projects developed as part of learning **embedded and real-time systems** concepts using **STM32 microcontrollers** and **FreeRTOS**.

The focus of these projects is on task synchronization, inter-task communication, and interrupt handling in real-time environments.

---

## 🔧 Technologies Used
- **STM32**
- **FreeRTOS**
- **STM32CubeIDE**
- **HAL drivers**
- **C programming language**

---

## 📂 Project Structure

Each folder represents a separate concept or mechanism used in embedded and real-time systems:

- **Task Suspend & Resume**
- **Mutex**
- **Binary Semaphore**
- **Counting Semaphore**
- **Hardware Interrupt**
- **Timer Interrupt**

Projects are organized by concept to clearly demonstrate their purpose and behavior.

---

## 🧠 Covered Concepts

### 🧵 Task Management
- `vTaskSuspend()`
- `vTaskResume()`
- Task coordination and execution flow control

### 🔐 Synchronization Mechanisms
- **Mutex** for mutual exclusion when accessing shared resources
- **Binary Semaphore** for task signaling
- **Counting Semaphore** for managing multiple resources or events

### ⏱ Interrupt Handling
- **Hardware Interrupts** (external events triggering ISR)
- **Timer Interrupts** for periodic task execution and time-based events

---

## 🎯 Purpose
The goal of this repository is to:
- Understand real-time constraints and task scheduling
- Learn proper synchronization techniques
- Gain hands-on experience with FreeRTOS APIs
- Practice structured embedded software development

---

## 📌 Notes
- Each project includes only essential source files (`Core`, `Drivers`, `.ioc`)
- Build folders (`Debug`, `Release`) are excluded
- Projects are intended for educational and demonstration purposes

---

## 👩‍💻 Author
**Zerina Ibrulj**  
Faculty of Information Technologies  
Software Engineering

