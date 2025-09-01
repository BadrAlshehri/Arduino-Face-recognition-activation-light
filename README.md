Arduino Face Recognition Activation Light

This project shows how to connect computer vision with simple hardware control. Using OpenCV, the camera scans the frame for faces, and when one is detected, the Arduino switches an LED on. As soon as the face leaves the frame, the LED turns off.

The setup is straightforward: the LED is connected to pin 9 on the Arduino through a 220Ω resistor, with the cathode wired to GND. After wiring the circuit and running the code, a camera window will open to confirm detection is active, and the LED will respond and turn on in real time to any face that appears.

copy and paste the Python code provided into VS code or any IDE you prefer, and the arduino code provided into the Arduino IDE and all should work great.
