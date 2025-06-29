# JOURNAL-PAPER
# 🚨 PRANATRANA – Smart Bridge Weight Monitoring System

A smart embedded solution for detecting and preventing bridge collapses due to overloading in tourist zones and sensitive areas.

---

## 📘 Overview

**PRANATRANA** is a hardware-based intelligent bridge safety system designed using Arduino Uno and load cell sensors. This project was developed as both a mini project and research publication to address real-world structural failures caused by overweight conditions.

> 📄 The system actively monitors the weight on a bridge and triggers an alert if the load exceeds its safety limit. It prevents accidents and infrastructure damage by proactively managing load limits.

---

## 🔬 Journal Publication

- **📑 Title:** PRANATRANA – Bridge Overload Monitoring System  
- **🧑‍🤝‍🧑 Authors:**  
  - Sk. Karishma  
  - P. Vijayalaxmi  
  - Praneeth  
  - Mahima  
  - Rudhira  
- **🏫 Affiliation:** CMR College of Engineering & Technology, Hyderabad 

---

## 🔧 Project Hardware Setup

### Components Used:
- Arduino UNO
- Load Cell + HX711 Amplifier
- 16x2 LCD Display
- Servo Motor
- Power Supply
- Buzzer/Alarm (optional)

### Working Principle:
1. Load cell detects the weight of the object or people on the bridge.
2. Arduino processes the signal and compares it with the predefined threshold.
3. If the weight exceeds the limit:
   - A warning is displayed.
   - Servo motor can restrict further entry (e.g., by closing a gate).
   - Alarm/buzzer can be triggered.

---

## 🧪 Results & Observations

- The system can detect live weight changes and display them on an LCD.
- When the threshold is crossed:
  - The servo motor activates to restrict access.
  - A message is shown on the LCD.
- This was tested with simulated bridge entry using weights and people counting logic.

---

## 🎯 Goals Achieved

- ✅ Real-time weight monitoring
- ✅ Safety action via Arduino (servo lockout/alarm)
- ✅ LCD output for user feedback
- ✅ Accurate load handling using Load Cell with HX711

---

## 📈 Future Enhancements

- Wireless data transmission to central monitoring system
- Integration with IoT dashboards
- Solar-powered design for remote areas
- GSM/IoT alert for real-time bridge status updates
- Cloud logging of overload incidents

---

## 🛠️ How to Run (Optional if Code is Present)

1. Connect load cell to HX711 → Connect to Arduino Uno
2. Upload `pranatrana.ino` using Arduino IDE
3. Open Serial Monitor or check LCD for real-time weight
4. Adjust `THRESHOLD` value in code for max allowed bridge weight

---

## 📚 References

- AASHTO LRFD Bridge Design Specs, 6th Edition
- Dias et al. (2019) – Impact of Overweight Vehicles
- Arduino.cc Documentation
- HX711 Load Cell Amplifier Tutorial – SparkFun
