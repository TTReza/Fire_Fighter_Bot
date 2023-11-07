# Fire_Fighter_Bot

The robot is powered by two 3.7-volt batteries connected in series to provide 8.4 volts
in total. These batteries are safely charged with a Battery Management System (BMS)
designed for two cells. The BMS ensures the batteries’ durability and safety by preventing
overcharging and excessive discharging. Additionally, a power switch is included for on/off
control, and a DC connector allows the robot to run directly from a 9-volt adapter or
batteries.
The robot’s brain is an Arduino UNO, which processes data from flame sensors and
manages various components. Three strategically placed flame sensors (front, back, and
left) detect the presence of flames. It should be mentioned that the distance of detecting
flame or fire can be modified physically from the Flame Sensor. Then the flame sensor
reading is sent to the input of Arduino and then it is processed to the Motor Driver and
then servo motor followed by 12V DC water pump from the Arduino outputs. The robot’s
movement is controlled by a small servo motor (SG90) to adjust its position in response
to detected flames.
To extinguish flames, a DC water pump is used, with added components like a filter
capacitor and a diode to ensure safe operation. Robot mobility is achieved using an L298
motor driver, which works in tandem with the Arduino to control DC motors’ rotation in
both directions. The motor driver’s OUT1, OUT2, OUT3, and OUT4 ports connect to
the left and rear motors, and a power connection ensures the robot receives the necessary
energy to function.
