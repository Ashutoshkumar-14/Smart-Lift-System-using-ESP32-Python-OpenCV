# 🚀 Smart Lift System using ESP32, Python & OpenCV

A prototype of an intelligent, camera-based crowd-aware elevator system built using **ESP32**, **Arduino C**, **Python**, and **OpenCV**.  
This system automatically detects the most crowded floor using live camera feeds and navigates the lift to serve that floor. Once the task is done, the lift returns to the ground floor, simulating an efficient smart building infrastructure.

---

## 📌 Key Features
- 🧠 Crowd Detection using OpenCV and Haar Cascade classifier.  
- 🔁 Lift Navigation logic controlled by ESP32 and DC gear motor.  
- 📡 HTTP-based Wi-Fi Communication between Python and ESP32.  
- 🌐 Built-in Web Server hosted on ESP32 to receive floor requests.  
- 🔦 LED Indicators to show lift’s current position (per floor).  
- 🧲 Reed Switches with magnets to accurately detect floor stops.  
- 🛠️ Modular & Scalable setup allowing multiple cameras and floors.  

---

## 🖼️ Real-World Applications
- 🏥 **Hospitals**: Prioritize floors with more patients/staff waiting.  
- 🏫 **Schools/Colleges**: Smart elevator scheduling during class hours.  
- 🏢 **Smart Offices**: Improve elevator efficiency in peak times.  
- 🏬 **Shopping Malls**: Crowd handling during rush hours.  

---

## 🛠️ Hardware Components

| Component         | Quantity | Description                                   |
|-------------------|----------|-----------------------------------------------|
| ESP32 Dev Board   | 1        | Main controller, Wi-Fi capable               |
| DC Gear Motor     | 1        | Drives lift movement                         |
| L298N Motor Driver| 1        | Controls motor direction/speed               |
| Reed Switches     | 3        | Floor detection via magnetic sensors         |
| LEDs              | 3        | Indicate lift location                       |
| Magnets           | 3        | Activate reed switches per floor             |
| Jumper Wires, Breadboard | -  | Prototyping                                   |
| Power Supply      | 1        | Motor and ESP32 powering                     |

---

## 💻 Software & Libraries
- **Arduino IDE** – For ESP32 programming  
- **Python 3.x**  
- **OpenCV (cv2)** – For face detection  
- **requests** – For HTTP requests to ESP32  
- **Haar Cascade** – Pre-trained face detection model  

---

## 📁 File Structure
