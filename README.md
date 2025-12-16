# Cybersecurity : CSN150
Project: ESP32-Cam Access Point

## Purpose
Set up ESP32 and Arduino enviornment. Execute sketch " Wifiscanner". 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

* Computer

## Links to documentation and tools

## Steps I followed
1. I followed the [documentation](https://randomnerdtutorials.com/esp32-cam-access-point-ap-web-server/)
2. Connected the ESP32 to my computer.
3. Started Arduino IDE.
4. Opened up the CameraWebServer Project example
5. Modified the default by adding "WiFi.softAP(ssid, password);" which allowed it to be an AP. 
6. Customised it with my own personnal ssid & password 
7. Uploaded the sketch to the board
8. Connected from pc to the board

## Problems and Solutions
* Problem: No internet connection. 
* Solution: This is normal since the esp32 is acting as an AP & doesn't send http requests.

## Final Report
In this project, I was able to set up the esp32 as an access point & allowed me to connect my devices directly to it.

## Screenshots
<img width="1920" height="1080" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/1a1614d1-518c-4d43-97a5-d108e97afccb" />
<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/e35bd79d-4123-40b1-afa0-ed188d92db64" />
<img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/8cdb24ee-f426-48dd-9f9e-2235733ad3ba" />
