# Self-Balancing-Robot

My project is the Self-Balancing Robot. The purpose of this project is to have a standing up 2 wheeled robot that balances on its own. Its kind of like a townhouse on wheels trying to balance in place. You may be wondering why does this project even exist. Well I mean it may not be useful in everyday life but it is a great way to learn the basics of robotics such as using motor drivers, using motors, using your microcontroller which in this case is the ESP32-WROVER, and the thing that controls almost everything about the balancing; the MPU-6050. You may be like what the heck is a MPU-6050? A MPU-6050 is a small PCB that are pretty cheap to buy and very useful. They detect how much your robot/object is tilting and sends that information to your microcontroller which then processes that info to give to the motor driver so the motors can react quickly for the robot to balance upright. In conclusion I wanted beginners to learn how tilt, motors, microcontrollers, and etc work.


-Below Are Pictures of my 3d Chassis Design-
<img width="1006" height="900" alt="Screenshot 2026-11-03 212520" src="https://github.com/user-attachments/assets/57536acc-afdf-4e46-9e73-41498285ebc0" />
<img width="900" height="918" alt="Screenshot 2026-11-03 200919" src="https://github.com/user-attachments/assets/6503e890-7962-4b01-ad52-4e7ed0c2a9fd" />

-Below is the wiring diagram (I generated it using ChatGPT)-
<img width="1827" height="1237" alt="Screenshot 2026-11-05 182301" src="https://github.com/user-attachments/assets/31ae7bc4-d27b-4fbd-a223-45cbc6ee3926" />







-Here is the picture of the list of hardware components that will be needed (it does not include the ESP32-WROVER becuase it is currently in a different project of mine)-
![IMG_4450_72906b576444640d.jpeg](https://cdn.hackclub.com/01a19354-bc25-76a4-8a1c-2e32b04643a4/IMG_4450_72906b576444640d.jpeg)

-BOM-
- ESP32-WROVER-CAM = $18 (Amazon) Link: https://www.amazon.com/Freenove-ESP32-Camera-Development-Board/dp/B0CJJHXD1W/ref=sr_1_3?crid=2YIP66O6LOAYT&dib=eyJ2IjoiMSJ9.Zm82jUy_DV610w7Iwa7XZb2fe-Z85sPhyoaQQ0g36FX9L6NIYUuH15ymK10wybLY6ROeQRMAZxydGUMOW0WXxUY7P_owNjjVs848SwG0BPVQKIrqS2N9AIKqQE9iXyICuqXasNqUG52J4OCmgg2qWp2ViJ89fhAu0GEG1R1QuRQq2WnV9jbn8AKooq9A2NxhKYx8Iwf2qbyuUu6JxVFG8ZMyQ5OfkU011sULTv7jujI.8eDPX1D8YP7jXq3NareVaneF1v3u_S6xThH6Lxeg-Gg&dib_tag=se&keywords=esp32+wrover+cam+board&qid=1793921466&sprefix=esp32+wrover+cam+board%2Caps%2C107&sr=8-3
- L298N Motor Driver = $3 (Aliexpress) Link: https://www.aliexpress.us/item/3256811980939815.html?spm=a2g0o.productlist.main.2.54e04d54syqxDU&algo_pvid=24ecdde6-f08e-49e0-9b80-5c2e302d7a74&algo_exp_id=24ecdde6-f08e-49e0-9b80-5c2e302d7a74-1&pdp_ext_f=%7B%22order%22%3A%2251%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%2112.65%212.57%21%21%2183.88%2117.02%21%402101c4b817939214982698445e0e35%2112000057678942333%21sea%21US%21940486537%21X%211%210%21n_tag%3A-29911%3Bd%3A7c7071ba%3Bm03_new_user%3A-29895%3BpisId%3A5000000219418181&curPageLogUid=HhgnUKwK43Ii&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012167254567%7C_p_origin_prod%3A
- 2 Yellow TT Motors with Wheels = $4 (Aliexpress) Link: https://www.aliexpress.us/item/3256812133292626.html?spm=a2g0o.productlist.main.1.4b5c36fc5TPzhq&algo_pvid=fab2dff1-f6e2-42f2-a2f0-1ad0941a311b&algo_exp_id=fab2dff1-f6e2-42f2-a2f0-1ad0941a311b-0&pdp_ext_f=%7B%22order%22%3A%2278%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%215.39%211.99%21%21%2135.74%2113.16%21%4021032c8d17939215488101761e101d%2112000058070009554%21sea%21US%21940486537%21X%211%210%21n_tag%3A-29911%3Bd%3A7c7071ba%3Bm03_new_user%3A-29895%3BpisId%3A5000000219418181&curPageLogUid=Tfj1p0Ylefad&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012319607378%7C_p_origin_prod%3A
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

- Total = $58 Excluding Shipping and Tax


CREDITS: ChatGPT for generating the wiring diagram


