
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

Setup Instructions

Prerequisites

Hardware: Asus Tinker Board, Touch Display, Sensors, Motors.

Software: Debian-based OS, Python 3.8+, Node.js for UI development.


Installation

1. Clone the repository:

git clone https://github.com/your-username/RT-Control-System.git


2. Navigate to the backend directory and install dependencies:

cd RT-Control-System/backend
pip install -r requirements.txt


3. Set up the frontend:

cd ../ui
npm install



Running the Project

1. Start the backend server:

python app.py


2. Open the UI in a browser or on the touch screen:

npm start



Contribution

Contributions are welcome! Please follow these steps:

1. Fork this repository.


2. Create a branch: git checkout -b feature-name.


3. Commit your changes: git commit -m "Added a feature".


4. Push to the branch: git push origin feature-name.


5. Submit a pull request.



License

This project is licensed under the MIT License.

Acknowledgments

Built using Asus Tinker Board for robotics integration.

NASA's "First Woman" comic inspired the RT robot concept.

Open-source libraries for hardware and UI development.



---

For any questions or suggestions, please contact:
Email: your-email@example.com
GitHub: your-username

මෙය ඔබගේ ව්‍යාපෘතියට අනුව අභිරුචිගත කරන්න. අමතර සැකසීම් අවශ්‍ය නම් කියන්න!

