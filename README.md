# Smart Factory Automation using PLC-Based Speed Control

## Project Overview

This project focuses on the development of a modular, PLC-controlled automation system to streamline and improve manufacturing processes, specifically cap handling, capping, and product transfer in a high-speed production line. The system integrates pneumatic, electric, and stepper actuators controlled by a Siemens S7-1200 PLC, ensuring precision, speed control, and reduced human intervention.

## Authors

Thamarai Kannan M K S  
Vignesh Ram R  
Jubair Ahamed L  
Kavin Raj S  

B.E. Mechatronics Engineering  
Bannari Amman Institute of Technology

## Key Features

- Modular 3-stage automation: Cap Handling, Capping, Product Transfer
- PLC-based centralized speed and motion control (Siemens S7-1200)
- Pneumatic suction-based Cartesian actuator for cap picking
- Electric actuator for controlled capping with torque sensors
- Gantry-type belt system for product transfer using stepper motors
- Real-time feedback and precision monitoring using sensors

## Technologies Used

- Siemens S7-1200 PLC (with TIA Portal)
- Proximity and Magnetic Sensors (Festo)
- Pneumatic Actuators with Suction Cups
- Electric Actuators and Nidec DC Motors
- Stepper Motors for gantry drive
- Gantry Belt Mechanism for product movement

## System Architecture

| Module             | Description                                           |
|--------------------|-------------------------------------------------------|
| Cap Handling       | Pneumatic suction actuator to pick caps from stack    |
| Capping            | Electric actuator with torque monitoring              |
| Product Transfer   | Stepper-motor-driven gantry belt for movement         |
| Control Logic      | Central PLC system coordinating all modules           |
| Sensors            | Proximity and magnetic sensors for real-time control  |

## Workflow

1. **Cap Handling**: Pneumatic actuator with suction cup picks up caps upon sensor detection.
2. **Capping**: Electric actuator caps the bottle using controlled torque application.
3. **Product Transfer**: Stepper motor-driven gantry system transfers the bottle to packing.
4. **PLC Logic**: Controls operation sequencing, speed synchronization, and error handling.

## Performance Summary

- Cycle Time: 15 seconds per product (240 products/hour)
- Cap Placement Accuracy: 90%
- Capping Torque Accuracy: ±2%
- Transfer Accuracy: 97%
- Defect Rate: 3%

## Benefits

- Reduced manual intervention and labor
- Improved speed and consistency
- Modular and scalable system design
- Enhanced operational safety and quality control

## Future Enhancements

- IoT-based remote monitoring and predictive maintenance
- Adaptive AI-based speed optimization
- Environmental factor sensing (temperature/humidity) for robust operation

## Repository Content

- `README.md` – Project documentation
- `PLC_LadderLogic.pdf` – PLC network diagrams or exported logic (optional)
- `Images/` – Photos or CAD models of the setup (if available)
- `Reports/FINAL_S7_REPORT.pdf` – Full technical report

## License

This project is intended for academic and learning use. For reuse, adaptation, or extensions, please credit the authors appropriately.
