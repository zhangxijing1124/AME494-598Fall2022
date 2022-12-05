# Final Project
#### Name: Xijing Zhang
#### Professor: Tejaswi Linge Gowda
#### Subject Name: Home Security System
#### 01 December 2022

## Report for Final Project(Home Security System)

#### Security is of most concern for anyone nowadays, whether it's data security or the security of their own home. With the advancement of technology and the increasing use of IoT, digital door locks have become very common these days. Digital lock doesn’t require any physical key but it uses RFID, fingerprint, Face ID, pin, passwords, etc. to control the door lock. People have many digital door lock applications using these various technologies, but face recognition door lock systems used by esp32-cam are a good choice to solve this problem.

### 1. Motivation
#### User: People who needs to increase their home security.
#### Objective: Improve home's security level in an easy, low-cost way

### 2. Hardware
#### (1) ESP32 cam
#### (2) Electronic door lock
#### (3) Relay module 
#### (4) 12v power supply
![alt text](https://github.com/zhangxijing1124/AME494-598Fall2022/blob/main/Final%20Project/Picture.jpg)

### 3. Environment and Setting
#### (1) Install ESP32 Board on Arduino IDE
![alt text](https://github.com/zhangxijing1124/AME494-598Fall2022/blob/main/Final%20Project/Picture/Screen%20Shot%202022-12-05%20at%201.08.34%20AM.png)
#### (2) Install the latest Python 2
https://www.python.org/downloads/macos/

#### (3) Common compilation errors: “Exec: “python”: executable file not found in $PATH”
Starting the IDE with the Terminal app could solve this problem:
> open /Applications/Arduino1.8.19.app
#### (4) If you use macOS, the errors may happen: “A fatal error occurred: Failed to write to target RAM (result was 0107) (ESPTOOL-95) #280”
Step 1:Install USB-to-Serial macOS Vendor Driver
https://www.wch.cn/downloads/CH34XSER_MAC_ZIP.html
Step 2: Select the new port “cu.wchusberial529A0093721”

#### (5) Install “ArduinoWebsockets.h” Library
You could find it in GitHub Repo
![alt text](https://github.com/zhangxijing1124/AME494-598Fall2022/blob/main/Final%20Project/Picture/WechatIMG970.png)

#### (6) Setting
Open “face_test.ino”, change the ssid and password to yours
![alt text](https://github.com/zhangxijing1124/AME494-598Fall2022/blob/main/Final%20Project/Picture/Screen%20Shot%202022-12-05%20at%201.28.46%20AM.png)
