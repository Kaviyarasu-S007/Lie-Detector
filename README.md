# Lie Detector with Arduino

## Step 1: How it Works

Our skin, with its amazing properties, plays a crucial role in this lie detector project. We leverage Electrodermal Activity (EDA), where the skin's conductivity changes based on various factors, including mood. To begin, connect the Arduino to the subject and link it to a computer with graphing software. Initial questions like "What is your name?" and "Where do you live?" establish a baseline for truthful responses. Subsequent questions aim to detect lies by observing changes in the established baseline.


## Step 2: Parts List

Gather the following components:
- Arduino Nano
- Velcro
- 2K Resistors
- LEDs (Red, Orange, Green)
- Basic tools: cardboard, foil, hot-glue, soldering iron, craft knife

## Step 3: Wiring

Follow these simple wiring instructions:
1. Connect a long cable to Arduino analog pin 0.
2. Connect a 2K resistor to ground and the extended analog 0 pin.
3. Connect a long cable to Arduino's 5-volt pin.
4. Connect the green LED's anode (long leg) to pin 2 and the cathode (short leg) to ground.
5. Connect the orange LED's anode to pin 3 and the cathode to ground.
6. Connect the red LED's anode to pin 4 and the cathode to ground.

## Step 4: Software and Code

Utilize the latest Arduino IDE version for the real-time graphing feature. Navigate to the tools menu to find the plotter. The code for the microcontroller is provided in the code section below. Copy and upload it to your board.
![image](https://github.com/Kaviyarasu-S007/Lie-Detector/assets/151661034/90918038-81ca-4701-97b8-3697b22ccdbf)
![image](https://github.com/Kaviyarasu-S007/Lie-Detector/assets/151661034/668dad73-6a73-4a8e-b2b4-d4ce3c0a98e1)



## Step 5: Making the Finger Clips

Enhance user experience by adding finger clips:
1. Glue a strip of tin foil to the bottom of both the hook and loop sides of Velcro.
2. Wrap the Velcro around your finger tightly, securing a stable connection.
3. Tape the exposed wire from analog pin 0 to the tin foil, ensuring a good connection.
4. Repeat the process for the 5-volt pin.

Reference : https://projecthub.arduino.cc/BuildItDR/arduino-lie-detector-41f703
