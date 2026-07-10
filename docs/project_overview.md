# 📖 Project Overview

## Objective

The objective of this project was to design and develop an IoT-based Smart Shopping Cart that simplifies the billing process in retail stores. By integrating RFID technology with a NodeMCU (ESP8266), the system automatically identifies products, maintains a running bill, and reduces the need for manual barcode scanning at checkout.

---

## Problem Statement

Traditional billing systems require every product to be scanned individually at the billing counter, which increases waiting time during peak hours. The project aims to demonstrate how RFID and IoT technologies can be combined to automate product identification and improve the shopping experience.

---

## Proposed Solution

The system uses RFID tags attached to products and an EM-18 RFID reader mounted on the shopping cart. Whenever a tagged product is placed into the cart, the NodeMCU receives the RFID data, identifies the product, updates the running total, and displays the information on a 16×2 LCD.

Since the NodeMCU provides Wi-Fi connectivity, it also hosts a simple local web page where the current cart details and bill can be viewed from another device connected to the same network.

---

## System Components

### Hardware

- NodeMCU (ESP8266)
- EM-18 RFID Reader
- RFID Tags
- 16×2 LCD Display
- I2C LCD Module
- Push Button
- Buzzer
- LED Indicators
- Breadboard and Jumper Wires

### Software

- Arduino IDE
- Embedded C / Arduino
- ESP8266 Wi-Fi Libraries
- HTML (Embedded Web Interface)

---

## Outcome

The project successfully demonstrated a working prototype of an IoT-enabled smart shopping cart capable of identifying RFID-tagged products, maintaining a running bill, displaying purchase information on an LCD, and serving billing information through a local web interface.

This project provided practical experience in embedded systems, IoT development, RFID interfacing, hardware integration, and microcontroller programming.
