# Intelligent-urban-environment-for-city-monitoring

AIM
To design and build an intelligent urban environment for city monitoring, incorporating smart surveillance, intelligent street lighting, and fire monitoring within Cisco Packet Tracer.

PROBLEM STATEMENT
Design and build an intelligent urban environment for city monitoring, incorporating smart surveillance, intelligent street lighting and fire monitoring within Cisco Packet Tracer.

SCOPE OF THE SOLUTION
This project implements a comprehensive smart city monitoring system that includes:
Smart Surveillance System: Motion-activated webcam for real-time monitoring and security
- Intelligent Street Lighting: Automated street lamp control based on motion detection for energy efficiency
- Fire Monitoring System: Smoke detection with automatic siren activation for emergency response
- Centralized IoT Management: All devices managed through a central Home Gateway
- Remote Monitoring: PC-based control and monitoring interface
- Wireless Connectivity: All IoT devices connected via wireless network for scalable deployment

REQUIRED COMPONENTS

IDE NAME: 
Cisco Packet Tracer

SOFTWARE:
- Cisco Packet Tracer (Network simulation and IoT modeling)
- IoT device management interface
- Automation rule engine

HARDWARE USED:
- DLG300 Home Gateway - Central hub for device management and automation
- PC-PT (PC0) - Monitoring and control station
- Webcam (IoT1) - Smart surveillance camera
- Street Lamp/Light (IoT2) - Intelligent lighting system
- Smoke Detector (IoT3) - Fire detection sensor
- Siren (IoT4) - Emergency alert system
- Motion Detector (IoT5) - Movement sensing for automation triggers

Network Topology
The project uses a star topology with the Home Gateway as the central hub. All IoT devices are connected wirelessly to the gateway, enabling:
- Device registration and management
- Real-time monitoring and control
- Automated responses based on sensor inputs
- Remote access via PC interface

Automation Rules Implemented
1. Motion Detection Rule: When motion is detected → Street lamp turns ON + Webcam activates
2. Fire Safety Rule: When smoke is detected → Siren activates
3. Energy Saving Rule: When no motion is detected → Street lamp turns OFF
