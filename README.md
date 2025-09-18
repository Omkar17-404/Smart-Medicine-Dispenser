# Smart-Medicine-Dispenser
This project is a smart, automated medicine dispenser designed to improve medication adherence and provide peace of mind for patients and their caregivers. It is an Internet of Things (IoT) solution that combines a physical dispensing mechanism with a smart notification system.

Our smart medicine dispenser provides a reliable, automated solution to this problem. It is designed to:
Automate Dispensing: Dispense the correct medication at the precise scheduled time.
Provide Smart Alerts: Use a built-in buzzer and LCD to remind the patient.
Enable Remote Monitoring: Send instant notifications to a patient's phone or a caregiver's device via Wi-Fi.
This project was built to be a user-friendly and highly effective tool for improving patient health and reducing the burden on caregivers.

Key Features
Automated Scheduling: A Real-Time Clock (RTC) module keeps accurate time and triggers the dispensing sequence.
Real-Time Display: An I2C LCD screen shows the current time, upcoming doses, and system status messages.
Audible & Visual Alerts: A buzzer and a flashing message on the LCD ensure the patient is alerted at medication time.
IoT Notifications: An ESP32 microcontroller with Wi-Fi sends push notifications to a smartphone via a cloud service Blynk, alerting patients and/or caregivers of a dose.
Pill Verification: An infrared sensor confirms that a pill has been successfully dispensed.

Technologies Used
Microcontroller: ESP32
Actuator: Servo Motor
Display: I2C 16x2 LCD
Sensing: DS3231 RTC Module, Proximity/IR Sensor
Software: Arduino IDE, C++
Connectivity: Wi-Fi, IFTTT/Blynk API
