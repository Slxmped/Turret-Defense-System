# Turret-Defense-System
Turret Defense System Project: 

![image](https://github.com/user-attachments/assets/0e96a87b-4e0b-48df-b830-0d104f2e3301) ![image](https://github.com/user-attachments/assets/baa4cca1-f83d-44e7-ad99-12588f2ff640) 

# Abstract/Summary
Turret Defense System is built for protection
(In the Arduino project that will be designed, I will be creating an automated turret system using components in the Arduino kit and other out sourced components. This is important because U.S citizens need to know that they can make basic home defense systems inside of their home and not only the government should know the technological makings behind certain systems. The problem that this will solve is the defense of homes in the U.S. If done correctly, U.S citizens who feel like their home is threatened from breaking and entering can have defense systems in place to neutralize any threat that intrudes to cause bodily harm to anyone inside of their homes. This will be useful in the defense and protection of families just in case the cops cannot show up in time as per usual. It isn’t useful for the police to show up when the victim is already harmed and incapacitated so it’s better to have an aid to help you defend you and your loved ones).

# Literature Review(Background Information)
The project for the missile defense system has been done before and people have tried to solve a similar problem. Users have used the ultrasonic sensor, Processing, and missile launchers that they have found in order to create the automated turret system. Some people have created a firing system or have found a firing system online. The best hope is to find a firing system online but if not, I may have to figure out how to build one from scratch and use it as the firing mechanism. People have solved their problem in terms of finding the correct components to create the system. People online have used nerf darts, already constructed projectile systems, or home-made devices that were assembled to launch a projectile. The devices in their projects were either separated from the ultrasonic sensor or attached in combination with the sensor and servo. I have to solve my own problem of obtaining the correct components to create a projectile launcher. In short, the servo sweeps the area with the ultra-sonic sensor, the sensor detects and object in range, and the device used to launch a projectile to a target launches the projectile at the specified target.

# Methodology
The way these software tools will be used in combination of this project is that Arduino IDE 2 will be used to create a program that will have control of a servo (Output Devices – Advanced), ultrasonic sensor (Input Sensors - Advanced), LEDs (Output Devices – Digital), aa solenoid (Output Devices - Digital) and a singular relay module. The ultrasonic sensor will be used to detect targets coming in to a certain location. When a target is detected and the automated turret system is ready to fire, this will be indicated with a projectile being launched from the turret and the flashing red LEDs indicating that the turret is firing. The Servo will be attached to a stabilized structure that will hold the housing of the turret. The ultrasonic sensor is then mounted to the servo using the housing of the turret’s head. The gun will mount the servo inside the turret’s housing head. Once a target is detected, the LEDs will indicate whether the system is shooting or in a ready state to shoot. Red flashing LED means the system is firing, and green means the system is ready to fire again. The ammo cartridge or the system I will be using will load the ammo and shoot again until the target is out of the vicinity and resume its sweep motion until another target is found. The servo will rotate the ultrasonic sensor automatically, A certain distance will be set for the sensor so every distance isn’t being shot at, and the LED’s will stay at a certain state to indicate the action. 
	
 In designing the system, many components will be connected in a format that allows communication between the systems. In the design, there will be an ultrasonic sensor. There is a wire connected from pin A0 on the Arduino to the trig of the ultrasonic sensor. The echo for the ultrasonic sensor is connected to the A1 pin on the Arduino board establishing the input and output connections of the sensor. The sensor is then connected to 5V of power from the Arduino board and grounded with the Arduino board. The ultrasonic sensor is placed in the housing of the turret's head to search for distances. Two LEDs were also connected to the Arduino board which will act as indicators of cycles between the different states. The green LEDs cathode was connected to the ground of the Arduino and the anode is connected to pin 12 on the Arduino. The cathode for the red LED is connected to the ground of the Arduino and the anode is connected to pin 13 on the Arduino board. A servo is also included into the project and in the servo connection, the ground and power make a connection to the power and ground of the Arduino board. The servo will be responsible for rotating the turret's head and allowing the ultrasonic sensor to scan the area. The pin for servo control is attached to pin 11 on the Arduino board for functionality. The final components that will be connected to the Arduino board is the solenoid that will be responsible for pulling the trigger of the turret and the relay that will be responsible for controlling the solenoid and adapting it to the 5V voltage given to the board. This will allow the turret to fire once a certain condition has been met. A 12V adapter will connect power to one of the relays ON pins and the power connection from the solenoid will be connected to one of the relays ON pins. The 12V adapter will be grounded using the ground of the solenoid. The relay voltage and ground are set to the Arduino’s voltage and ground connections on the breadboard. The control pin from the relay is set to the Arduino’s pin 10 for solenoid control. The servo sits at the base of the box at the top to hold the turrets head and the solenoid sits at the back end of the turrets head with a string around the trigger ready to pull at will. The relay is placed inside of the base of the box near the breadboard and Arduino board. 
# Section A: Physical Design
![image](https://github.com/user-attachments/assets/02b1cb86-36f0-48d7-a594-b65e21ebedf1) ![image](https://github.com/user-attachments/assets/0ee21c4b-9f6c-476e-9b2f-f00502f9264c) ![image](https://github.com/user-attachments/assets/f3f899c0-cf9e-4dff-bd71-86663cd01964)
![image](https://github.com/user-attachments/assets/1e3eac41-4b68-42aa-b8b7-ed56fe7f838f) ![image](https://github.com/user-attachments/assets/62cc79e5-64c4-4a20-87f4-2f19508a3c61) ![image](https://github.com/user-attachments/assets/6c7eec0d-86cc-4bc8-848f-ba7f54b7b558)

Designing this project required ulterior components and pieces to design the Turret Defense System. The first ulterior component needed was a cardboard box. This cardboard box was a 10.8in x 9.50in x 2.93in box that could open up like a laptop or a lunchbox. This cardboard box was spray painted black to give a bit of a professional look to the box. The next step was to cut a 1in x 1.5in space into the cardboard box at the upper left portion of the cardboard box and a 0.9in x 0.7in at the upper right of the box in order to feed wires from within the box to the components from the Arduino board. There was an Arduino board added inside of the cardboard box with a breadboard added alongside the Arduino board. There were four holes drilled into this cardboard box where the high torque servo would be added using the star mount servo attachment. The servo was attached to the star shaped mount and the holes were distanced 1.5in x 1.5in across from one another for the length of the star mount. The servo was then screwed into the cardboard box as a placeholder for the head housing for the turret. A base was then created from a 9.75in x 8.25in flat cardboard/foam like box giving a flat base layer for the dart zone nerf blaster. The dart zone automatic blaster was deconstructed to find the component that allowed the blaster to rev. The component was found to be a pushbutton which was then desoldered and replaced with a switch to keep the engine revving at all times. The head of the blaster was left off with the switch and handle that keeps the clip in place for easier adjustability. The pistol was then zip tied upside down approximately 4in x 9.5in onto the base of the foam like cardboard. The turret head was then spray painted black and utensils, green accents were spray painted to the box. The back of the box would then be cut out to interact with the inside of the turret's head without interfering with its placement. There was a 2.3in x 1.5in space placed in the box for the barrel of the gun to stick outside of the turret's head. To the top left of the turret's face, there was a 2in x 1.5in space cut to make way for the ultrasonic sensor. Centimeters below that space were two holes spaced equally for the red and green LEDs, the first hole for the green, the second for the red LEDs. The turret head was then given a 2.75in x 2in space into the top of the box making space for the ammo clip.
	
 The head of the turret was then zip tied by the four front and end corners of the box tying the flat base to the turret's head keeping the head attached. The Green LED was then wired and taped together sticking into the first hole made on the turret's face and the red LED was taped together and wired into the second hole in the box. The battery of the blaster was taped to the right of the turret's head. The ultrasonic sensor was placed in the space designated for the sensor and taped at the back of the top of the sensor's frame. A 12V solenoid of 20N of force was placed at the rate of the turret approximately 1.75in x 1.50in from the flat base and from the back of the turret with zip ties. The solenoid was fed a lead wire that would wrap around the trigger of the blaster and be tied down tightly to the other end of the box opposite to the solenoid. This completes the full setup of the physical aspect of the turret.

![image](https://github.com/user-attachments/assets/ade116a8-3b2f-472d-8ea0-5255234fbecd) ![image](https://github.com/user-attachments/assets/e29891c1-012b-450c-a2c6-9632d0492d86)

Problems & Issues: The problems and issues that followed the physical creation were the LEDs falling out of the holes drilled. This was solved by taping around the LEDs making it stay in place when being lodged into the hole. Another issue were the wires falling out of the ultrasonic sensor and LEDs which were taped to ensure they do not fall out and the wires were too short for the sensor and LEDs. These wires were lengthened so there were no more tugs and pulls onto the wires. 

# Section B: Electrical Design  
In the electric design of the turret defense system, there were many components connected and wired together. The following images below are the electric schematic diagrams and wiring of the turret defense system:  
![image](https://github.com/user-attachments/assets/bbceadda-befd-4e4c-9651-cecc65660ec1) ![image](https://github.com/user-attachments/assets/d35d35e6-365d-4432-89f5-aa6067d2894a) ![image](https://github.com/user-attachments/assets/c9594fbb-8b1e-4cc7-96db-20cde82c5d33)



In the circuit, starting with the first connection made were the LEDs. The green LED was connected to the Arduino board’s pin 12 by the Anode. The green LED was also connected to the ground of the 5V circuit for troubleshooting purposes. Another green LED was connected to the circuit’s 330 Ohm resistor by the Anode to regulate the flow of the electric circuit and gets connected to the same ground by the cathode. A red LED was also connected in similar fashion with the Anode being connected to pin 13 on the Arduino’s board and grounded to the 5V circuit’s ground. Another red LED is connected by the Anode to another 330 Ohm resistor and grounded to the same ground as the previous red LED. This will give full functionality to the green and red LED to be controlled and operational. A servo is then added into the design connecting the servo to the 5V power and the ground of the servo to the ground of the 5V circuit. The servos control pin was connected to pin 11 on the Arduino board for full servo control. There were two wires across the bread board, one connecting to power and one connecting ground to establish power across the entire breadboard. An HC-SR04 ultrasonic sensor was introduced into the setting which first connects the power of the ultrasonic sensor to the 5-voltage supply from the Arduino. The ground also gets connected to the 5-voltage ground from the Arduino. The trig pin gets connected to the analog sensors on the Arduino board connecting to pin A0 on the Arduino board. The echo pin gets connected to the analog A1 pin on the Arduino board. A solenoid, a 5V relay, and a 12V adapter is then introduced into the setting. The solenoid is a 20N of force solenoid and this solenoid has several connections. The solenoid's power connects to the normally open connection on the 5V relay and the ground of the solenoid is connected to the ground of the 12V adapter. The power of the 12V adapter is connected to the normally open connection on the middle relay module. The relay module allows the 12V adapter to interact with the 5V circuit without overheating or disrupting the circuit’s flow. The relay's power connector connects to the 5V power from the Arduino and the ground from the relay is connected to the ground from the Arduino. The relay and solenoid control pin is connected to pin 10 on the Arduino board for full relay and solenoid control. This completes the electrical design of the circuit

# Embedded controller: 

The Arduino Mega 2560 is a microcontroller that is heavily based on the ATmega2560 AVR microcontroller. The microcontroller has 70 digital input/output pins. Each set of pins has their own unique function. There are 14 pins that can be used as PWM outputs and 16 can be used as analog inputs. There is an in-circuit system programming header, reset button, power jack, 16MHz resonator, and a USB connection. The Arduino just needs a usb cable or power adapter to get started. The Mega 2560 is different from the previous board as it does not use FTDI USB-to-Serial driver chips and uses Atmega8U2 programmed as a USB-to-Serial converter. The Mega 2560 has its own USB bootloader, which allows advanced users to reprogram it.

•	Microcontroller: ATmega2560

•	EEPROM: 4 KB

•	DC current per I/O pin: 40mA

•	DC current for 3.3V pin: 50mA 

•	Flash memory: 256 KB (8KB being the bootloader)

•	SRAM: 8KB

•	Clock speed: 16MHz

•	Operating voltage: 5V

•	Input voltage: 7V-12V

•	Digital I/O pins: 70 (14 PWM)

•	Analog input pins: 16

 # Input Sensors: 
 
 The ultrasonic ranging module (HC-SR04) gives a 2cm - 400cm non-contact measurement function. This accuracy can reach to 3mm. This module includes ultrasonic transmitters, receiver and control. The IO trigger is used for at least 10us high level signals. The module will automatically send eight 40kHz and detect a pulse that is sent back to the sensor. If the signal that returns is through high level, time of high output I/O duration is the time from sending ultrasonic to return, the test distance will be equal to high level time * velocity * sound) (340M/S)/2. The SRF04 requires a short trigger pulse and provides an echo pulse. The controller has the time length of this pulse to find the range. There is a 5V supply, echo pulse output, trigger pulse input, and a ground. After a short 10us pulse is sent to the trigger input, an 8-cycle burst of ultrasound is sent at 40kHz. The sensor then listens for an echo and as soon as an echo is detected, it lowers the line again. The echo line is a pulse that has a width proportional to the distance of the object. If nothing is detected, the SRF04 will lower its echo line anyway to about 36mS. To calculate the distance, the sensor provides a pulse proportional to the distance. If the width of the pulse is measured in uS, then dividing by 58 will give you the distance in cm, or dividing by 148 will give the distance in inches. uS/58 =  cm or uS/148 = inches.  

•	Working voltage: 5VDC

•	Static current: Less than 2mA

•	Output signal: Electric frequency signal, high level 5V, low level 0V.

•	Sensor angle: Not more than 15 degrees

•	Detection distance: 2cm-450cm

•	High precision: Up to 0.3cm

•	Input trigger signal: 10us TTL impulse

•	Echo signal: output TTL PWL signal

•	Mode of connection: VCC, trig, echo, and GND   
	
 # Output Actuators and Devices

Servo: A servo is a small device that uses a potentiometer, a three wire DC motor, a gear train, a potentiometer, an integrated circuit, and an output shaft bearing. One wire is for power, one is for ground, and one is the control input line. The shaft can be positioned in specific angular positions by sending signals to the servo. The coded signal will help maintain the angular position of the shaft. If the code changes then the angular position of the shaft changes. Servos work with voltages between 4 and 6 volts. The potentiometer allows the control circuitry to monitor the current angle of the servo motor. The motor will turn to the correct direction if the control of the circuit detects that the position is not correct. A servo is used to control the motion between 0 and 180 degrees. It is unable to turn further due to the mechanical build that stops the servo once the main gear detects an excessive angle. The power applied to the motor is proportional to the distance it needs to travel. The motor will move at full speed if the shaft needs to move at a great distance and slower speeds means less power from the motor. Servos can be used in RC cars, robots, puppets, and planes. The gears differ from different servos. Cheaper servos usually have plastic gears while expensive servos have metal gears. The functionality is relatively the same between servos. In this project, the torque of the servo is essential as the weight of the housing for the turret is exceptionally higher than a standard mini servo. The torque is the maximum power the servo can produce. A torque of rating 130 can move slightly over 8lbs. A larger servo with a metal gear and higher torque was used. 

•	Operating Voltage Range: 4.8V - 6.8V

•	Operating speed (5.0V): 0.15 sec/60 degree

•	Operating speed (6.8V): 0.13 sec/60 degree

•	Stall torque (5.0V): 21kg/cm

•	Stall torque (6.8V): 25kg/cm

•	Control System: PWM (Pulse Width modification)

•	Pulse Width range: 500-2500 Usec

•	Neutral position: 1500 Usec

•	Running degre: 180 degrees (when 500-2500 Usec)

•	Dead Band Width: 3Usec

•	Operating frequency: 50-330Hz

•	Rotating direction: Counterclockwise (when 500~2500Usec)

•	Gear ratio: 275

•	Bearing: Double bearing

•	Connector wire: 17.7 inches

•	Motor: 3-pole(s)

•	Waterproof performance: I966

# Input and Output interface circuits
	
 Relay Module: A relay module is a circuit board that is home to one or more relays. Relay modules can come with 2-8 relays mounted and going as high as 16. Relay modules can have transistors, resistors, protection diodes, LEDs, and more parts. The relay module is an electrical switch that can be used to control systems and devices that have higher voltage ratings. In the case of this project, the relay needed to control 12V from the adapter and convert it to a safe 5V for the Arduino. The relay module, similar to the solenoid, has an electromagnetic make to it. The input voltage for the relay is usually DC but with an electrical load, it can be changed to AC within limits of the relay.  Relays can go from 3.2V-24V. The purpose is to switch electrical devices on and off and isolate the control circuit from the device or system being controlled. Relay modules can make the control signal stronger using small power from a microcontroller. Relay modules have normally open or normally closed switches. The normally open switch is only open when the electromagnet is not active and closed when it is active. The normally closed switch remains closed and only opens when the relay is active. This is where the pin connection from the solenoid and adapter connects. Things to look out for when choosing a relay: Relays may show voltage as high as 250 volts with current of 15 amps. It is recommended to use voltages of 12V and currents of 1A or lower.

•	Normal Voltage: 5V DC

•	Normal Current: 70mA

•	AC load current: Max is 10A at 125V AC or 250V AC

•	Release time: 5msec

•	Maximum switching: 300 operating per minute

•	Operating time: 10msec

•	Includes: 5-pins & designed with plastic material

•	DC load current Max is 10A at 30V DC or 28V DC

•	Voltage Supply ranges: 3.75V-6V

•	Quiescent current: 2mA

# LEDs: 

LEDs (Light Emitting Diodes) are bulbed shaped diodes that emit light depending on the color type of the LED chosen. LEDs have two wires; one connects the Anode which is the positive connection and the cathode which is the ground connection. Electronic parts that move in one direction similar to this fashion are called Diodes. The longer lead of the LED connects to the positive voltage and the shorter lead is cathode and connects to the ground. There are 5mm LEDs, 3mm LEDs, and 10mm LEDs. LEDs are used for illumination and indication. In this project it is solely used for indication primarily and illumination secondarily. The LED is used to indicate the change in states and operation of the turret defense system. LEDs have a milli-candela rating to determine how bright the LED will be. The brightness of an LED can be changed with resistors, the larger the resistor the dimmer the LED will become. A smaller resistor however makes for a brighter LED. The LED brightness can also be changed using the voltage. The higher the voltage, the brighter the LED.

# LED Colors & Voltage Ratings
![image](https://github.com/user-attachments/assets/12d2c4c9-82dd-4b0b-a81f-e6c5cc71ca12)

# Solenoid:
	Solenoid: Push/Pull solenoids are linear solenoids are on/off Actuators that create a force in one direction and reverse the force using a return spring. A solenoid is made out of a copper wire coil which is fastened tightly into a helix, a mobile plunger, and iron or steel housing. These linear solenoids have a very high holding force with very little power consumption. The solenoids can be used for heavy duty applications such as doors, drive rollers, lift mechanisms, friction brakes, pen plotters, and pen lifts. When a solenoid coil is energized, magnetic Flux moves between the fixed pole piece and plunger. The magnetism is brought together whether the polarity is different or not for the energizing current. The pull type solenoid comes from the incorporation of a pushrod attachment to the plunger that passes through the pole piece. The push/pull solenoid is designed for mechanical means to connect an armature or pull end and the base or push end of a certain device.
 
•	Solenoid Voltage: 12V

•	Solenoid Force: 20N

•	Solenoid Type: Push/Pull

•	Stroke: 10mm

•	Frame type: Open Frame

•	Solenoid Magnetism: Electromagnetic

Below are diagrams of the solenoid’s stroke based on the force applied, response time, and duty cycles based on resistance values and voltage in DC.







