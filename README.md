# Ramp Regulation with AI-Enabled Traffic Camera


## Overview

This project implements an Automatic Ramp Regulation system targeting ramp traffic congestion. By leveraging advanced video processing techniques, the system analyzes live freeway traffic conditions at ramp entry points, estimates congestion levels, and dynamically regulates traffic flow via a traffic light mechanism.

## Key Features

- **AI-Powered Video Analytics:** Detects, tracks, and estimates the speed of vehicles using OpenCV and custom logic.
- **Automatic Ramp Metering:** Dynamically adjusts traffic light timing based on real-time traffic flow and density.
- **Simple, Stand-Alone Deployment:** Requires only a single camera. No cloud dependency. Works offline in edge environments.
- **Reliable under all conditions:** Supports standard 3-lane roads, low-light/nighttime operation, and adverse weather conditions.

## Tech Stack

| Tool/Language | Role |
|---------------|------|
| Python        | Core logic, AI processing, traffic analytics |
| OpenCV        | Frame analysis, vehicle tracking |
| YOLO          | Deep learning-based vehicle detection |
| Arduino IDE   | Microcontroller integration for controlling traffic light/gate |
| PTV VISSIM    | Traffic simulation during development/testing |

## Development Environment

- OS: Windows 10 (21H2)
- Simulation: VISSIM for validation before real-world application

## System Architecture

<div align="center">
  <img src="https://i.imgur.com/CsnjOjn.png" alt="System Architecture" />
</div>

## Real-Time Verification
<div align="center">

#### No Traffic

  <img src="https://i.imgur.com/a1s4M1I.png" alt="No Traffic State" />
</div>
<div align="center">

#### Heavy Traffic

  <img src="https://i.imgur.com/DGg9FNW.png" alt="Heavy Traffic State" />
</div>

## Running the Project

1. Download the project files from Google Drive and extract them:
   After downloading, extract the contents of the downloaded zip file to your desired location on your local machine.

2. Navigate to the project directory:

   ```bash
   cd automatic-ramp-regulation-system
   ```

3. Run the `main.py` file:

   ```bash
   python main.py
   ```

## File Descriptions

- `main.py`: Main script to run the GUI and control the system.
- `Congestion_Estimation.py`: Module for estimating congestion levels.
- `Video_Processing.py`: Module for processing video input.
- `Ramp_Regulater.py`: Module for regulating traffic on the ramp.
- `Network_Handler.py`: Module for handling network communication with the traffic light system.
---

**Yousef Aldahash**  
Computer Engineer  
[dahash.yousef@gmail.com](mailto:dahash.yousef@gmail.com)
