# 8086 Microprocessor Central Unit Project

## Overview

This project focuses on designing a microsystem centered around the 8086 microprocessor. It includes various components such as memory modules, interfaces, input devices, output devices, and programming routines.

## Environment

The project was developed using Proteus 8.6 SP2 Professional.

## Components

- **8086 Microprocessor**: Acts as the central processing unit of the system.
- **EPROM Memory**: Utilizes 27C512 circuits to provide 128 KB of programmable read-only memory.
- **SRAM Memory**: Utilizes 62256 circuits to provide 64 KB of static random-access memory.
- **Serial Interface**: Incorporates the 8251 circuit, positioned in the 05A0H – 05A2H or 0DA0H – 0DA2H zone based on switch S1's position.
- **Parallel Interface**: Features the 8255 circuit, placed in the 0890H – 0896H or 0C90H – 0C96H zone, depending on switch S2's position.
- **Keypad**: A 16-contact input device for user interaction.
- **LEDs**: 18 light-emitting diodes for visual feedback and status indication.
- **7-Segment Display**: A module capable of displaying up to 10 hex characters simultaneously across 10 ranks.
- **LCD Module**: Consisting of two lines, each with 16 characters, with an interface chosen by the student.

## Programming

- All assembly language programs will be structured as subroutines.
- Programming routines will include:
  - Configuration and control of the 8251 and 8255 circuits.
  - Transmission and reception routines for characters via the serial interface.
  - Character transmission routines on the parallel interface.
  - Keypad scanning routine for user input.
  - LED on/off routine for controlling the LEDs.
  - Routine for displaying a hex character on a segment rank of the 7-segment display.

