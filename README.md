# Arduino Project 7 – BuzzPen Prototype Alpha 🦯🔊  

## 📖 Product Story  
Mobility is one of the biggest challenges faced by blind and visually impaired people. Traditional tools like the **white cane** are effective but limited — they only detect obstacles on the ground within a short range. High-tech mobility aids exist, but they are often **too expensive, bulky, or inaccessible** to those who need them most.  

**BuzzPen** was created as a low-cost, portable **assistive mobility tool**.  
Instead of replacing the white cane, BuzzPen is designed to **complement it** by providing **early feedback when obstacles are nearby**.  

In this first version (“Prototype Alpha”), I used an Arduino and a **buzzer** to test the concept. The device emits a sound that increases in frequency when objects are detected closer, alerting the user in real time. Future versions would use a **vibration motor** for discreet, tactile feedback.  

## 🛠️ Design Concept  
- **Ultrasonic sensor (HC-SR04)**: measures distance to obstacles.  
- **Arduino**: processes signals and controls feedback.  
- **Buzzer**: provides auditory cues — beeps faster as obstacles get closer.  
- **LED**: lights up as an additional signal (useful for testing and demos).  
- **Potentiometer**: adjusts the detection range, allowing the device to be **calibrated to different environments** (indoors vs outdoors, crowded spaces, etc).  

## 🎯 Goals of the Prototype  
- Test whether **low-cost sensors + feedback loops** can provide useful obstacle awareness.  
- Allow **adjustable sensitivity** using a potentiometer.  
- Explore how **dual feedback (sound + light)** works before moving to vibration feedback in later versions.  
- Establish a proof-of-concept for a **compact, pen-sized mobility tool**.  

## 🔌 Components Used  
- Arduino Board  
- HC-SR04 Ultrasonic Sensor  
- Buzzer  
- LED + 220Ω resistor  
- 10kΩ Potentiometer  
- Breadboard + jumper wires

## ⚡ Circuit Setup

<img width="1422" height="515" alt="the buzz pen (2)" src="https://github.com/user-attachments/assets/8c50c084-b555-4ed7-8470-01d1060a4153" />


