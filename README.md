# Autonomous Medical Delivery Robot - Line Follower System

## 📌 Project Overview
**A smart healthcare solution** using an 8051 microcontroller-based line-following robot to automate medicine delivery in hospitals. Equipped with IR sensors and L293D motor drivers, this robot navigates pre-defined paths to transport medications between patient beds, reducing staff workload and improving efficiency.

[![Watch Demo]([https://img.youtube.com/vi/YOUTUBE_VIDEO_ID/0.jpg)](https://youtu.be/YOUTUBE_VIDEO_ID](https://drive.google.com/file/d/1A4tFDbwrXCDe3M9qZGm4LLql-2b2k7LU/view?usp=sharing))  

## 🛠️ Key Components
- **8051 Microcontroller** - Brain of the system
- **IR Sensor Array** (2x LM358 comparators) - Path detection
- **L293D Motor Driver** - Controls 4 DC motors
- **Acrylic Chassis** - With 65mm wheels
- **Medicine Compartment**

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

## 🚀 Future Enhancements

- Add RFID for patient identification

- Integrate webcam for remote monitoring

- Implement obstacle avoidance sensors

- Solar charging capability

## 🔧 Technical Implementation
```c
// Sample Code Snippet (Direction Control Logic)
if(left_sensor==0 && right_sensor==0) {
  move_forward();  // Both sensors on white surface
} 
else if(right_sensor==1) {
  turn_right();    // Right sensor detects line
}
