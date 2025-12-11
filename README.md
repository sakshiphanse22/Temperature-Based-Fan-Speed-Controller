# Temperature-Based-Fan-Speed-Controller
The Temperature-Based Fan Speed Controller uses an Arduino UNO and a DHT11 sensor to monitor ambient temperature and adjust fan speed via PWM control.  

## About the Project
The Temperature-Based Fan Speed Controller uses an **Arduino UNO** and a **DHT11 sensor** to monitor ambient temperature and adjust fan speed via **PWM control**.  

---

## Features
- Real-time temperature monitoring  
- Automatic fan speed control using PWM  
- Sensor-based feedback for accurate operation  
- Compact and low-power embedded solution  

---

## Hardware Components
- Arduino UNO  
- DHT11 Temperature Sensor  
- DC Fan  
- Power Supply  
- Connecting Wires & Breadboard  

---

## Firmware / Software
- Programming Language: Embedded C  
- IDE: Arduino IDE  
- Libraries: DHT sensor library, PWM libraries  

---

## working
In the first step, we have installed DHT 11 library, as we have used DHT 11 temperature & humidity sensor. 
We have set the threshold temperature in such a way that, when the temperature rises above threshold point, the LED on pin no. 13 of Arduino UNO board will glow and simultaneously, the fan will turn ON.
The fan will turn OFF, when the temperature will fall below threshold point.
