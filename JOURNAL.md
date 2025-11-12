| Title | Author | Description | Created_at |
|--------|----------------|------------------------------------------|------------|
| H818I | Kiya | A high-performance custom rocket with full avionics, airframe, and motor designed from scratch. | 2025-10-02 |

# Dev Log "H818I"

**Total Time (Hours): 42 Hours**

---

## Week 1 (10/02/2025) – 8 Hours  

**Days worked on:**  
Thursday – 2 hours<br>
Friday – 1 hour<br>
Saturday – 3 hours<br>
Sunday – 2 hours  

- Began detailed concept and mission planning  
- Created flight model and rough mass breakdown  
- Designed early sketches for motor and avionics housing  
- Selected materials: 6061 aluminum for the motor casing and 304 stainless steel for the nozzle  
- Simulated first flight profile (target: 6,000 ft at Mach 0.6)  
- Modeled nose cone, avionics bay, and recovery section in Fusion 360  

---

## Week 2 (10/09/2025) – 10 Hours  

**Days worked on:**  
Monday – 2 hours<br>
Tuesday – 2 hours<br>
Wednesday – 3 hours<br>
Thursday – 2 hours<br>
Friday – 1 hour  

- Designed and finalized motor geometry (38mm × 277mm, 385 N thrust)  
- Modeled grain holders and retention system  
- Started designing 4-layer avionics PCB (Teensy 4.1 + ESP32-S3)  
- Planned data flow and LoRa communication layout  
- Designed fin structure and servo mounts  
- Confirmed center of gravity and stability margin through simulations  

---

## Week 3 (10/16/2025) – 9 Hours  

**Days worked on:**  
Monday – 2 hours<br>
Tuesday – 1 hour<br>
Wednesday – 3 hours<br>
Thursday – 2 hours<br>
Friday – 1 hour  

- Finalized internal layout of avionics bay and wiring  
- Added four pyro channels and four servo outputs for deployment and control  
- Modeled outer airframe with correct tolerances for internal assemblies  
- Designed and tested 3D-printed mock sections for fit checks  
- Ran high-speed stress simulations on fins and airframe shell  

---

## Week 4 (10/23/2025) – 8 Hours  

**Days worked on:**  
Monday – 1 hour<br>
Tuesday – 2 hours<br>
Wednesday – 2 hours<br>
Thursday – 1 hour<br>
Friday – 2 hours  

- Began physical build process and sourced aluminum and stainless steel stock  
- Started 3D printing parts for structural components and avionics housing  
- Prototyped and tested PCB connections  
- Verified Teensy–ESP32 communication and telemetry output  
- Created wiring diagram for all sensors (IMU, barometer, magnetometer, GPS, accelerometer)  

---

## Week 5 (10/30/2025) – 7 Hours  

**Days worked on:**  
Monday – 1 hour<br>
Tuesday – 2 hours<br>
Wednesday – 1 hour<br>
Thursday – 2 hours<br>
Friday – 1 hour  

- Finished 3D-printed airframe components and motor housing  
- Assembled avionics PCB and verified sensor output through test data  
- Installed servos and wired pyro channels  
- Assembled final rocket structure and performed weight and balance checks  
- Began sanding, painting, and surface finishing  

---

# Launch Preparation  

- **Expected Altitude:** 6,000 ft (≈1,829 m)  
- **Expected Speed:** Mach 0.6 (≈204 m/s)  
- **Motor Thrust:** 385 N (custom 38mm × 277mm solid motor)  
- **Avionics:** Dual MCU (Teensy 4.1 + ESP32-S3) on 4-layer PCB  
- **Sensors:** IMU, barometer, magnetometer, GPS, accelerometer  
- **Competition:** FARS – Altitude and Speed Challenge  
- **Launch Target:** Mid-November 2025  
