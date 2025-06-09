# Autonomous Medical Delivery Robot - Line Follower System

## 📌 Project Overview
**A smart healthcare solution** using an 8051 microcontroller-based line-following robot to automate medicine delivery in hospitals. Equipped with IR sensors and L293D motor drivers, this robot navigates pre-defined paths to transport medications between patient beds, reducing staff workload and improving efficiency.

[Watch Demo](https://drive.google.com/file/d/1A4tFDbwrXCDe3M9qZGm4LLql-2b2k7LU/view?usp=sharing)  

## 🛠️ Key Components
- **8051 Microcontroller** - Brain of the system
- **IR Sensor Array** (2x LM358 comparators) - Path detection
- **L293D Motor Driver** - Controls 4 DC motors
- **Acrylic Chassis** - With 65mm wheels
- **Medicine Box with multiple compartments**
- **12V DC Power Supply**

## Software Used

- **Keil µVision**: Embedded C programming and simulation
- **EasyEDA**: Circuit design and PCB layout
- **Embedded C**: Microcontroller programming

## 🏥 Healthcare Applications

- Automated medicine delivery to patient beds

- 24/7 operation without human intervention

- Cost-effective alternative to manual delivery

- Reduces infection risks by minimizing contact

## 📊 Performance Metrics

- Parameter	Specification

- Path Accuracy	- 92% on sharp turns

- Payload Capacity - 500g medicines

- Operating Speed	- 0.3 m/s (adjustable)

- Battery Life	- 4 hours continuous use

## How It Works

1. **Sensors**: IR sensors detect the black line on a white surface.
2. **Comparators**: Convert analog sensor signals into digital for microcontroller input.
3. **Microcontroller**: Processes sensor input and controls the motors.
4. **Motor Driver**: Drives the motors based on microcontroller instructions.
5. **Movement**: Robot navigates the hospital floor delivering medications.

## Results

- The prototype functions as expected in lab conditions.
- Performance is reliable for basic path-following and stopping tasks.
- Improvements can be made with additional sensors for sharper turns and better path detection.
