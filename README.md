# AUTOMATIC-STREET-LIGHT
Automatic Street Light System

 Project Overview

The **Automatic Street Light System** is an energy-efficient lighting solution that automatically controls street lights based on ambient light intensity. The system utilizes a **Light Dependent Resistor (LDR)** to detect environmental lighting conditions and operates the street light accordingly without manual intervention.

This project demonstrates a practical application of embedded systems in **smart energy management and automation**.


Objectives

* To design an automatic lighting system based on ambient light
* To reduce energy consumption and human effort
* To implement a cost-effective and reliable solution
* To demonstrate real-time sensing and control using a microcontroller



Hardware Components

* Arduino Uno / Nano
* LDR (Light Dependent Resistor)
* 10kΩ Resistor
* Relay Module (or transistor switch)
* LED / AC Lamp (Load)
* Power Supply


System Architecture

The system is based on a **sensor–controller–actuator model**:

* **Sensor:** LDR detects light intensity
* **Controller:** Arduino processes input signal
* **Actuator:** Relay switches the street light



 Working Principle

The LDR operates on the principle of **photoconductivity**, where its resistance varies inversely with light intensity:

* **Daytime (High light intensity):**
  LDR resistance decreases → Voltage increases → Light OFF

* **Nighttime (Low light intensity):**
  LDR resistance increases → Voltage decreases → Light ON

The Arduino continuously reads analog values from the LDR and compares them with a predefined threshold to control the relay.

System Workflow

1. LDR senses ambient light
2. Analog signal is sent to Arduino (A0 pin)
3. Arduino converts analog signal to digital value (0–1023)
4. Value is compared with threshold
5. Relay is triggered accordingly
6. Street light turns ON/OFF automatically


features
* Fully automatic operation
* Energy-efficient system
* Simple and low-cost implementation
* Reliable and scalable design
* Suitable for real-world applications


Applications

* Street lighting systems
* Highway lighting
* Garden and pathway lighting
* Smart city infrastructure
* Industrial outdoor lighting

 Future Enhancements

* Integration with IoT for remote monitoring and control
* Motion detection using PIR sensor for additional energy savings
* Solar-powered implementation
* Adaptive brightness control using PWM

