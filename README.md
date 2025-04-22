# 🤖 GCBot – Gesture-Controlled Bot

GCBot is a gesture-controlled robot powered by an **ESP32** and a **Python-based gesture detection system** using MediaPipe and OpenCV.  
This project uses **PlatformIO** for embedded development and is compatible with **Visual Studio Code**.

---

## 📁 Project Structure
``` 
GCBot/
├── include/            # Header files for the ESP32 firmware
├── lib/                # Custom libraries used in the project
├── python/             # Python scripts for gesture detection using MediaPipe and OpenCV
├── src/                # Main source code for the ESP32 firmware
├── test/               # Unit tests (if applicable)
├── .vscode/            # Recommended VS Code settings and extensions
├── .gitignore          # Files and directories ignored by Git
├── platformio.ini      # PlatformIO configuration file
└── README.md           # Project documentation
```

---

## 🚀 Getting Started

### 🧱 1. Clone the Repository

```bash
git clone https://github.com/WorldConqueror5623/GCBot.git
cd GCBot
```

### 🛠️ Requirements
#### Hardware:

- ESP32 development board

- USB cable for programming

- (Optional) LEDs, motors, or actuators for testing

- Breadboard and jumper wires

#### Software:

- Visual Studio Code + PlatformIO extension

- Python 3.8+

- OpenCV

- MediaPipe

## ⚙️ Installation
### 2. ESP32 Firmware
- Open the project in Visual Studio Code.

- Install the PlatformIO extension if you haven't already.

- Configure your ESP32 board in platformio.ini if needed.

- Connect your ESP32 via USB.

- Build and upload the firmware:

  ```bash
  pio run --target upload
  ```
### 3. Python Gesture Detection
- Navigate to the Python scripts folder:

  ```bash
  cd python
  ```
- Run the gesture detection script:

  ```bash
  python gesture_control.py
  ```


