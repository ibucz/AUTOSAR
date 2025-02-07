# AUTOSAR Software Architecture

This project explores the AUTOSAR software architecture, covering various layers, device drivers, and practical implementation for automotive embedded systems.

---

## Overview

- **Basic Software (BSW) Layer**
  - Explored **MCAL, ECUAL, Service Layer, and Complex Drivers**.
  - Learned about **BSW Modules** and various stacks like **Communications, Memory, and Diagnostics**.

- **RTE and Application Layers**
  - Gained insights into the **Run Time Environment (RTE)** and the design of software components for **ECUs**.

- **AUTOSAR Device Drivers**
  - Covered key aspects like **modular programming, API specifications, and error reporting (DET, DEM)**.
  - Studied **configuration variants**.

- **AUTOSAR Design for Interior Light Control ECU**
  - Learned how to **design and map software components across multiple ECUs** with **VFB (Virtual Function Bus)**.

- **AUTOSAR C Implementation**
  - Studied **AUTOSAR’s C rules** and **MISRA C 2004** compliance.

- **Automotive Buses**
  - Explored **LIN and CAN Protocols**.

---

## Implementation

- **Developed DIO and Port AUTOSAR Driver** for **TM4C Microcontrollers**.
- **Final Project:** Applied the **full layered architecture model**.

---

## Project Structure

```
AUTOSAR-Software-Architecture/
│-- src/        # Source code, AUTOSAR MCAL implementation, driver configuration
│-- docs/       # Documentation, system architecture, configuration details
│-- configs/    # Configuration files for AUTOSAR components
│-- README.md   # Project description and usage details
```

---

## How to Use

1. Clone this repository:
   ```sh
   git clone https://github.com/ibucz/AUTOSAR-Software-Architecture.git
   ```
2. Open the project in your preferred **IDE**.
3. Configure the **AUTOSAR stack** using the provided configuration files.
4. Compile and flash onto the **TM4C Microcontroller**.

---

## License

This project is licensed under the **MIT License**.

---

## Contributors
- [Your Name](https://github.com/ibucz)

Feel free to contribute to this project by submitting issues or pull requests! 🚀

