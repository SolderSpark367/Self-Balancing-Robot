# Self-Balancing-Robot

My project is the Self-Balancing Robot. The purpose of this project is to have a standing up 2 wheeled robot that balances on its own. Its kind of like a townhouse on wheels trying to balance in place. You may be wondering why does this project even exist. Well I mean it may not be useful in everyday life but it is a great way to learn the basics of robotics such as using motor drivers, using motors, using your microcontroller which in this case is the ESP32-WROVER, and the thing that controls almost everything about the balancing; the MPU-6050. You may be like what the heck is a MPU-6050? A MPU-6050 is a small PCB that are pretty cheap to buy and very useful. They detect how much your robot/object is tilting and sends that information to your microcontroller which then processes that info to give to the motor driver so the motors can react quickly for the robot to balance upright. In conclusion I wanted beginners to learn how tilt, motors, microcontrollers, and etc work.


-Below Are Pictures of my 3d Chassis Design-
<img width="1006" height="900" alt="Screenshot 2026-11-03 212520" src="https://github.com/user-attachments/assets/57536acc-afdf-4e46-9e73-41498285ebc0" />
<img width="900" height="918" alt="Screenshot 2026-11-03 200919" src="https://github.com/user-attachments/assets/6503e890-7962-4b01-ad52-4e7ed0c2a9fd" />

-Below is the wiring diagram (I generated it using ChatGPT)-




-Here is the picture of the list of hardware components that will be needed (it does not include the ESP32-WROVER becuase it is currently in a different project of mine)-
![IMG_4450_72906b576444640d.jpeg](https://cdn.hackclub.com/01a19354-bc25-76a4-8a1c-2e32b04643a4/IMG_4450_72906b576444640d.jpeg)

-BOM-
- ESP32-WROVER-CAM = $18 (Amazon)
- L298N Motor Driver = $6 (Aliexpress)
- 2 Yellow TT Motors with Wheels = $5 (Aliexpress)
- MPU-6050 Tilt Sensor = $2 (Aliexpress)
- 2 3.7v Recharageable Batteries = $4 (Aliexpress)
- 4-AA Battery Holder = $2 (Aliexpress) 
- LM2596S Buck Converter = $4 (Aliexpress)
- USB to C Cable = $3 (Aliexpress)
- 4 AA Batteries = $5 (Amazon)
- Small Jumper Wire Set = $3 (Aliexpress)
- Filament for Chassis = $5 (Amazon or Aliexpress both can work)
- Screws, Nuts, and Bolts = $2 (Amazon or Aliexpress both work)
- 3.7v Battery Charger = $3 (Amazon or Aliexpress both have it)

- Total = $62 Excluding Shipping and Tax


CREDITS: ChatGPT for generating the wiring diagram


