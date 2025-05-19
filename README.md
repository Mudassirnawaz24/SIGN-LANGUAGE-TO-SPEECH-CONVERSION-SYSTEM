# SIGN-LANGUAGE-TO-SPEECH-CONVERSION-SYSTEM

An innovative mini project aimed at bridging communication barriers between speech-impaired individuals and the rest of the world. This system uses flex sensors attached to a glove to detect finger gestures and convert them into text and audible speech using an Arduino Uno, Bluetooth HC-05, and an LCD I2C display.

![Prototype Image](image3/final_prototype.jpg) <!-- Replace with actual image filename -->

---

## 📌 Project Overview

This project is a **Sign Language to Speech Conversion System** designed to help hearing or speech-impaired individuals communicate easily using a wearable glove with flex sensors. The glove interprets hand gestures and translates them into corresponding text displayed on an LCD and speech output via Bluetooth using a mobile TTS application.

---

## 🔧 Features

- Real-time gesture detection and speech conversion
- Compact and wearable glove system
- Text display on LCD
- Bluetooth-enabled speech output
- Custom gesture programming via Arduino IDE

---

## 🧰 Technologies & Tools

- **Microcontroller:** Arduino Uno
- **Sensors:** Flex Sensors (3)
- **Display:** 16x2 LCD with I2C module
- **Wireless Communication:** HC-05 Bluetooth Module
- **Programming:** C/C++ via Arduino IDE
- **Support Tools:** TTS Android Application

---

## 🛠️ Components Used

| Component            | Description                                  |
|---------------------|----------------------------------------------|
| Flex Sensors         | Detects finger bends and gestures            |
| Arduino Uno          | Controls logic and processes sensor data     |
| HC-05 Bluetooth      | Sends data to a mobile TTS app               |
| 10k Resistors        | For voltage divider circuit                  |
| LCD 16x2 (I2C)       | Displays converted text                      |
| Arduino IDE          | Used to upload code to Arduino               |

![Block Diagram](image1/block_diagram.jpg) <!-- Replace with actual image filename -->
![Circuit Diagram](image2/Flowchart.jpg) <!-- Replace with actual image filename -->

---

## 🚀 How It Works

1. **Gesture Input**: Flex sensors detect finger bending angles.
2. **Data Processing**: Arduino interprets analog input from sensors.
3. **Text Display**: Recognized gesture is shown on LCD.
4. **Speech Output**: The corresponding text is transmitted via Bluetooth and spoken using a TTS app.

Example Scenarios:
- 🤲 "Please give me food" when ring finger is bent.
- 🖐️ "Please give me tablets" when index & middle fingers are bent.

---

## 📂 Project Structure

/sign-language-speech-converter
│
├── Arduino_Code.ino # Arduino program code
├── images/ # Folder for prototype and diagrams
│ ├── block_diagram.jpg
│ ├── circuit_diagram.jpg
│ ├── final_prototype.jpg
│ ├── gesture_food.jpg
│ └── gesture_tablets.jpg
└── README.md # This file

yaml
Copy
Edit

---

## 📝 Getting Started

### Prerequisites:
- Arduino Uno
- Flex sensors (3)
- LCD 16x2 with I2C module
- HC-05 Bluetooth module
- Arduino IDE

### Setup Steps:
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/sign-language-speech-converter.git
   cd sign-language-speech-converter
Upload Arduino_Code.ino to your Arduino board using the Arduino IDE.

Pair your smartphone with the HC-05 Bluetooth module.

Use a Text-to-Speech (TTS) app to receive the output.

🎯 Applications
Communication aid for deaf and speech-impaired individuals

Educational tools for learning sign language

Assistive technology in healthcare

Emergency communication in noisy environments

📉 Limitations
Limited gesture vocabulary

Requires consistent gesture input for accuracy

Sensitivity to glove fit and hand movement

🌐 Future Enhancements
Integration of machine learning for gesture recognition

Adding support for multiple sign language dialects

Voice customization

IoT integration with smart home systems

👨‍🎓 Author
SK. Mudassir Nawaz
B.Tech in Electronics & Communication Engineering
Kakatiya Institute of Technology & Science, Warangal

Project Guide: S.P. Girija (Associate Professor, Dept. of ECE)

📚 References
Suharjito et al., “Sign Language Recognition Application Systems,” Procedia CS, 2017.

Ahmed et al., “Electronic Speaking System for Speech Impaired People,” ICEEICT, 2015.

Harish & Poonguzhali, “Hand Gesture Recognition System,” ICIC, 2015.
