# STM32F407 LCD Interfacing

## Overview

This project demonstrates how to interface a **JHD162A 16×2 Character LCD** with the **STM32F407 Discovery Board** using **Embedded C** and **STM32CubeIDE**. The LCD is connected in **4-bit mode** to reduce GPIO usage, and a **10kΩ potentiometer** is used to adjust the display contrast.

## Hardware Required

* STM32F407 Discovery Board
* JHD162A 16×2 Character LCD
* 10kΩ Potentiometer
* Jumper Wires
* Breadboard
* USB Cable

## Software Used

* STM32CubeIDE
* Embedded C
* STM32 HAL Library

## Features

* 16x2 LCD interfacing in 4-bit mode
* LCD initialization
* Display characters and strings
* Cursor positioning
* Clear LCD display
* Adjustable LCD contrast using a potentiometer

## Hardware Connections

* **STM32F407 Discovery Board**
* **16x2 LCD**
* **10kΩ Potentiometer** (for LCD contrast)
* **Jumper Wires**

> *GPIO pin connections can be modified in the source code based on your hardware setup.*

## Project Structure

```
Core/
├── Inc/
│   └── lcd.h
├── Src/
│   ├── lcd.c
│   └── main.c
```

## How to Run

1. Open the project in **STM32CubeIDE**.
2. Build the project.
3. Connect the STM32F407 Discovery Board.
4. Flash the program to the board.
5. Power the LCD and adjust the potentiometer until the text becomes visible.

## Technologies Used

* Embedded C
* STM32F407 Discovery Board
* STM32 HAL Library
* GPIO
* JHD162A 16×2 Character LCD

## Author

**Nitin Ghugarkar**
