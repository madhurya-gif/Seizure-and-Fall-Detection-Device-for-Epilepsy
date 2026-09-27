# Seizure and Fall Detection Device for Epilepsy
# Overview
This device is a simple feedback device that uses Arduino Nano 33 BLE. It is a small watch like device that detects a person's rapid movements or seizures and when a person falls down. Meant to detect epileptic seizures and a buzzer starts to beep when detected. Different beeps for fall and seizure. An LED glows and a push button exists to turn off beeping. When beeping, it waits for some time for the push button to be pressed, if time lapses then it sends a BLE signal to a phone. Simple prototype, developed in 1.5 weeks as part of a course called "Feedback Devices for Special needs". 
# Tools
1. Arduino Nano 33 BLE
2. Breadboards & Wires
3. 3D printer for casing
4. Push button, buzzer, LED
5. C++ code
# Results
1.  Seizures are detected well. Waits for a certain pattern and time before beeping.
2.  Fall is also detected based on a simple logic. There is free fall and then impact.
3.  The gravity acceleration changes. Thresholds are around 0.8g for free fall and around 1.7g for impact.
4.  Time threshold: beeping for about 3 seconds before sending BLE.
5.  Frequency threshold is about 2-30  Hz for seizure detection.
6.  Simple and cheap alternative for smart devices and very accessible.
7.  Can be improved well. Best use case for severe epilepsy and seizures and can alert people to avoid physical injuries as a result of seizures and fall such as tongue biting, twisted body, sharp surface injuries etc. 
