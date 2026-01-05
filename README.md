# digital-output-led
This repository contains a basic embedded systems demo that drives a single LED using a microcontroller’s digital I/O. Covers pin configuration, timing logic, and hardware setup for a clean, reproducible test circuit.

This repository documents a simple but foundational embedded‑systems project: controlling a single green LED using a digital I/O pin on the Elegoo R3 microcontroller. The goal of this project is not complexity, but learning — it serves as my first hands‑on experiment with C++ programming for microcontrollers and my second time creating a schematic in KiCad.

I’ll be expanding this project over time as I build confidence with hardware, firmware, and documentation workflows.

🔧 Project Overview
This project demonstrates:

Configuring a digital output pin on the Elegoo R3

Wiring an LED and current‑limiting resistor on a breadboard

Using jumper wires to connect the microcontroller to the circuit

Writing a simple C++ program to toggle the LED on and off at timed intervals

Creating a schematic in KiCad to document the circuit

Capturing a photo of the physical breadboard build for reference

Although the circuit is extremely simple, it forms the basis of almost every embedded system: reading and writing digital signals, understanding current flow, and verifying that your toolchain works end‑to‑end.

🧠 Why This Project Exists
This repository is intentionally small and focused. It is part of my journey to learn:

The basics of embedded C++

How to structure microcontroller projects

How to document hardware using KiCad

How to build clean, reproducible breadboard circuits

How to use GitHub to track engineering progress

This is my first time using C++ for microcontroller programming and my second time using KiCad, so the project is designed to be simple, repeatable, and educational.

Future versions will expand into more complex behaviours, sensors, and multi‑component circuits.

🛠️ Hardware Used
Elegoo R3 (Arduino‑compatible) microcontroller

Breadboard

Green LED

resistor (current limiting)

Male–male jumper wires

USB cable for programming

🔌 Circuit Description
The circuit consists of:

One digital I/O pin (e.g., D7) configured as an output

A jumper wire from the I/O pin to the resistor

The resistor connected to the anode of the LED

The LED’s cathode connected to GND

The Elegoo R3 powered via USB
