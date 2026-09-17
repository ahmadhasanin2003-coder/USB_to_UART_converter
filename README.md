# USB Type-C to UART Converter

A custom USB Type-C to UART interface designed using the **CP2102 USB-to-UART bridge IC**.

## Overview

This project is a USB Type-C based UART converter that can be used to provide serial communication between a computer and embedded systems.

The design includes:

- USB Type-C receptacle for USB connectivity
- CP2102 USB-to-UART bridge
- USB ESD protection
- USB Type-C CC resistors
- UART TX/RX status LEDs
- External UART pins for easy connection to a microcontroller
- Power filtering and decoupling capacitors

## Block Diagram

```text
Computer
   │
   │ USB Type-C
   ▼
USB Type-C Connector
   │
   │ USB D+ / D-
   ▼
CP2102 USB-to-UART
   │
   ├── TX
   ├── RX
   └── VBUS
        │
        ▼
   External UART Pins
