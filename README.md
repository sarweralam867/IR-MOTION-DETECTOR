# IR-MOTION-DETECTOR
IR MOTION DETECTOR || Brac University || CSE251 : Electronic Devices and Circuits

Group Members:
Mitisha Tasnim Rahman (ID: 20301327)
H.M Sarwer Alam (ID: 20301224)
Shudeb Ghosh Barno (ID: 20301222)
MD. Abdullah Al Sadik (ID: 20301094)
Samia Semu (ID: 20301297)


Abstract:
This project aimed to design and build an IR motion detector, using essential electronic components such as an IR LED, photodiode, and a passive buzzer to detect motion based on light interruption. The system operates as an active detector that activates an LED and buzzer when the infrared (IR) beam is blocked, signaling motion. The circuitry includes two main parts—one controlling the LED and the other triggering the buzzer, both working in tandem. The detection is based on changes in light intensity received by the photodiode, activating the output when the beam is interrupted. This project demonstrates an affordable and practical solution for motion detection, which can be applied in various real-life applications.

Component List:

Passive Buzzer (5V)
IR Transmitter LED (3mm)
Breadboard
Infrared Photodiode (T&R 3mm)
Resistors (100 ohm, 330 ohm, 10k, 1k, 4.7k)
L7805 Voltage Regulator
9V Battery
LED (Red, 5mm)
Male-to-Male Jumper Wires
LM358 Operational Amplifier
9V Battery Connector
Capacitor (4.7uF, 50V)
C829 NPN Transistor
100k Ohm Potentiometer
Working Principle:
The IR motion detector operates on the principle of infrared radiation emitted by the IR LED and received by the photodiode. The photodiode's resistance changes with varying levels of IR radiation, which in turn affects the voltage drop across it. An operational amplifier (LM358) is used as a voltage comparator to detect these changes. When the IR beam is interrupted, the photodiode's resistance drops, causing the comparator to output a high voltage. This high voltage powers the LED and sends a signal to an astable multivibrator, generating a square wave that activates the buzzer.
