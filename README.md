# Real-Time Driver Fatigue and Distraction Monitoring System

## Overview
An IoT-based real-time driver safety system developed using Raspberry Pi 4 and computer vision techniques to detect driver drowsiness, yawning, and distraction.

## Key Features
- Eye Aspect Ratio (EAR) based drowsiness detection
- Mouth Aspect Ratio (MAR) based yawning detection
- Driver authentication using facial recognition
- Two-stage alert system (Local + Cloud)
- Emergency call and live location sharing

## Tech Stack
- Python 3.11
- OpenCV, Dlib
- Raspberry Pi 4
- Twilio, Pushover
- RPi.GPIO, picamera2

## Team Project
Developed as part of the IoT Programming course at NIT Kurukshetra.

## How to Run
```bash
pip install -r requirements.txt
python code/main.py
