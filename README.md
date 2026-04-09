# fan-control-using-max31790
design of a 6, 4wire fan control board that can independently control each fan individually by controlling the pwm output. 

📌 Overview

This project is a Smart Fan Control System designed to monitor and control multiple fans using embedded hardware. It supports real-time speed control, fault detection, and communication with a host system.

The system is ideal for applications like:

Server cooling systems
PC fan hubs
Industrial ventilation systems
🚀 Features
🔄 Multi-Fan Control (Supports multiple PWM fans)
⚡ Dynamic Speed Adjustment
🌡️ Temperature-Based Control (Optional)
⚠️ Fan Fault Detection (FanFail Monitoring)
📡 I2C Communication Interface
🧠 Microcontroller-Based Smart Control (Optional)
🔌 12V Input with 5V/3.3V Regulation
Hardware Components
Microcontroller (e.g., STM32F103C8T6)
Fan Controller IC (e.g., MAX31790)
PWM Fans (4-pin)
Power Supply (12V input)
Buck Converter (12V → 5V / 3.3V)
Pull-up Resistors (for I2C, PWM, TACH)

code for the stm32 is not available 

SCHEMATIC IMAGE FOR REFERENCE
<img width="1106" height="775" alt="image" src="https://github.com/user-attachments/assets/75b1ddba-4f87-46fa-8990-3886df2b14b3" />

PCB LAYOUT FOR REFERENCE
<img width="1136" height="787" alt="image" src="https://github.com/user-attachments/assets/b094e3a5-9188-448c-972a-51a710110909" />

3D VIEW FOR REFERENCE
<img width="795" height="598" alt="image" src="https://github.com/user-attachments/assets/8b2576c4-60ee-4ffa-9fff-663e27173a95" />


