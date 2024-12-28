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
RT-Control-System/
├── backend/              # Backend server and API logic
│   ├── app.py            # Flask/Django backend
│   ├── requirements.txt  # Python dependencies
├── ui/                   # Frontend for screen display
│   ├── index.html        # UI design
│   ├── styles.css        # UI styling
│   └── app.js            # UI interactivity
├── hardware/             # Hardware-related code
│   ├── motor_control.py  # Motor control logic
│   ├── sensor_input.py   # Sensor integration
└── README.md             # Project documentation
