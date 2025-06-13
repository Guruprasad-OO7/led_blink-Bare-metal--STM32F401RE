STM32F4 SysTick LED Blink (Bare-Metal)

This project demonstrates how to blink an LED connected to PA5 on an STM32F401RE microcontroller using the SysTick timer for millisecond delays. It is a minimal bare-metal C project, without using HAL or CMSIS abstraction layers — only direct register access.

🚀 Project Overview

- Microcontroller: STM32F4 series (e.g., STM32F401RE, STM32F103C8T6)
- Development Tool: STM32CubeIDE
- Programming Language: C
- Clock Speed: 16 MHz (assumed for SysTick delay)
- Pin Used: GPIOA Pin 5 (PA5) — commonly connected to onboard LED (like on Nucleo boards)

 🧠 What It Does

- Configures PA5 as output
- Initializes the SysTick timer to generate 1 ms delay intervals
- Toggles PA5 every 3 seconds using `delay_ms()` function


