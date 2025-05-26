# README.md
# RT Robot Control System 🤖

A modular Python-based control system for a multi-functional RT Robot using an ASUS Tinker Board and peripheral microcontrollers.

## 🚀 Features

- 4-wheel motor driver control
- Dual arm servo system
- Neck servo control
- Screen display and camera input
- Communication via Wi-Fi LoRa, RC, and Bluetooth
- SIM card and memory card functionality

## 🧠 Architecture

See `wiring_diagram.png` for a full hardware overview.

## 📁 File Structure

- `main-controller/` – Main control script
- `motor_driver.py`, `servo_driver.py` – Motor/servo control logic
- `camera_module.py` – Camera input processing
- `communication_manager.py` – Communication protocols
- `screen_display.py` – UI control on screen
- `serial_comms.py` – Serial communication layer
- `requirements.txt` – Python dependencies

## 📦 Setup

```bash
pip install -r requirements.txt
python3 main-controller/main.py
