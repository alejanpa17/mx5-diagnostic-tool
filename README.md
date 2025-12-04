# MX5 Diagnostic Tool 🚗 📱

> **Note:** This project is currently in the early **Proof of Concept** phase. It is a work in progress designed to validate wireless diagnostics for the Mazda MX-5 NA/NB.

## 📖 Overview

**MX5 Diagnostic Tool** is an open-source hardware and software solution designed to modernize diagnostics for the Mazda MX-5 (Miata) NA and NB generations.

Unlike modern OBD2 vehicles, early Miatas use a proprietary diagnostic protocol located in the engine bay. This tool acts as a wireless bridge, plugging directly into the **Engine Bay Diagnostic Box**, allowing users to read fault codes, stream live data, and perform active tests via a wireless interface (WiFi/Bluetooth).

## ⚡ Capabilities

This tool interfaces with the proprietary Mazda diagnostic protocol to provide the following functions:

### 🔍 Diagnostics
* **Scan for Fault Codes:** Reads and decodes current error pulses from the ECU for display on a phone.
* **View Previous Faults:** Accesses historical fault codes stored in memory.
* **Switches Test:** Validates the functionality of relays.

### 🛠️ Active Tests
* **Cooling Fan Test:** Manually triggers the cooling fan relay to verify circuit integrity.
* **Fuel Pump Test:** Manually activates the fuel pump to verify operation.

### 📈 Live Telemetry
* **Battery Voltage:** Real-time voltage monitoring.
* **Rev Counter:** Displays live RPM read directly from the tachometer signal.
* **Oxygen Sensor:** Monitors real-time feedback from the O2 sensor.

---

## ⚠️ Disclaimer

**Experimental Project:** This tool interacts directly with the vehicle's ECU. As a Proof of Concept, features are experimental. Use with caution.
