Description This project implements a Smart Distance Monitoring System ("Centinela") designed to detect objects within a variable range. Unlike static sensors, this system allows real-time sensitivity adjustment (5cm–50cm) using an analog potentiometer.

The firmware is built upon a Finite State Machine (FSM) architecture, enabling a robust "Active/Standby" toggle mode via a capacitive touch sensor with software debounce. Visual feedback is provided through an RGB LED traffic-light logic, ensuring clear status indication for both safety and system state.

Adjustable Threshold: Dynamic mapping of analog input to physical distance limits (map() function).

State Machine Logic: Implemented a toggle switch with debounce control for stable user interaction.

Precision Sensing: Optimized ultrasonic reading using microseconds timing for accurate measurements.

Visual Feedback: Intuitive RGB color coding (Blue: Standby, Green: Safe, Red: Alert).
