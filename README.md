# Automatic-Fare-Generator-System-for-Parking-Lots

This repository contains the code and documentation for a prototype of a fully automated fare-generation system for parking lots. The system is capable of detecting vehicles, determining their class, and calculating the fare based on a specific policy. The prototype is built using Raspberry Pi 3 B+ along with OpenCV-Python, an ultrasound sensor, and a camera module.

## Introduction

The Automatic Fare Generation System is designed to automate the process of calculating fares for vehicles in parking lots. It utilizes computer vision techniques, specifically OpenCV-Python, to detect vehicles entering and exiting the parking lot. The system also employs an ultrasound sensor to measure the distance of the vehicle from the sensor, which helps determine the vehicle's class.

### Features
- [x] Fare calculation based on a specific policy
- [x] Raspberry Pi 3 B+ as the hardware platform
- [x] OpenCV-Python for computer vision tasks
- [x] Ultrasound sensor for distance measurement

#### Running the repository

 *  Clone the repository
       git clone https://github.com/Archit1307/Automatic-Fare-Generator-System-for-Parking-Lots
 *  Install the necessary dependencies. Ensure you have Python 3.x and pip installed, then run the following command
       pip install -r requirements.txt
 *  Connect the ultrasound sensor and camera module to your Raspberry Pi 3 B+ as per the hardware documentation

 *  To run the Automatic Fare Generation System, execute the following command:
       python fare_generation.py
