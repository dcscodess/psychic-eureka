# psychic-eureka


# IntelliCargo – AIoT-Based Transport Stress Monitoring System

A real-time TinyML solution for detecting shocks, vibrations, and tilts in cargo using ESP32 and Edge Impulse.

##  Features
- Motion classification (Drop, Tilt, Vibration, Idle)
- Edge AI inference on ESP32-C6
- Data collected and trained via Edge Impulse
- Optional MQTT/HTTP alert integration

##  Technologies
- ESP32-C6-DEVKITC-1-N8
- MPU6050 Accelerometer & Gyro
- TinyML model trained via Edge Impulse
- Arduino/PlatformIO firmware
- Optional dashboard: ThingsBoard or Node-RED

##  How It Works
1. Collect motion data → Edge Impulse
2. Train model → Deploy to ESP32
3. Detect anomalies in real time
4. Alert locally or send to cloud

##  Folders
- `firmware/` → Code + model integration
- `docs/` → Setup guides & wiring
- `assets/` → Test videos, photos


