This section describes the integration of a flame sensor with a Raspberry Pi for fire detection. The flame sensor provides a digital signal indicating the presence of fire. The Raspberry Pi processes this signal, triggering appropriate actions like sounding an alarm (buzzer) and activating an LED indicator.

SIMULATION STEPS:

SIMULATE FLAME SENSOR: Use a digital signal source in Proteus to simulate the flame sensor's output.

CONNECT TO RASPBERRY PI: Connect the digital signal source to a digital input pin on the Raspberry Pi.

PROGRAM RASPBERRY PI: Write Python code to read the digital input and trigger actions based on the detected fire state.

SIMULATE FIRE EVENTS: Manually manipulate the signal source to simulate fire detection scenarios.

EVALUATE PERFORMANCE: Observe the Raspberry Pi's response and evaluate the effectiveness of the fire detection logic.

FIRE DETECTION LOGIC:

1.The flame sensor detects thermal radiation and outputs a HIGH signal (1) when a flame is present.

2.This HIGH signal triggers the buzzer and the alarm LED.

![Flame](https://github.com/user-attachments/assets/1269556a-edae-4d61-8629-0fffbe109ba4)
