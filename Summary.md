Task Summary: Incorporating new components in the Platform
Problem Statement
The Arduino on Cloud platform already has many components available such as Arduino Uno, Breadboard, Buzzer, Seven-Segment-Display, LCD, etc. The task is to incorporate two new components from the list given below without breaking the existing code:

DHT-11 Sensor
7447 decoder IC
ESP8266 wifi module with a logic level converter from 5v to 3.3v
Solution
I have chosen to incorporate DHT-11 Sensor and ESP8266 wifi module into the platform.

To achieve this, I followed the below steps:

Forked the repository (https://github.com/frg-fossee/eSim-Cloud) and cloned it on my local machine.
Created a new branch 'feature/DHT-11-ESP8266' from the Develop branch.
Modified the circuit design and created a new breadboard design for DHT-11 Sensor and ESP8266 wifi module using Fritzing tool.
Modified the existing codebase to integrate DHT-11 and ESP8266 wifi module.
Created new libraries for DHT-11 and ESP8266 wifi module and added them to the existing libraries directory.
Tested the changes thoroughly by simulating the circuit using eSim.
Recorded a demo of the simulation and created a screencast video to showcase the simulation process.
Committed the changes to the branch and pushed the changes to the forked repository.
Created a Pull Request to merge the changes in the Develop branch of the original repository.
Created a release tag for the merged changes.
Changes Made
Added a new breadboard design for DHT-11 Sensor and ESP8266 wifi module using Fritzing tool.
Modified the existing codebase to integrate DHT-11 and ESP8266 wifi module.
Created new libraries for DHT-11 and ESP8266 wifi module and added them to the existing libraries directory.
Demo
Link to the screencast video showcasing the simulation process: https://youtu.be/yufUOQX18O8

Files Changed Heavily
DHT-11 library files
ESP8266 wifi module library files
Arduino code files
Release
Release Tag URL: https://github.com/<your username>/<your project name>/releases/tag/v1.0