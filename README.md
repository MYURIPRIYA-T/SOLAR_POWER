# 🌞 Smart Solar System IoT

This repository contains the firmware and hardware design of a **Smart Solar System** built using the **ESP32 microcontroller**. The system includes sun tracking, automatic cooling, and power management features with the scope to integrate **IoT-based monitoring** in the future.

---

## 🚀 Project Features

### 🌅 Sun Tracking
- **LDR sensors** to detect sun direction.
- **Servo motor** to rotate the solar panel.
- **Limit switches** to define rotation boundaries.

### 💧 Automatic Solar Panel Cooling
- **Motor pump** controlled by **relay**.
- Activates based on solar panel temperature or manual trigger.
  
### ⚡ Power Supply & Control
- **LM2596 buck converter**: Steps down 12V to 5V.
- **L298D Motor Driver**: Controls a geared DC motor for mechanical movement.

### 📡 Future Scope
- **IoT Monitoring via WiFi** using ESP32.
- Cloud-based data logging (e.g., Firebase, MQTT, Blynk).

---

## 🧰 Hardware Used

| Component               | Purpose                              |
|------------------------|--------------------------------------|
| ESP32                  | Main microcontroller                 |
| Servo Motor            | Solar panel angle rotation           |
| LDR Sensors            | Detect sunlight direction            |
| Limit Switches         | Restrict servo rotation boundaries   |
| DC Motor + L298D       | Manual rotation via gear system      |
| Relay Module           | Control motor pump for cooling       |
| LM2596 Buck Converter  | Step-down 12V to 5V                  |
| Solar Panel            | Power generation                     |

---

## 🗂 Folder Structure
/firmware/ └── main.ino (ESP32 Code) └── modules/

/hardware/ └── schematics/ └── PCB/

/docs/ └── diagrams/ └── images/

---

> This is an open-source project developed for educational and research purposes. Feel free to fork and improve it!


