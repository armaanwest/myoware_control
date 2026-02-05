# MyoWare Signal Acquisition (EMG Control)

This project implements EMG signal acquisition using the MyoWare 2.0 muscle sensor, an Arduino microcontroller, and TRS breakout wiring for prosthetic control development.

The goal of this project is to capture muscle activation signals, process them through Arduino, and prepare the signal pipeline for controlling DC motors in a prosthetic hand.

---

## Overview

This project is part of ongoing biomedical and electrical engineering work focused on EMG-based prosthetic control systems.

Signal flow:

Muscle → MyoWare Sensor → AUX Cord → TRS Breakout → Arduino → Computer

The Arduino reads analog EMG signals and outputs processed values for monitoring, debugging, and future control algorithms.

---

## Hardware Used

- MyoWare 2.0 Muscle Sensor
- Arduino Uno R3
- TRS Breakout
- DC Motors (prosthetic hand)
- Aux/TRS cable
- Breadboard + wiring

---

## Software / Tools

- Arduino IDE
- C/C++ (Arduino)
- Serial Monitor for signal visualization

---

## Features

- EMG signal acquisition
- Analog signal reading from MyoWare
- Real-time serial output
- Foundation for prosthetic motor control

---
