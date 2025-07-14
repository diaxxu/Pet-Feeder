# 🐾  Smart Cat Feeder 

An automatic pet feeder designed and built using **Fusion 360**, an **ESP32**, and a **servo motor**. The feeder is controlled remotely via the **Blynk IoT app**, allowing food to be dispensed from anywhere in the world over Wi-Fi.

---

## ✨ Features

- 🌍 **Remote Control** – Trigger feeding from anywhere using your phone
- ⚙️ **Servo-Driven Gate** – Opens/closes a rotating valve
- 📐 **Custom CAD Design** – Entire structure modeled in Fusion 360
- 🔌 **ESP32 Microcontroller** – Wi-Fi enabled brain of the system
- 🧪 **Minimal Hardware** – Clean and compact wiring on a single protoboard
- 🔋 **Low Power** – Servo activates only when feeding

---

## 🛠️ Technologies Used

- [ESP32](https://www.espressif.com/en/products/socs/esp32)
- [Blynk IoT Platform](https://blynk.io/)
- Servo Motor (e.g., SG90 or MG90S)
- [Arduino IDE](https://www.arduino.cc/en/software)
- [Fusion 360](https://www.autodesk.com/products/fusion-360)

---

## 🚧 Future Upgrades

- 📷 Wi-Fi camera integration for pet monitoring
- 🕒 Timer-based automatic feeding mode
- 📦 Load cell for food level detection
- 🐱 Telegram Bot or web-based UI

---

## 🔧 How It Works

1. ESP32 connects to your home Wi-Fi network
2. A button press on the Blynk mobile app sends a signal
3. The ESP32 receives the command and rotates the servo to open the gate
4. After 2 seconds, the gate closes again
5. Food drops out, cat is happy 🐈‍⬛




