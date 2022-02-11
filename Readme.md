# VT HPS - ISR17 
## Sensor & Actuation System 

The purpose of this repository is to hold the code for sensor and actuation system for the ISR17 submarine.

## Schematic
Add pin diagram here

## Files included in this repository 

[gui.py](https://github.com/Syennagraham/ISR17/blob/main/gui.py)
Python3
Takes serial string as input and outputs the sensor system GUI.

[control_motors.ino](https://github.com/Syennagraham/ISR17/blob/main/control_motors.ino)
Arduino IDE
Controls two motors using 5 buttons. 

[HUD_data.ino](https://github.com/Syennagraham/ISR17/blob/main/HUD_data.ino)
Arduino IDE
Takes inputs from sensors (2 pressure sensors, 2 rpm sensors and 1 gyro) and outputs a serial string (00#00#00#00) for the python file (gui.py) to interpret and make a GUI with.

[gyro_simulation/MPU6050_DMP6.ino](https://github.com/Syennagraham/ISR17/blob/main/gyro_simulation/MPU6050_DMP6.ino)
Arduino IDE
Takes the input of the MPU6050 gyro to output to a GUI.

[gyro_simulation/sketch_3DGyro.pde](https://github.com/Syennagraham/ISR17/blob/main/gyro_simulation/sketch_3DGyro.pde)
Processing IDE
Provides a simulation GUI of a plane to show orientation of the gyro. 


## Helpful links
Arduino IDE - https://www.arduino.cc/en/software
Python3 download - https://www.python.org/downloads/
