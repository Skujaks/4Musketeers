# 4Musketeers

A device that detects cabinet tampering and environmental risks.  
It flags events such as:
- door movement
- movement or enclosure tampering
- potential water damage

## Why It Matters
Street-level telecom and utility cabinets are at risk of theft, vandalism, and intrusions. 
Industry reports (2024–2025) highlight thousands of incidents, causing costly outages and reduced reliability.  
This node provides early warnings to protect networks and equipment.  


## Sensors Included
- **Hall effect sensor** - detects door movement
- **LSM6DSO16IS gyroscope** – flags movement or enclosure tampering
- **MH-RD raindrop sensor** - detects and warns about potential water damage

## Fetures
- Arming and disarming the alarm
- LED lights to indicate the alarm status
- Sent notification and siren if alarm is triggered
- Sent notification for water damage

## Running the demo
Download the code from ... and flash it to the stm32nucleo using mbed IDE. To get the project working correctly wire 
