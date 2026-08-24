<div align="center">

# STM32 Library

**Reusable STM32 drivers, BSP modules, display libraries, and peripheral interfaces**



[📁 View Complete Library on Google Drive](https://drive.google.com/drive/folders/1TGUgCtuM7zuP9B2Q1TXZI9r4Hi6G3Usz?usp=sharing)

</div>

---

This repository contains reusable STM32 libraries and driver modules developed and tested during embedded systems development.

The goal is to maintain clean, reusable building blocks that can be integrated into STM32 projects instead of rewriting the same driver code every time. Because apparently humans enjoy rewriting the same I2C LCD driver seventeen times.

## 📦 What's Inside

| Module            | Description                                         |
| ----------------- | --------------------------------------------------- |
| **BSP**           | Board Support Package and hardware-specific drivers |
| **Display**       | Display interface and display-related drivers       |
| **Keypad Driver** | Matrix keypad scanning and input handling           |
| **LCD Library**   | Character LCD interfacing and control               |
| **Step Driver**   | Stepper motor driver and control functions          |

## 🗂️ Library Structure

```text
STM32-Library/
│
├── BSP/
│   ├── Inc/
│   └── Src/
│
├── Display/
│   ├── Inc/
│   └── Src/
│
├── keypad-driver/
│   ├── Inc/
│   └── Src/
│
├── lcd-lib/
│   ├── Inc/
│   └── Src/
│
└── step-driver/
    ├── Inc/
    └── Src/
```

## 🔧 Supported Concepts

* STM32 GPIO
* Timers
* PWM
* Interrupts
* Display interfacing
* Keypad interfacing
* Stepper motor control
* Board-level drivers
* Peripheral abstraction


