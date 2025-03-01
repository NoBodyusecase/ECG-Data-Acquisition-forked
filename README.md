# ECG Data Acquisition & Heart Rate Analysis System 🩺  
**Arduino-based system to simulate ECG waveforms, calculate BPM, and detect rhythm irregularities.**  
*(Developed for "Introduction to Medical Equipment - Task 01")*  

---

## 📝 Overview  
This project simulates ECG signal acquisition using an Arduino, OLED display, and a heart rate sensor (or potentiometer). It visualizes **normal/disease ECG waveforms**, calculates real-time heart rate (BPM), and evaluates rhythm regularity. Perfect for prototyping medical devices or learning biosignal processing!  

---

## 🌟 Features  
- **Simulated ECG Waveforms**: Switch between normal and arrhythmia (disease) patterns.  
- **Real-Time BPM Calculation**: Error percentage relative to a reference BPM (72).  
- **Interactive OLED Display**: Toggle graph inversion and disease mode with push buttons.  
- **Sensor Simulation**: Works with real sensors or Tinkercad potentiometers.  

---

## 🛠️ Components  
- Arduino Uno  
- SSD1306 OLED (128x64, I2C)  
- Heart Rate Sensor (or Potentiometer)  
- Push Buttons (x2)  
- Breadboard & Jumper Wires  

---

## 🔧 Setup  
1. **Wire the Circuit**:  
   - OLED: `SDA → A4`, `SCL → A5`, `VCC → 5V`, `GND → GND`  
   - Heart Rate Sensor: `OUT → A0`, `VCC → 5V`, `GND → GND`  
   - Buttons: `Pin 2` (Graph Inversion), `Pin 3` (Disease Mode) with pull-up resistors.  

2. **Upload Code**:  
   - Install `Adafruit_SSD1306` and `Adafruit_GFX` libraries.  
   - Upload `sketch_feb24b.ino` to Arduino.  

3. **Simulate in Tinkercad**:  
   - Replace the sensor with a potentiometer for testing.  

---

## 🎮 Usage  
- Press **Button 1** (Pin 2) to invert the ECG graph.  
- Press **Button 2** (Pin 3) to toggle between normal/disease ECG modes.  
- OLED shows BPM, error percentage, and prompts for sensor input.  

---

## 📊 Task Alignment  
This project fulfills **Task 01** requirements by:  
✅ Acquiring/simulating ECG data  
✅ Calculating heart rate (BPM) and error  
✅ Visualizing rhythm regularity (normal vs. disease)  
✅ Providing reasoning via error analysis  

---

## 📜 License  
Open-source under MIT License. Adapt and heal the world! ❤️  
