# Distance Measurement Using Arduino & HC-SR04 Ultrasonic Sensor:

* In this project, we are going to interface Ultrasonic sensor HC-SR04 with ATMEGA328P and LCD Display.
* The ultrasonic sensor is used to measure the distance.
* It acts as a Sonar.
* It sends an ultrasonic wave of a certain frequency that comes back after hitting the object and calculates the time traveled by it.
* So let’s learn about Distance Measurement Using ATMEGA 328P & HC-SR04 Ultrasonic Sensor.

## COMPONENTS USED:

1. ATMEGA328P
2. Ultrasonic Sesnor HC-SR04
3. 16*2 LCD Display
4. Breadboard
5. Connecting Wires
6. 5V Power Supply

## FEATURES:

Ultrasonic sensors emit short, high-frequency sound pulses at regular intervals. These propagate in the air at the velocity of sound. If they strike an object, then they are reflected back as echo signals to the sensor, which itself computes the distance to the target based on the time-span between emitting the signal and receiving the echo.

We will have to convert this time into cm to calculate the distance traveled. We will use the following equation to calculate the distance.

                                               S = v * t
                                               
 The ultrasonic wave is basically a sound wave that travels at a speed of 340 m/s (0.034 cm/s). The ultrasonic sensor is measuring the time it takes to hit the object and then come back but we need only time that it takes to hit the object. So, we will divide it by 2.
                                           
                                           S = (t * 0.034)/2                                              

![image](https://user-images.githubusercontent.com/94309132/144060375-8026e283-b561-4b80-8d45-fa88e47b47f0.png)


## HIGH LEVEL REQUIREMENT:

###  HC-SR04 ultrasonic sensor

* The HC-SR04 ultrasonic sensor uses sonar to determine the distance to an object like bats do. It offers excellent non-contact range detection with high accuracy and stable readings in an easy-to-use package.
* From 2cm to 400 cm or 1” to 13 feet. Its operation is not affected by sunlight or black material like sharp rangefinders are (although acoustically soft materials like cloth can be difficult to detect). It comes complete with the ultrasonic transmitter and a receiver module.


1. Minimum measuring range - 2 cm
2. Maximum measuring range : 400 cm or 4 meter
3. Accuracy : 3 mm
4. Operating Voltage : +5V
5. Operating Current : 15mA
6. Working Frequency : 40 KHz
7. Trigger Input signal : 10us pulse
8. Measuring angle : 15 degree

### 16x2 LCD Module

* 16x2 LCD modules are very commonly used in most embedded projects, the reason being its cheap price, availability,  programmer friendly and available educational resources. 

1.Operating Voltage is 4.7V to 5.3V
2.Current consumption is 1mA without backlight
3.Alphanumeric LCD display module, meaning can display alphabets and numbers
4.Consists of two rows and each row can print 16 characters.
5.Each character is build by a 5×8 pixel box
6.Can work on both 8-bit and 4-bit mode
7.It can also display any custom generated characters
8.Available in Green and Blue Backlight


## LOW LEVEL REQUIREMENTS

###  HC-SR04 ultrasonic sensor

1. VCC: +5VDC
2. Trig : Trigger (INPUT)
3. Echo: Echo (OUTPUT)
4. GND: GND


### 16x2 LCD Module


|pno| pin name                  |              pin description
|---|---------------------------|---------------------------------------------------------------------------------------------|
|1  |   Vss (Ground)            |     Ground pin connected to system ground                                                   |
|2  |  Vdd (+5 Volt)            |      Powers the LCD with +5V (4.7V – 5.3V)                                                  |
|3  |  VE (Contrast V)          | Decides the contrast level of display. Grounded to get maximum contrast.                    |
|4  |  Register Select          |    Connected to Microcontroller to shift between command/data register                      |
|5  |   Read/Write              |    Used to read or write data. Normally grounded to write data to LCD                       |
|6  |   Enable                  |    Connected to Microcontroller Pin and toggled between 1 and 0 for data acknowledgement    |
|7  |   Data Pin 0              |                                                                                             |
|8  |    Data Pin 1             |                                                                                             |       
|9  |  Data Pin 2               |                                                                                             |
|10 |   Data Pin 3              |                                                                                             |  
|11 |  Data Pin 4               |                                                                                             | 
|12 |  Data Pin 5               |                                                                                             |
|13 |  Data Pin 6               |                                                                                             |
|14 |  Data Pin 7               |                                                                                             |
|15 |   LED Positive            |Backlight LED pin positive terminal                                                          |
|16 |     LED Negative          |  Backlight LED pin negative terminal                                                        |


### 4WIH ANALYSIS :

* What - The ultrasonic sensor is used to measure the distance. It acts as a Sonar. It sends an ultrasonic wave of a certain frequency          that comes back after hitting the object and calculates the time traveled by it. 
* Where - Ultrasonic sensors are used primarily as proximity sensors. They can be found in automobile self-parking technology and anti-           collision safety systems. Ultrasonic sensors are also used in robotic obstacle detection systems, as well as manufacturing             technology.
* when - anytime.
* why - An ultrasonic sensor is an electronic device that measures the distance.
* How - after buliding perfect system , testing and executiON.


### SWOT ANALYSIS :

* stregnth - Measure distance easily.
* Weakness - nil
* Oppurtunity - can inbuilt with any application nedds distance measurement.
* Threat - nil



# PIN DIAGRAM :

## ATMEGA328P PIN DIAGRAM :

![image](https://user-images.githubusercontent.com/94309132/144063584-b38957ec-8d26-493f-94b8-37bb2d8a6313.png)



## Ultrasonic Sensor HC-SR04:

![Ultrasonic-sensor-pinout](https://user-images.githubusercontent.com/94309132/144062975-3799cb4d-9bc6-4a12-a861-e287d5e3e59e.png)


## 16x2 LCD Module :

![image](https://user-images.githubusercontent.com/94309132/144063212-58a0ad56-f626-48b3-9f26-61cb8638d0a5.png)


# BLOCK DIAGRAM :

![uml (1)](https://user-images.githubusercontent.com/94309132/144071425-13a73aaa-368a-44e1-9a1c-10f7530802f9.png)


# COMPONENT DIAGRAM  :

![Untitled Workspace](https://user-images.githubusercontent.com/94309132/144427272-33da3e3f-377c-4efe-b2e3-4272e9859034.png)


# BILL OF MATERIALS

Circuit: module 2 project.simu

Bill of Materials:

Hd44780-2 : Hd44780   
SR04-4 : SR04   
atmega328-1 : atmega328   

# SIMULATION DIAGRAM :


![module 2 project](https://user-images.githubusercontent.com/94309132/144086770-f0c138eb-d531-4765-ae43-1779941e009b.png)


# FUNCTION OF PROJECT:

The ultrasonic sensor emits a high-frequency sound pulse and calculates the distance depending  upon the time taken by the echo signal to travel back after reflecting from the desired target. The speed of sound is 341 meters per second in air. After the distance is calculated, it will be displayed on the LCD display. 


# SAMPLE OUTPUT:

## HARDWARE OUTPUT:


![image](https://user-images.githubusercontent.com/94309132/144422935-3cc4eca4-5549-4fd7-ace9-5c2514ff9e8b.png)


## SIMULATION OUTPUT:


![image](https://user-images.githubusercontent.com/94309132/144423316-e927a5e8-a35d-4576-afef-603d0e21f853.png)

