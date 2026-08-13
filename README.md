# 💡 LDR-Based Automatic Street Light System

An IoT/Embedded Systems project built with **Arduino Uno** and a **Light Dependent Resistor (LDR)** to automate street light operations and minimize energy waste.

## 🌟 Overview
Traditional street lighting systems rely on manual operation or static timers, leading to significant energy wastage when lights remain ON during daylight hours. This project presents a simple, cost-effective, and smart solution: an automated lighting system that continuously monitors ambient light levels using an LDR sensor and dynamically controls street lamps via a relay/LED setup.

### 🎯 Key Features
* **Automatic Day/Night Detection:** Uses an LDR module to sense ambient brightness in real-time.
* **Energy Efficient:** Ensures lights remain OFF during daytime and turn ON only when threshold light levels drop below a set limit.
* **Adjustable Threshold:** Easily tweak sensor sensitivity directly in the Arduino code or via a potentiometer.
* **Low Cost & Plug-and-Play:** Built using readily available, budget-friendly electronic components.
* **Expandable Architecture:** Easily upgradable to include motion sensors (PIR), solar charging, or IoT monitoring (ESP8266/ESP32).

---

## 🛠️ Components Used
* **Microcontroller:** Arduino Uno R3
* **Sensor:** LDR (Light Dependent Resistor) Module / Photoresistor
* **Output:**  LED (for prototype demo)
* **Resistors:** 10kΩ and 220kΩ Resistors (for voltage divider circuit)
* **Power Supply:**  USB
* **Misc:** Breadboard & Jumper Wires

  ---

## 🔬 Working Principle & Physics Behind LDR
The system operates based on the photoconductive properties of a Light Dependent Resistor (LDR) and an Arduino voltage divider network.
🧪 Physics of the Photoresistor (LDR)
Photoconductive Semiconductor: An LDR is constructed using high-resistance semiconductor materials (such as Cadmium Sulfide, CdS).
Photoconductivity Principle: A photoresistor is a light-controlled variable resistor whose resistance decreases with increasing incident light intensity.
Electron Excitation: When incident light hitting the LDR exceeds a certain threshold frequency, absorbed photons give bound electrons enough energy to jump into the conduction band.
Charge Carriers & Resistance: The resulting free electrons (and their hole partners) conduct electricity, thereby significantly lowering resistance:
      In the Dark: A photoresistor exhibits high resistance, reaching up to a few Mega-ohms.
      In the Light: Resistance drops dramatically down to a few hundred ohms.
Device Characteristics: The resistance range and sensitivity of a photoresistor can substantially differ among dissimilar devices. Moreover, unique photoresistors may react substantially differently to photons within certain wavelength bands.
Application: Due to these properties, LDRs are widely applied in light-sensitive detector circuits and light automation systems.
