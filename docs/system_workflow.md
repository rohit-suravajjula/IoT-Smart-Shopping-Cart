# ⚙️ System Workflow

## Overview

The Smart Shopping Cart automates product identification and billing using RFID technology and a NodeMCU (ESP8266). The workflow below describes how data moves through the system from scanning a product to displaying the updated bill.

---

## Workflow

### Step 1 — Product Scanning

A customer places an RFID-tagged product into the shopping cart. The EM-18 RFID reader detects the RFID tag and reads its unique ID.

---

### Step 2 — Data Processing

The RFID tag information is sent to the NodeMCU (ESP8266), which identifies the corresponding product and retrieves its details.

---

### Step 3 — Bill Calculation

The NodeMCU updates the running total by adding the newly scanned product to the cart.

---

### Step 4 — Display Update

The product name and updated total amount are displayed on the 16×2 LCD mounted on the shopping cart.

---

### Step 5 — Web Interface

The NodeMCU hosts a simple local web page over Wi-Fi, allowing the current shopping cart details and bill to be viewed from another device connected to the same network.

---

### Step 6 — Item Removal

If a customer wishes to remove an item, the push button and RFID scanning process are used to update the bill accordingly.

---

## Outcome

The system demonstrates how embedded systems, RFID technology, and IoT connectivity can work together to automate the shopping and billing process.
