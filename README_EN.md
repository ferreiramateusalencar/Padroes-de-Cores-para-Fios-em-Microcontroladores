# Color Standards for Wires in Microcontrollers

This repository documents a suggested color standard for wires in microcontroller projects, facilitating organization and connection identification.

📖 Read in [Português](README.md).

## 📦 Color Structure

### Power and Energy
- **VCC (Voltage Common Collector - +5V, +3.3V):** 🔴 Red or 🟠 Orange
- **GND (Ground):** ⚫ Black or 🟤 Brown

### Data and Communication
- **GPIO (General Purpose Input/Output - Digital):** ⚪ White, ⚪ Gray, or 🔵 Light Blue
- **I²C (Inter-Integrated Circuit):**
  - **SDA (Serial Data Line):** 🔵 Blue or 🟢 Light Green
  - **SCL (Serial Clock Line):** 🟡 Yellow or 🟠 Orange
- **UART (Universal Asynchronous Receiver-Transmitter):**
  - **RX (Receive):** 🟢 Green
  - **TX (Transmit):** 🟡 Yellow
- **SPI (Serial Peripheral Interface):**
  - **MISO (Master In Slave Out):** 🟣 Purple
  - **MOSI (Master Out Slave In):** 🟠 Orange
  - **SCK (Serial Clock):** 🟡 Yellow
  - **CS/SS (Chip Select/Slave Select):** ⚪ Gray or 🔵 Dark Blue

### Other Functions
- **PWM (Pulse Width Modulation):** 🔵 Blue or 🟣 Purple
- **Switches or Control:** ⚪ White or ⚪ Gray

## 🎯 Best Practices
- **Consistency:** Use the same colors for the same functions throughout the project.
- **Documentation:** Label wires and log connections.
- **Safety:** Ensure colors correctly indicate polarity and signals.

## 📥 Contributions
Feel free to open a pull request or issue for suggestions and improvements.

## 📜 License
This project is licensed under the MIT license. See the [LICENSE](https://github.com/ferreiramateusalencar/Padroes-de-Cores-para-Fios-em-Microcontroladores/blob/main/LICENSE) file for details.

---

🎯 **Organize your project efficiently and avoid confusion!**
