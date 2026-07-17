## What is the Role of the ESP32?
The role of an Esp 32 is to be like the brain; its where the decisions happens, where the data is , and where the sensors are read. Basically, where all the work and technicality happens.
It is a microcontroller that controlls the entire system. It executes C++ program, processes data, communicates with the sensors, connects to Wi-Fi, and sends information to the OLED display

## What is the role of the OLED display?
The role of the OLED display is to display the information that is decided by the ESP32, it cant work on its own. It needs final decisions from the brain to display. So its almost like a UI which is a User Interface.

## What is the role of the DHT22 sensor?
The role of the DHT22 sensor is to sense the tempreture and humidity of the room the DeskClock is in.

## How does the device know the correct time?
The wifi asks the internet server for real time timing and automatically updates based on the internet server.
ESP32 sends the request through Wi-Fi

## what is the system architecture system flow?
Wifi -> Internet server -> Esp 32 -> OLED Display + DHT22 sensor

## Why choose ESP32?
## Microcontroller Decision

I chose the ESP32 because it satisfies all major project requirements:

- Built-in Wi-Fi for internet time synchronization
- Compatible with Arduino IDE and C++
- Enough processing power for the display, sensor, and future features
- Affordable compared to Arduino Nano 33 IoT and Arduino UNO R4 WiFi
- Large community support and many learning resources

The ESP32 also leaves more of the budget available for other components such as the OLED display, DHT22 sensor, buttons, and future upgrades.
