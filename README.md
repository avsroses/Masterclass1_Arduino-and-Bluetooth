# Arduino and Bluetooth

## Hardware

- Arduino UNO R4 Board
- DFRobot Gravity: 130 DC Motor Module
- Button component for Arduino
- Potentiometer component for Arduino
  
## Software

- Arduino IDE
- LightBlue app on mobile phone

## Explanation

**ArduinoBLE_LED_example** contains the code for turning an LED on or off from a mobile device connected over Bluetooth. It takes in any value and if that isn't zero turns the light on.    

**BLUETOOTH_MOTOR** contains the code for making a motor spin at different speeds, controlled from a mobile device over Bluetooth.  
can be seen in [Video 1](https://github.com/avsroses/Masterclass1_Arduino-and-Bluetooth/blob/a8d8a3c88418d8e31f6567ccaf9e1874ea655a51/Video_examples/example_1.mp4)

**Bluetooth_motor_Button_press** contains the code for making a motor spin when a button is pressed. The button is connected to another Arduino and the two are linked by Bluetooth to interact.   
can be seen in [Video 4](https://github.com/avsroses/Masterclass1_Arduino-and-Bluetooth/blob/a8d8a3c88418d8e31f6567ccaf9e1874ea655a51/Video_examples/example_4.mp4)   

**Bluetooth_motor_Potentiometer** contains the code for making a motor spin at different speeds based on a potentiometer connected to another Arduino and the two are linked by Bluetooth.    
can be seen in [Video 2](https://github.com/avsroses/Masterclass1_Arduino-and-Bluetooth/blob/a8d8a3c88418d8e31f6567ccaf9e1874ea655a51/Video_examples/example_2.mp4) and [Video 3](https://github.com/avsroses/Masterclass1_Arduino-and-Bluetooth/blob/a8d8a3c88418d8e31f6567ccaf9e1874ea655a51/Video_examples/example_3.mp4)

All the codes that communicate with each other do so by sharing the same UUID number. This method can be used to have one central Arduino and many peripheral Arduinos, doing different things. 
