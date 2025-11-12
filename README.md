# *H818I*

### A high-performance custom rocket designed entirely from scratch, featuring a 4-layer avionics PCB, custom airframe, and custom solid motor. The rocket is expected to reach **6,000 ft (≈1,829 m)** at **Mach 0.6**, powered by a **385 N thrust** motor.

### The airframe is constructed from lightweight composite sections reinforced with fiberglass cloth and resin. The rocket includes four pyro channels and four servo channels, offering flexibility for multiple deployment and control configurations.

### The avionics system is built on a **4-layer PCB** integrating two microcontrollers — a **Teensy 4.1** and an **ESP32-S3** — working together to process flight data and transmit telemetry via **LoRa** to the ground station. The board includes multiple sensors to track acceleration, rotation, altitude, and GPS position.

---

# Bill of Materials (BOM)

| **Category** | **Item** | **Details** | **Est. Price** | **Purchase Link** |
|--------------|-----------|-------------|----------------|--------------------|
| Mechanical   |           |             |                |                    |
| Structure    |           |             |                |                    |
| Electronics  |           |             |                |                    |
| Recovery     |           |             |                |                    |
| Propulsion   |           |             |                |                    |
| Software     |           |             |                |                    |

---

### PCB Overview

The **4-layer PCB** serves as the core of the H818I flight computer.  
It integrates:
- **Teensy 4.1** (primary sensor and control processor)  
- **ESP32-S3** (telemetry and communication)  
- **LoRa radio module** for long-range ground communication  
- Multiple onboard sensors: **IMU**, **barometer**, **magnetometer**, **GPS**, and **accelerometer**  
- **Four pyro channels** and **four servo outputs** for deployment and active control  

The avionics system is designed for flexibility, allowing reuse across future rocket designs.

---

### Why Did I Make This Rocket?

I’ve always wanted to design something that merges mechanical engineering, electronics, and aerospace in one project — and this is it. H818I represents months of design, simulation, and testing, combining everything I’ve learned about flight dynamics, propulsion, and control into a single launch-ready rocket.

---

# Physical Build

