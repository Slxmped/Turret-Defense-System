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

![image](https://github.com/user-attachments/assets/a4e21cba-7b33-44f6-8f00-28380759c1a4)

# Data communication and network interface
	
USB port: The USB port serves its function as the primary communication between the Arduino board and the PC. The Arduino is connected via external connection from the Arduino to the PC using a USB cable. This allows the board to send and receive signals for programming and also applies power to the Arduino board. The voltage applied from the PC meets the standard 5V requirement from the Arduino board. The USB is known as a high-level data communication subsystem

![image](https://github.com/user-attachments/assets/ce1a0876-1927-4158-a25b-8aac1c8c82ed)

Power supply system: The power supply systems that were used in the project was the Arduino power supply of 5V from the PC connection and a 12V power supply adapter. In this project, a few components were powered by the USB connection and a few components were powered by the 12V voltage adapter. Most of the Arduino components such as the servo, ultrasonic sensor, and LEDs were powered by the default 5V from the USB connection. The solenoid and relay are powered from the 12V voltage adapter using a connection that separates the power and ground connections. The solenoid has a connection to the relay and the adapter has a connector to the relay. This relay then allows the 12V power supply to be compatible with the 5V Arduino circuit allowing full control.

# Section C: Software Design

In the design for the program, there were several steps and plans that had to be laid out and followed for this system to work. The following flowchart outlines all of the programming steps and procedures that needed to be done to create the program:

![image](https://github.com/user-attachments/assets/abf7f317-4772-498b-9d93-6aecfa6fba00)

In short, the first segment of the flowchart is where global variables get assigned to the program. These variables setup the state machine, the components, and create holder variables for certain functionalities in the circuit. There are functions being opened and state machine variables being created. In the next portion of the chart is the setup statement which contains the components being initialized and setup to perform certain functions like the pin modes being changed to input and output, the servo and sensor being setup, and communications being setup for the serial monitor. The third is where the distance variable gets created using the ultrasonic sensor. This is setting up the calculations and the different pin interactions for the setup of the ultrasonic sensors distance detection to be setup. The next part further completes the setup of the get distance function by returning the inches and centimeters for distance detection. The next two parts are the two if conditions being checked for. In one condition, this detects for the first state and the next detects for the second state. Depending on which state is chosen, the next part chooses which state’s criteria has been met. Depending on the criteria that has been met, either the first function or second function is applied to the scenario thus completing the flow chart. 

#include <FiniteStateMachine.h>

#include <Servo.h>

const int pingTrig = A0;

const int pingEcho = A1;

const int SOLENOID = 10;

const byte NUMBER_OF_STATES = 2;

long distance = 0; // Holds variable for distance  

int count = 0;

int count2 = 0;

Servo myservo;
void One_fn();
void Two_fn();


// Initialize states

State One = State(One_fn);

State Two = State(Two_fn);

FSM CET_Turret_State = FSM(One); // Initialize state machine, start in state: One

#define ledRed 13

#define ledGreen 12

int pos = 1500;  // Starting position for the servo (centered)

int lastServoPosition = 1500;  // Remember the last position

int sweepDirection = 1;  // 1 for forward, -1 for backward

int stepSize = 100;  // Increment/decrement for servo movement

unsigned long previousMillis = 0;  // Timing for servo movement

const long interval = 20;  // Interval for non-blocking servo update (in ms)

void setup() {
  
  // Initialize serial communication
  
  Serial.begin(9600);
  
  pinMode(SOLENOID, OUTPUT);
  
  pinMode(ledRed, OUTPUT);
  
  pinMode(ledGreen, OUTPUT);

  myservo.attach(11);  // Servo control on pin 11

  // Initialize sensor pins
  
  pinMode(pingTrig, OUTPUT); // change A0 pin mode to digital output
  
  pinMode(pingEcho, INPUT);  // change A1 pin mode to digital input

}



void getDistance() {
  long duration, inches, cm;

  // The HC-SR04 is triggered by a HIGH pulse of 2 or more microseconds.
 
  // Give a short LOW pulse beforehand to ensure a clean HIGH pulse
  
  digitalWrite(pingTrig, LOW);
  
  delayMicroseconds(5);
  
  digitalWrite(pingTrig, HIGH);
 
  delayMicroseconds(10);
 
  digitalWrite(pingTrig, LOW);

  duration = pulseIn(pingEcho, HIGH);
  
  distance = (duration / 2) / 29.1;

  // Convert the time into a distance
 
  inches = microsecondsToInches(duration);
 
  cm = microsecondsToCentimeters(duration);
 
  inches = constrain(inches, 100, 150);

  Serial.print(inches);
 
  Serial.print("in, ");
  
  Serial.print(cm);
  
  Serial.print("cm");
  
  Serial.println();

  delay(100);  // Small delay to prevent overwhelming the serial output

 
}

long microsecondsToInches(long microseconds) {
  
  return microseconds / 74 / 2;

}

long microsecondsToCentimeters(long microseconds) {
  
  return microseconds / 29 / 2;
  
}

void loop() {
  
  // Main code to run repeatedly
  
  getDistance();

  int currentState;

  // Check the condition to switch states
  
  if (distance > 130) {
    
    currentState = 0;
    
    count = 0;

  } else if (distance <= 100)  {
  
    count +=1;
    
    if (count > 1){
      
      currentState = 1;
    
    }
   
  }

  // State transitions based on distance
  
  switch (currentState) {
    
    case 0:
      
      CET_Turret_State.transitionTo(One);
      
      break;
    
    case 1:
      
      CET_Turret_State.transitionTo(Two);
     
      break;
      
  }

  // Update the state machine
 
  CET_Turret_State.update();
  
}

void One_fn() {
  
  digitalWrite(ledGreen, HIGH);
  
  digitalWrite(SOLENOID, LOW);
  
  digitalWrite(ledRed, LOW);

  unsigned long currentMillis = millis();

  // Non-blocking update every interval (e.g., every 20ms)
 
  if (currentMillis - previousMillis >= interval) {
    
    previousMillis = currentMillis;

    
    // Update servo position non-blocking
    
    pos += sweepDirection * stepSize;

    // Reverse direction at limits
    
    if (pos >= 2500 || pos <= 500) {
      
      sweepDirection = -sweepDirection;
    
    }

    // Set the servo position
    
    myservo.writeMicroseconds(pos);
    
  }
  
}

void Two_fn() {
  
  myservo.writeMicroseconds(pos);  // Keep servo at the current position
  
  digitalWrite(ledGreen, LOW);
  
  digitalWrite(SOLENOID, HIGH);
  
  digitalWrite(ledRed, HIGH);
  
  delay(50);  // Toggle LED for visual feedback
  
  digitalWrite(ledRed, LOW);
  
  delay(50);
  
} 


 # Source Code Analysis:
 
•	#include <FiniteStateMachine.h> and #include <servo.h> includes the finite state machine library and the servo library into the program.

•	const int pingTrig = A0; sets the trig pin to analog pin 0 from the ultrasonic sensor to the arduino. Const int ping echo = A1; sets the echo pin from the sensor to analog pin 1 on the arduino.

•	const int solenoid = 10; Sets the solenoid to be connected to pin 10 on the Arduino board.

•	const byte Number_OF_STATES = 2; create two different states for the finite state machine.

•	long distance = 0; holds the variable for distance for the finite state machine. When this changes, based on the condition states will change.

•	int count = 0; is the false positive variable holder, if the turret happens to glitch out because of the sensor it will bypass any false positive detections until it is constant.

•	int count2 = 0; Is another variable created to detect false positives.

•	Servo myservo; Attaches the servo object to the variable myservo for further use.

•	void One_fn() creates a variable that calls the function into place and activates it for its definition later in the program.

•	void Two_fn() also creates another variable that calls the function into place and activates it for state two function definition later.

•	State One = State(One_fn); initializes the first state and State Two = State(two_fn) initializes the second function.

•	FSM CET_Turret_State = FSM(One) initializes the state machine to start at state one.

•	#define ledRed 13 assigns the red LED to pin 13 and #define ledGreen 12 assigns the green LED to pin 12 on the Arduino.

•	int pos = 1500; sets the starting position for the servo to be centered.

•	int lastServoPosition = 1500; remembers the last servo position to be referred to.

•	int SweepDirection = 1; sets the sweep direction for the Servo.

•	int stepSize = 100; adjusts the speed of the servo when sweeping. The higher the step size the faster.

•	unsigned long previousMillis = 0; creates a timer for the servo’s movement.

•	const long interval = 20; creates a non-blocking interval which allows the servo to perform other tasks while waiting for the update to complete. Updates every 20ms.

•	void setup(){ is where certain variables get initialized to perform a task.

•	serial.begin(9600); establishes communication to the serial monitor.

•	pinMode(SOLENOID, OUTPUT); establishes the solenoid to be an output.

•	pinMode(ledRed, OUPTUT); establishes the red LED to be an output.

•	pinMode(ledGreen, OUTPUT); establishes the green LED to be an output.

•	myservo.attach(11); attaches the servo to pin 11 on the Arduino board.

•	pinMode(pingTrig, OUTPUT); sets the trig pin on the ultrasonic sensor to an OUTPUT since it will send out signals.

•	pinMode(pingEcho, INPUT); sets the echo pin to an INPUT since it receives signals.

•	void getDistance(){ creates a variable that will obtain the distance for the ultrasonic sensor.

•	long duration, inches, cm; creates variables for the ultrasonic sensor to use for setting each measurement requirement.

•	digitalWrite(pingTrig, LOW); sets the trig pin to low meaning it is in an off state.

•	delayMicroseconds(5); delays the next process by 5 microseconds.

•	digitalWrite(pingTrig, HIGH) allows the trig pin to be high and activates it on the sensor.

•	delayMicroseconds(10); allows for a 10 microsecond delay before the next process.

•	digitalWrite(pingTrig, LOW); writes the trig pin low once again.

•	duration = pulseIn(PingEcho, HIGH) writes the echo ping high. This entire process allows the ultrasonic sensor to send a receive signals.

•	distance = (duration /2) /29.1; calculates the ultrasonic sensors distance detection based on the duration.

•	inches = microsecondsToInches(duration); Converts the time of microseconds to inches and attaches this to the duration of the sensor.

•	cm = microscondsToCentimeters(duration); applies the previous logic but for a centimeter conversion.

•	inches = constrain(inches, 100, 150); contrains the inches to remain in between 100, 150.

•	serial.print(inches); will print the value in inches to the serial monitor.

•	serial.print(“in, “); will print “in” next to the inches value.

•	serial.print(cm); will print the centimeter value.

•	serial.print(“cm”); will print “cm” next to the centimeter value.

•	serial.println(); will print another line to give space between values.

•	delay(100); will give a small delay of 100ms.

•	long microsecondsToInches(long microseconds){ will create a variable for microsecondsToInches and attach it to microseconds.

•	return microseconds /74/2; will return microseconds for inches through calculation.

•	long micorsecondsToCentimeters(long microseconds) { creates a variable for microsecondsToCentimeters and attaches it to microseconds.

•	return microseconds /29/2; returns the calculation for centimeters in microseconds.

•	void loop() { creates the function that will run repeatedly though the code.

•	getDistance(); calls the get distance function into the main code space.

•	if (distance > 130) { currentState = 0; count = 0; this if statement will detect that if the distance is greater then 130 the turret will remain in state 0 and the count will not increase.

•	else if (distance <= 100) { count += 1;  if the distance is less than 100 for the sensor, the count will start to increase.

•	if (count > 1){ currentState = 1; if the count is greater than 1 then the state will change to state 1 counting the false positives.

•	Switch (currentState) { creates a switch case statement.

•	case 0: CET_Turret_State.transitionTo(One); assigns the case to be state One for when state machine has to transition to state one.
•	break; breaks the case statement made.

•	case 1: CET_Turret_State.transitionTo(Two); assigns the state to be State 2 for when the state machine has to transition to state two.

•	break; ends the case statement made.

•	CET_Turret_State.update(); will update the turret state.

•	void One_fn() { creates the function that will be responsible for how state one behaves.

•	digitalWrite(ledGreen, HIGH); Turns the green LED on.

•	digitalWrite(SOLENOID, LOW); Turns the solenoid off.

•	digitalWrite(ledRed, LOW); Turns the red LED off.

•	unsigned long currentMillis = millis(); creates a variable for current millis and attaches the millis object.

•	if (currentMillis – previousMillis >= interval) {  previousMillis = currentMillis; creates an if statement that if the current milliseconds minus the previous milliseconds is greater than or equal to the interval value, then the previous millis will be equal to the currentMillis.

•	pos += sweepDirection * stepSize; which is the servo position will be updated to be the sweep direction * stepsize which updates the motor speed.

•	if (pos >= 2500 I I pos <= 500) { sweepDirection = -sweepDirection; will create if statement that if the servo position is at its max reading or lowest reading, the sweep direction will be reversed at its limits.

•	myservo.writeMicroseconds(pos) will write the microseconds to the variable pos to set the servo position.

•	void Two_fn() { creates a function for the second state’s operation.

•	myservo.writeMicroseconds(pos); keeps the servo at the current position its moved to.

•	digitalwrite(ledGreen, LOW); writes the green LED to be low and turn off.

•	digitalwrite(SOLENOID, HIGH); turns the solenoid on.

•	digitalWrite(ledRed, HIGH); writes the LED to be turned on.

•	delay(50); gives the system a 50ms delay.

•	digitalWrite(ledRed, LOW); turns the red LED off once again.

•	delay(50); gives a 50ms delay making the red LED flash.

Problems & Issues: Writing the program was relatively intermediate as there were simpler parts to writing the program and difficult parts. The simpler parts were defining variables, setting up the sensor and other components, and setting up a few logical statements. There however were difficult parts to logical statements in the program such as, how I was going to make the servo stop once the sensor detects motion and shoot. Initially the servo would complete a whole cycle then it would stop and shoot which isn’t how the system is supposed to work. It is supposed to stop and shoot upon detection of an object. The solution to that was modifying the program in a way where the limits of the servo could be disrupted before it makes its full sweep. This was done by creating the pos variable in combination with an OR statements and the limits of how far the servo would turn and the non-blocking interval arranged. This would then update in the next function that sets the servo to stop at the current position where an object is detected based on the statements written.

