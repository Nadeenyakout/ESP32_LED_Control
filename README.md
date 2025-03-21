📌 ESP32 LED Control Project
Objective
This project demonstrates basic hardware programming with ESP32 for controlling LEDs using different methods, including blinking, fading, push-button control, and LDR-based control. Each task includes source code, circuit schematics, video demonstrations, and detailed reports.

📂 Repository Structure
lua
Copy
Edit
ESP32_LED_Control/
│-- README.md  (Project overview and instructions)
│-- Task_1_Blinking_LED/
│   │-- Blinking_LED.ino
│   │-- Circuit_Diagram.png
│   │-- Demo_Video.mp4
│   │-- Report.pdf
│
│-- Task_2_Fading_LED/
│   │-- Fading_LED.ino
│   │-- Circuit_Diagram.png
│   │-- Demo_Video.mp4
│   │-- Report.pdf
│
│-- Task_3_Push_Button_LED/
│   │-- Push_Button_LED.ino
│   │-- Circuit_Diagram.png
│   │-- Demo_Video.mp4
│   │-- Report.pdf
│
│-- Task_4_LDR_Controlled_LED/
│   │-- LDR_Controlled_LED.ino
│   │-- Circuit_Diagram.png
│   │-- Demo_Video.mp4
│   │-- Report.pdf
Each task folder contains:

Source code (.ino file) – Arduino code for ESP32.
Circuit diagram (.png file) – Schematic representation of the hardware setup.
Video demonstration (.mp4 file) – A recorded demonstration of the working project.
Report (.pdf file) – A detailed explanation of the implementation and observations.
🚀 Tasks Overview
Task 1: Blinking LED on ESP32
📌 Description:
Control an LED to blink at regular intervals using ESP32. This involves setting up the ESP32 with the Arduino IDE, wiring an LED through a 330-ohm resistor, and programming it to turn on and off repeatedly.

🔧 Requirements:

ESP32, LED, 330-ohm resistor, Breadboard, Jumper wires
📂 Deliverables:

Blinking_LED.ino
Circuit_Diagram.png
Demo_Video.mp4
Report.pdf
Task 2: Fading LED on ESP32
📌 Description:
Use PWM (Pulse Width Modulation) to gradually change the brightness of an LED using ESP32.

🔧 Requirements:

ESP32, LED, 330-ohm resistor, Breadboard, Jumper wires
📂 Deliverables:

Fading_LED.ino
Circuit_Diagram.png
Demo_Video.mp4
Report.pdf
Task 3: Push Button Controlled LED on ESP32
📌 Description:
Use a push button to control an LED. The LED will turn ON when the button is pressed and OFF when released.

🔧 Requirements:

ESP32, LED, Push button, 330-ohm resistor, 10k-ohm resistor, Breadboard, Jumper wires
📂 Deliverables:

Push_Button_LED.ino
Circuit_Diagram.png
Demo_Video.mp4
Report.pdf
Task 4: LDR Light Sensor Controlled LED on ESP32
📌 Description:
Use an LDR (Light Dependent Resistor) to detect ambient light levels and turn on an LED when it gets dark. The circuit includes an LDR with a voltage divider, connected to ESP32 for light-based automation.

🔧 Requirements:

ESP32, LED, LDR, 330-ohm resistor, 10k-ohm resistor, Breadboard, Jumper wires
📂 Deliverables:

LDR_Controlled_LED.ino
Circuit_Diagram.png
Demo_Video.mp4
Report.pdf
🛠 How to Use This Project
Clone the repository to your local system:
bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/ESP32_LED_Control.git
Open the .ino files in Arduino IDE or PlatformIO (VS Code).
Connect your ESP32 board to your computer.
Upload the code to the ESP32.
Assemble the circuit based on the provided diagrams.
Run the project and observe the LED behavior.
