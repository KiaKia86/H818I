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

- Started to plan the rocket
- Created an open rocket simulation to predict how fast the rocket would go
- Made sketches and a model (Very rough) to get an idea of what the rocket would look like 
- Researched materials for motor (304 steel and 6061 aluminum)
- Modeled nose cone and body tube in Fusion 360

**Open Rocket Simulation**
<img width="1917" height="1037" alt="image" src="https://github.com/user-attachments/assets/3cc2f56d-c38b-4596-a34e-4fe9b2cf2af6" />
**Body Tube**
<img width="1511" height="897" alt="image" src="https://github.com/user-attachments/assets/f6803131-27e9-4f41-b6ac-8e7e35555158" />
**Nose Cone**
<img width="1507" height="977" alt="image" src="https://github.com/user-attachments/assets/a91634b8-e3ef-4782-9726-66f7fbfa438f" />

---

## Week 2 (10/09/2025) – 10 Hours  

**Days worked on:**  
Monday – 2 hours<br>
Tuesday – 2 hours<br>
Wednesday – 3 hours<br>
Thursday – 2 hours<br>
Friday – 1 hour  

- Designed the finalized the motor size (38mm x 277mm, with 385N of thrust) 
- Modeled grain holders  
- Started designing 4-layer avionics PCB  
- Designed fins based on the openrocket simulation and data  
- Confirmed center of gravity and stability margin through simulations

**Full Motor Design**
<img width="1513" height="899" alt="image" src="https://github.com/user-attachments/assets/76187186-b956-41a6-b797-59edf7cd36af" />
**Motor Cross Section**
<img width="1504" height="971" alt="image" src="https://github.com/user-attachments/assets/cdd22f91-3df7-423c-865b-20e4224f3c21" />
**Propellant Case Mold**
<img width="1520" height="970" alt="image" src="https://github.com/user-attachments/assets/0ab84a35-7681-4e43-9b88-b9381ef92c39" />
**Fins**
<img width="1509" height="896" alt="image" src="https://github.com/user-attachments/assets/1dd4c108-24bf-44b3-ad5a-326ab566a2cf" />

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
