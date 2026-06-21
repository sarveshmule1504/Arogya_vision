# Bill of Materials (BOM)

This document lists all the components required to build the Arogya Vision project.

---

## Hardware Components

| Component               | Description                                      | Quantity |
|-------------------------|--------------------------------------------------|----------|
| **ESP32 Microcontroller** | Microcontroller for BP Monitor and Vitals       | 2        |
| **BP Monitor Device**    | Compatible with ESP32 (UART communication)      | 1        |
| **Temperature Sensor**   | Example: MLX90614 or DS18B20                    | 1        |
| **Pulse Oximeter Sensor**| Example: MAX30102 or MAX30100                   | 1        |
| **5V USB Power Adapter** | Power supply for ESP32                          | 2        |
| **USB Cables**           | Micro-USB or Type-C depending on ESP32          | 2        |
| **Raspberry Pi**         | For running the Streamlit app                   | 1        |
| **Touchscreen Display**  | Optional 7-inch display for Raspberry Pi        | 1        |
| **Cables and Connectors**| Jumper wires, Dupont connectors                 | Various  |
| **Enclosure**            | Custom-designed case for housing components     | 1        |
| **LED Indicators**       | Optional for status indication                  | Various  |
| **Push Buttons**         | Optional for manual control                     | Various  |

---

## Software Requirements

| Software               | Description                                      |
|------------------------|--------------------------------------------------|
| **Arduino IDE**        | For programming ESP32                           |
| **Python 3.x**         | For running the Streamlit app and test scripts  |
| **Streamlit**          | For the user interface                          |
| **Google Cloud TTS API**| For voice guidance                              |
| **ArduinoJson**        | For ESP32 JSON handling                         |
| **Python Libraries**   | `streamlit`, `pyserial`, `google-cloud-texttospeech`, etc. |

---

## Notes
- Ensure all components are compatible with each other.
- Use high-quality materials for durability and reliability.
- Regularly calibrate sensors for accurate readings.

---

**Status:** Ready for procurement and assembly.