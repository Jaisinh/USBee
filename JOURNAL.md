# USBee -The BIG DADDY of pentesting tools

<img width="2172" height="724" alt="ChatGPT Image Jun 20, 2026, 12_25_58 AM" src="https://github.com/user-attachments/assets/9253e067-580a-4e8f-8cb5-a52046d885d1" />
I initially sketched the logo by hand and later used AI tools to refine and polish it into a more professional design.

[Link](https://user-cdn.hackclub-assets.com/019ee13f-3206-7648-bb24-fc1554dd3182/IMG_20260620_002140339~2.jpg)

FUNCITONALITIES:
-  Keystrokes injection but with wireless caoabilites
-  Keystroke Capture
-  Wirless deauth
-  Wirless beacon
-  copy usb drives??
  
# What i need?
So this is what i would need for the wirless keystroke injection i would just need a male usb which can also be printed on the pcb for it to act as a key logger i would need a sd card reader and a female usb the male one is already there  for it to act as a wirless beacon and deauth i would need a small oled screen and way to choose the different modes like a rotary switch but i cant find the component 😭            <img width="216" height="213" alt="Screenshot 2026-06-19 at 4 25 30 PM" src="https://github.com/user-attachments/assets/860312ef-b47a-445d-a7c2-a733706be5a9" />

pss.. I would also nedd a lipo battery an d i beleve the xiao esp32-c3 already has a battery charging built in

# STARTING THE BUILD:
At first I thought I would use Kicad to design the pcb but for the world of it i could add the xiao's symbol and footprint libriray i tried installing from the OPL library on github and also tried installing throught snapeda but i couldn't .I also decided to chaing the microcontroller to the xiao esp32-s3 plus its a bit epensive but it can act as a usb host and i can connect the male usb a port directl and @Rudy from slack helped me find what the above componen was called .I will use it to controll the oled screen to perferom different functionalities

I also ended up changing to easyeda as it had most of the libraries pre installed and made a mock schematic i oly has the wifi duck functionality and and the deauth and beacon functionality i will add reset of the functionalities tommorow 

<img width="607" height="290" alt="Screenshot 2026-06-20 at 12 19 46 AM" src="https://github.com/user-attachments/assets/c43ff58e-5b52-4fa6-9cb3-580d091f0fda" />


