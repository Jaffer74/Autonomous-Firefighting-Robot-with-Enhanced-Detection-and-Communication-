# 🔥 Autonomous Firefighting Robot with Enhanced Detection and Communication  

![Autonomous Firefighting Robot](https://github.com/Jaffer74/Autonomous-Firefighting-Robot-with-Enhanced-Detection-and-Communication-/blob/main/Enhanced_Firefighting_Robot.png) 

## 🌟 Introduction  
This project addresses critical challenges in fire detection and suppression systems, such as delayed response times and limited mobility. The **Autonomous Firefighting Robot** is a state-of-the-art solution designed to detect and extinguish fires autonomously while providing real-time communication with authorities.  

## ✨ Features  
- **Fire Detection**: Uses flame sensors to detect fire.  
- **Gas Detection**: Equipped with an MQ2 gas sensor for hazardous gas detection.  
- **Firefighting Mechanism**: Servo-controlled water pump for targeted water spraying.  
- **Real-Time Alerts**: GSM module integration for SMS and call alerts to authorities.  
- **Obstacle Avoidance**: Infrared sensors ensure smooth navigation.  

## 🛠️ Components  
- **Arduino Uno**: Central microcontroller to manage operations.  
- **Flame Sensors**: Detects fire sources and navigates towards them.  
- **MQ2 Gas Sensor**: Detects hazardous gases in the environment.  
- **Servo Motor**: Controls the direction of the water spray.  
- **GSM Module (SIM800L)**: Sends SMS and calls to alert authorities about fire or gas leaks.  
- **L293 Motor Driver**: Powers the motors for navigation.  
- **Water Pump**: Extinguishes the fire effectively.  

## ⚙️ Working Mechanism  
1. **Initialization**: Sensors, GSM module, and components are set up.  
2. **Fire Detection**: Flame sensors scan the environment, and the robot moves towards detected fire.  
3. **Gas Detection**: Hazardous gases are detected by the MQ2 sensor, triggering alerts.  
4. **Firefighting**: The robot activates the water pump and sprays water using the servo motor to extinguish the fire.  
5. **Real-Time Communication**: Sends SMS and phone calls via GSM module for remote monitoring.  

## 📈 Results  
- Efficiently detected and extinguished small to medium-sized fires.  
- Sent real-time alerts to predefined contacts.  
- Successfully navigated obstacles and reached fire sources.  

## 🚀 Future Enhancements  
- **Thermal Imaging Cameras**: Improved fire detection in varying conditions.  
- **Solar Charging**: Extend operational duration with renewable energy.  
- **Enhanced Mobility**: Greater adaptability for rough terrains.  

## 🏁 Getting Started  

### 📋 Prerequisites  
- **Hardware**: Arduino Uno, Flame Sensors, MQ2 Sensor, GSM Module, Servo Motor, Water Pump, and L293 Motor Driver.  
- **Software**: Arduino IDE.  

### ⚡ Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Autonomous-Firefighting-Robot.git
   cd Autonomous-Firefighting-Robot
2. Load the Arduino code onto the Arduino Uno board using the Arduino IDE.  
3. Connect the components as per the provided circuit diagram (available in the repository).  

### ▶️ Run the Project  
- Power the robot.  
- Monitor its activities using serial communication in the Arduino IDE.  
- Alerts and notifications will be sent automatically when a fire or gas leak is detected.  

## 📂 Repository Structure  

```plaintext
Autonomous-Firefighting-Robot/
│
├── Arduino_Code/        # Code for Arduino Uno
├── Documentation/       # Project reports and diagrams
├── Images/              # Robot images and testing scenarios
└── README.md
```


