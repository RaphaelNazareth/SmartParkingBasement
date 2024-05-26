# SmartParkingBasement
This project aims to detect gas leaks in a basement or high-intensity smoke from vehicles parked there. Additionally, the smart parking system is equipped with LEDs that can detect empty parking spaces. Notably, this project is implemented without a microcontroller.


![Inside Parking Basement](https://github.com/RaphaelNazareth/SmartParkingBasement/assets/86475236/14e06a52-8657-465d-9e9b-d665abc69fc9)
*Image: Inside the basement*
![Outside Parking Basement](https://github.com/RaphaelNazareth/SmartParkingBasement/assets/86475236/a2450072-65c7-4e61-93c2-32ab722bd830)
*Image: Outside basement miniature*

# Features
- Miniature Replica: A 1:64 scale model of a real-life basement.
- Gas and Smoke Detection: Gas sensors and buzzers mounted on the walls detect gas leaks and provide auditory alerts.
- Parking Space Detection: Photoresistors on the parking floor detect vehicle presence, while LED indicators on the walls light up to show occupied parking spaces.
# Technologies Used
- KiCad: create schematic diagrams 
- Tinkercad: demonstrate each component layouts.
- NI Multisim: checked voltage levels across components
# How It Works
The system operates in a continuous loop:

- Gas Detection: Gas sensors detect NH3 smoke from a car. If smoke is detected, the fan and buzzer activate.
- Vehicle Detection: If no smoke is detected, photoresistors detect cars. The LED turns on when a car is detected and off when no car is present.
# Documentation

For a comprehensive demonstration of the Smart-Aquarium in action, please watch the [Video Demonstration](https://drive.google.com/file/d/1OCX7r5Hs2Rc73Zu4nhF_WHBZBUdhfXhH/view?usp=drive_link).


[Return to top](https://github.com/RaphaelNazareth/SmartParkingBasement)
