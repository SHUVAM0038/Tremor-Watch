# **PROJECT NAME** : Tremor Watch



&nbsp;i) **Problem Statement**

Unexpected earthquakes can cause severe damage before people have time to react. This project aims to detect ground tremors early and provide an immediate audible and visual alarm to help safeguard lives and property.



&nbsp;ii) **Scope of the Solution**

\- Detect low-level vibrations using an accelerometer (e.g., ADXL335).

\- Provide real-time alert via buzzer, LED, and 16×2 LCD.

\- Optionally log and display seismic activity graphically on a computer using Processing IDE.

\- Modular enough to use tilt sensors (KY‑002) for cost‑effective versions.



&nbsp;iii) **Required Components**

\- IDE \& Software:

&nbsp; - Arduino IDE

&nbsp; - (Optional) Processing IDE for seismic graph

\- Hardware:

&nbsp; - Arduino UNO

&nbsp; - Tilt Sensor

&nbsp; - 16×2 LCD (or OLED)

&nbsp; - Buzzer (driven via BC547 transistor)

&nbsp; - LED + resistors

&nbsp; - 10 k potentiometer for LCD contrast

&nbsp; - Power supply (9–12 V)

&nbsp; - Breadboard and jumper wires



iv)  **Results of the Project**

-The system successfully detects tilt or vibration events simulating minor seismic activity using the tilt sensor.

-When vibrations exceed the set threshold (e.g., a shake or tilt), the buzzer and LED are instantly activated, providing both sound and visual alerts.

-The 16×2 LCD displays the real-time status, confirming detection of motion with a warning message like "EARTHQUAKE DETECTED".

-During periods of no vibration, the system remains idle while continuously monitoring for tremors.

-In simulation (TinkerCad/Fritzing) and physical testing, the system showed reliable responsiveness and minimal false triggering under normal conditions.

-The use of simple, low-cost components ensures affordability and adaptability for educational and safety purposes.







