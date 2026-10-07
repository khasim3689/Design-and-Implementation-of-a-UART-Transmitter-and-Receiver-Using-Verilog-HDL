Design-and-Implementation-of-a-UART-Transmitter-and-Receiver-Using-Verilog-HDL

📌 Project Overview

This project presents the design and simulation of a UART (Universal Asynchronous Receiver/Transmitter) Transmitter and Receiver using Verilog HDL and Xilinx Vivado. The system is designed to transmit and receive 8-bit data through serial communication using a defined UART data frame.

The project demonstrates the internal working of UART communication and the interaction between the UART Transmitter, UART Receiver, Baud Rate Generator, Shift Registers, Control Logic, and Serial Data Line.

🎯 Main Objective

The main objective of this project is to understand and implement a basic UART communication system using Verilog HDL and verify data transmission and reception through RTL simulation and waveform analysis in Vivado.

🏗️ UART Architecture

The UART system consists of the following major blocks:

UART Transmitter
UART Receiver
Baud Rate Generator
Transmit Shift Register
Receive Shift Register
Control Logic
Start Bit Detection
Stop Bit Detection
Serial Data Line
Testbench

⚙️ Working Principle

The UART system operates through the following sequence:

Parallel Data → Transmitter → Serial Data → Receiver → Parallel Data

Transmit: The UART Transmitter accepts 8-bit parallel data and converts it into serial data.

Start Bit: A logic 0 start bit indicates the beginning of UART transmission.

Data Transmission: The 8-bit data is transmitted serially, starting from the Least Significant Bit (LSB).

Stop Bit: A logic 1 stop bit indicates the end of the UART data frame.

Receive: The UART Receiver detects the start bit, samples the incoming serial data, and reconstructs the original 8-bit parallel data.

Verification: The received data is compared with the transmitted data using the testbench and Vivado waveform simulation.
