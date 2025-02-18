## Title of the Project
AnomolyDetection-Hydrogen FCEV
## Data Description
A set of four Fuel cells (# 5, 6, 7 and 18) were run through 2 different operational profiles
(charge& discharge) at room temperature. Charging was carried out in a constant current (CC)
mode at 1.5A until the Fuel cell voltage reached 4.2V and then continued in a constant voltage
(CV) mode until the charge current dropped to 20mA. Discharge was carried out at a constant
current (CC) level of 2A until the battery voltage fell to 2.7V, 2.5V, 2.2V and 2.5V for Fuel cell 5 6 7
and 18 respectively. 
Repeated charge and discharge cycles result in accelerated aging of the Fuel cell. The
experiments were stopped when the Fuel cell reached end-of-life (EOL) criteria, which was a 30%
fade in rated capacity (from 2Ahr to 1.4Ahr).
This data can be further used for the prediction of both remaining charge (for a given discharge
cycle) and remaining useful life (RUL).
Files: 
1. B0005.mat Data for Fuel cell #5
2. B0006.mat Data for Fuel cell #6
3. B0007.mat Data for Fuel cell #7
4. B0018.mat Data for Fuel cell #18

## Data Dictionary
- ambient_temperature: ambient temperature (degree C)
- datetime: the date and time of the start of the cycle, in MATLAB date vector format
- data: data structure containing the measurements
- Voltage_measured: Fuel cell terminal voltage (Volts)
- Current_measured: Fuel cell output current (Amps)
- Temperature_measured: Fuel cell temperature (degree C)
- Current_charge: Current measured at load (Amps)
- Voltage_charge: Voltage measured at load (Volts)
- Time: Time vector for the cycle (secs)
- Capacity: Fuel cell capacity (Ahr) for discharge till 2.7V

## Requirements
<!--List the requirements of the project as shown below-->
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks.
* Development Environment: Python 3.6 or later is necessary for coding the sign language detection system.
* Deep Learning Frameworks: TensorFlow for model training, MediaPipe for hand gesture recognition.
* Image Processing Libraries: OpenCV is essential for efficient image processing and real-time hand gesture recognition.
* Version Control: Implementation of Git for collaborative development and effective code management.
* IDE: Use of VSCode as the Integrated Development Environment for coding, debugging, and version control integration.
* Additional Dependencies: Includes scikit-learn, TensorFlow (versions 2.4.1), TensorFlow GPU, OpenCV, and Mediapipe for deep learning tasks.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![image](https://github.com/user-attachments/assets/5fd58955-529f-457e-95d0-828130446578)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - cycle vs capacity

![image](https://github.com/user-attachments/assets/b41f92f0-6e53-45f2-87ba-3573c096201a)

#### Output2 -Datetime(when we started the charging of the cycle) vs time (time taken to complete one cycle)
![image](https://github.com/user-attachments/assets/97378a1c-2fee-4e57-97a7-aad4aacd9fbe)
### 3. Datetime vs Capacity of fuel cell
![image](https://github.com/user-attachments/assets/0515530e-2d9b-44dc-916f-cf74c52da599)
### 4. Time vs Capacity
![image](https://github.com/user-attachments/assets/73625f8f-827e-46a4-ad5b-2d895506a006)
### 5. Fuel cell temperature vs time
![image](https://github.com/user-attachments/assets/2da77a4c-3315-4116-a4ec-f10db03289d6)



## Results and Impact
"AnomalyDetection-Hydrogen FCEV" in the available sources. However, I can provide some general insights into anomaly detection in Hydrogen Fuel Cell Electric Vehicles (FCEVs).

Anomaly detection in FCEVs involves monitoring various parameters to identify deviations from normal operation, which could indicate potential issues or failures. Key areas of focus include the fuel cell stack, hydrogen storage system, and overall vehicle performance. For instance, the National Renewable Energy Laboratory (NREL) conducts evaluations of FCEVs to assess fuel cell stack durability, efficiency, vehicle range, fuel economy, and safety. These evaluations help in identifying anomalies and improving the technology. 
NREL

Additionally, the California Air Resources Board (CARB) publishes annual evaluations on FCEV deployment and hydrogen fuel station network development. These reports provide insights into the current status and progress of FCEVs, which can be useful for understanding common issues and areas requiring improvement. 
CALIFORNIA AIR RESOURCES BOARD

If you have specific details or context about the "AnomalyDetection-Hydrogen FCEV 8dc743" project or system, please provide more information, and I'll be glad to assist you further.
This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References
1."Utilising Digital Twins for Smart Maintenance Planning of Fuel Cell in Electric Vehicles": This paper presents a framework that employs digital twins for predictive maintenance of fuel cells in electric vehicles. It focuses on real-time condition monitoring and predicting the remaining useful life of fuel cells to optimize maintenance schedules and enhance reliability. 
MATEC CONFERENCES

2."Efficient Water-Related Failure Detection in PEM Fuel Cells": This study proposes a method to detect, diagnose, and classify various water failure modes in Proton Exchange Membrane Fuel Cells (PEMFCs) using a ybrid diagnostic approach. The approach combines a fractional order impedance model with artificial neural networks to identify faults effectively.



