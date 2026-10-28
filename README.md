# AI-Rescue-Drone-HSC
# AI-Based Drone for Post-Disaster Survivor Detection Using Micro-Doppler Radar & Thermal Sensor

An autonomous AI-powered quadcopter system designed to detect trapped survivors under debris and low-visibility conditions using sensor fusion (Micro-Doppler Radar + Thermal Infrared Sensing).

## 📌 Features
- **Micro-Doppler Radar:** Detects minute vital body movements (breathing and heartbeat) through rubble and debris.
- **Thermal Infrared Sensor:** Captures human body heat in open or partially visible areas.
- **AI Sensor Fusion:** Onboard AI (YOLO / TensorFlow) processes dual-sensor data to minimize false alarms.
- **Real-Time GPS Broadcasting:** Instantly transmits accurate coordinates of survivors to rescue monitoring teams.

## 🛠️ Environment Setup & Installation

### Prerequisites
- Python 3.9+
- OpenCV (`pip install opencv-python`)
- TensorFlow / PyTorch
- QGroundControl / Mission Planner

### Quick Start
```bash
# Clone the repository
git clone [https://github.com/sec25ei090-beep/AI-Rescue-Drone-HSC.git](https://github.com/sec25ei090-beep/AI-Rescue-Drone-HSC.git)
cd AI-Rescue-Drone-HSC

# Install required dependencies
pip install -r requirementsGPS_MODULE_PORT=/dev/ttyUSB0
RADAR_BAUD_RATE=115200
THERMAL_SENSOR_I2C_ADDR=0x33
RESCUE_APP_SERVER_URL=[https://api.rescuedeploy.org/location](https://api.rescuedeploy.org/location).txt
