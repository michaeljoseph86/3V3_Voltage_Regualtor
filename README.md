# 3V3 lDO Regulator

**AMS1117** 3V3 Step Down Power Supply Module

![Tux, the Linux mascot](https://i.imgur.com/hN47aSC.png)

**Current repository folder structure:**

<p>Calibration: Raw sensor data useful for checking calibration algorithms (e.g. accelerometer bias, scale factor, etc.).
Communication: UAVLink data protocol for reliably packing and transferring data and commands between the aircraft and a further device (e.g. base station). This could be via telemetry or direct serial links.
Control: Algorithms for dynamic control of the aircraft (e.g. PI, state feedback, etc.).
Data: Collection of various datasets that may be useful for offline testing (e.g. raw IMU data).
Debug Software: Tools for interfacing with the hardware (e.g. to read navigation data).
Documentation: Preliminary documents to detail aspects of the flight control system.
Filtering: FIR and IIR filter implementations, as well as FIR filter design tool.
Firmware: The core flight control firmware running on the STM32 microcontrollers.
Flight Simulator: 6-DOF and 3-DOF fixed-wing flight simulators developed in Unity. Very useful for testing control logic and algorithms. Requires dynamic model of aircraft.
GPS: NMEA sentence parser, as well as raw GPS data for testing.
Ground Control: Basestations written in C# to send commands to aircraft and receive data via telemetry. Includes moving map, live plots, etc.
Hardware: HADES flight control board design files (schematic, layout, assembly). Hardware consists of sensors, microcontrollers, power electronics, etc. This custom hardware is where the firmware runs on.
State Estimation: Kalman filters (various types: quaternion, Euler, different states estimated) designed in Matlab and exported to C for estimation of states required for feedback control (e.g. attitude, position, etc.).
Tests: Miscallaneous tests go here. For instance, device driver testing, communication protocol tests, etc.</p>

<p>Note: Most subfolders include an additional README that further describes its contents.</p>

<p>Disclaimer: No guarantees are made regarding accuracy and correctness of schematic symbols, footprints, and 3D models. Use at your own risk.</p>
