Line Following Robot

A basic two-sensor Line Following Robot LFR built with Arduino UNO and L298N Motor Driver. The robot follows a black track on a light surface using infrared IR sensors and a differential drive mechanism for sharp turning.

Hardware Requirements
 Arduino UNO
 L298N / L293D Motor Driver
 IR Sensor Modules 2x
 BO Motors with Wheels 2x
Robot Chassis
 7.4V / 12V Battery Pack
 Jumper Wires

Circuit Connections

Sensor Connections
 Left IR Sensor Out: Arduino Pin 2
 Right IR Sensor Out: Arduino Pin 3

Motor Driver Connections
 Left Motor Forward IN1: Arduino Pin 8
Left Motor Backward IN2: Arduino Pin 9
 Right Motor Forward IN3: Arduino Pin 10
 Right Motor Backward IN4: Arduino Pin 11


How It Works
Both sensors on WHITE surface: Robot moves forward.
  Left sensor detects BLACK line: Robot turns right to realign.
  Right sensor detects BLACK line: Robot turns left to realign.
  Both sensors detect BLACK line: Robot stops.


How to Upload
1. Open the .ino file in Arduino IDE.
2. Select Arduino Uno under Tools -> Board.
3. Select your connected COM Port.
4. Click Upload.
