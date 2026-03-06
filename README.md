# ESP32 FPV Rover

![AI Sketch](images/AI_Sketch.png)

Personal electronics project developed as part of the **Statis Hack Club** program.  
This project is meant to learn **embedded systems, robotics, and hardware design** by building a small FPV rover.

## Overview
The rover streams live video via an **ESP32-CAM** and can be remotely controlled.  
It features camera tilt and front wheel steering using servo motors, and a rear DC motor for movement.

## Why I Made This Project
I wanted to **practice hands-on electronics and robotics** and explore power distribution, motor drivers, and camera control.

## Hardware Components
- ESP32-CAM  
- MG90S Servo Motor (x2)  
- DC Motor  
- MX1508 Motor Driver  
- TP4056 Charging Module  
- 3.7V LiPo Battery  
- Capacitors (470µF and 0.1µF)

## Project Status
- Design phase completed  
- Components selected  
- Initial schematic created  
- GitHub repository structure prepared  
- CAD and PCB designs will be added once components arrive

## Visuals
### Wiring / Schematic
![Schematic](images/schematic.png)  
*Initial wiring schematic on perfboard.*

## Bill of Materials (BOM)

| Name                    | Purpose                     | Cost (USD) | Qty | Total (USD) | Link | Distributor |
|-------------------------|----------------------------|------------|-----|-------------|------|------------|
| Dupont wires            | Connect the components     | $4.55      | 1   | $4.55       |      | Aliexpress |
| Perfboard 7x9 cm        | PCB                        | $1.85      | 1   | $1.85       |      | Aliexpress |
| Switch                  | Turn ON/OFF                | $1.55      | 1   | $1.55       |      | Aliexpress |
| TP4056                  | Charging the battery       | $1.05      | 1   | $1.05       |      | Aliexpress |
| 0.1 uF Ceramic Capacitor| Clean the signal           | $1.69      | 1   | $1.69       |      | Aliexpress |
| 470uF Capacitor         | Clean the signal           | $2.70      | 1   | $2.70       |      | Aliexpress |
| Driver DC Motor         | To control the DC Motor    | $1.59      | 1   | $1.59       |      | Aliexpress |
| DC Motor N20            | Motor for accelerating     | $2.56      | 1   | $2.56       |      | Aliexpress |
| Battery                 | Battery                    | $7.98      | 1   | $7.98       |      | Aliexpress |
| Mg90s                   | Servo                      | $2.72      | 2   | $5.44       |      | Aliexpress |
| ESP32 CAM               | Microcontroller            | $9.07      | 1   | $9.07       |      | Aliexpress |

## Author
Personal electronics project focused on **learning embedded systems, robotics, and hardware design**.
