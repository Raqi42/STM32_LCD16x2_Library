![Screenshot 2025-03-25 231702](https://github.com/user-attachments/assets/12fc3a5a-a752-4edb-85b6-21c754d53c9f)

# STM32F103C8T6_LCD16x2_Library

This repository contains a library for interfacing the STM32F103C8T6 Blue Pill microcontroller board with an alphanumeric 16x2 LCD. The library is designed to be versatile and reusable, making it easy to integrate with other STM32F103C8T6 projects.

## Project Overview

The example project demonstrates the implementation of the library, showcasing an interactive program where pressing an interrupt-based push button triggers the following sequence:

1. A **beep sound** is produced by a buzzer.
2. The displayed text shifts to the left until it disappears from the screen.
3. The text then scrolls back onto the screen from the right.
4. The text performs a **ping-pong motion**—scrolling back and forth—before settling in its original position.
5. A final **beep sound** is produced, indicating the process is complete.

This sequence highlights the advanced functionality of the library and its ability to handle LCD text manipulation and synchronization with hardware events.

## Features

- Easy interfacing of the STM32F103C8T6 Blue Pill board with the LCD16x2 module.
- Text shifting, scrolling, and ping-pong motion capabilities.
- Interrupt-driven functionality using push buttons.
- Hardware integration with a buzzer for sound notifications.

## Getting Started

### Prerequisites

- STM32F103C8T6 Blue Pill board.
- LCD16x2 alphanumeric module.
- Buzzer and interrupt-driven push button.
- STM32CubeIDE or other ARM development environments.

### Demo

Below is a summary of the interactive sequence executed in the demo project:

 1.  Text shifts left → disappears → scrolls from right.
 2.  Performs a ping-pong motion → settles in place.
 3.  Buzzer indicates start and end of process.


- step by step video tutorial: https://www.youtube.com/watch?v=yM69uJBZpsA
- If you have any questions or issues, please reach out via  email. aliqorbanif@gmail.com




