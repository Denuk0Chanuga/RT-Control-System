# RT-Control-System

RT (Robotic Technician) robot control system designed for robotics projects. This system is built to manage RT's hardware and software components efficiently, enabling smooth interaction and functionality.

## Features
- Full hardware control via the **Asus Tinker Board**.
- Interactive **Touch Screen Interface** for manual and automatic control.
- Real-time data visualization (e.g., sensor readings, task status).
- Integrated motor control, sensor input, and GPIO management.
- Modular codebase for easy maintenance and scalability.

## Directory Structure
```plaintext
rt-robot-control-system/
├── main-controller/               # Tinker Board code
│   ├── motor_control/
│   │   └── motor_driver.py
│   ├── servo_control/
│   │   └── servo_driver.py
│   ├── communication/
│   │   └── communication_manager.py
│   ├── main.py
├── sub-system/
│   ├── camera_module.py           # For Pi Zero or Arduino with camera
│   ├── screen_display.py          # Head screen display code
│   └── serial_comms.py
├── hardware/
│   ├── wiring_diagram.png
│   └── parts_list.md
├── README.md
└── requirements.txt

