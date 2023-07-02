## AODC ROBOT 

This project was generated with [Arduino IDE](https://www.arduino.cc/en/software) Version 2.1.0.

## Development Of Robot
The project is design to build an obstacle avoidance robotic vehicle using ultrasonic sensors for its movement. A microcontroller (ATmega328) is used to achieve the desired operation. A robot is a machine that can perform task automatically or with guidance. The project proposes robotic vehicle that has an intelligence built in it such that it directs itself whenever an obstacle comes in its path. This robotic vehicle is built, using a micro-controller of AT mega 328 family. An ultrasonic sensor is used to detect any obstacle ahead of it and sends a command to the micro-controller. Depending on the input signal received, the micro-controller redirects the robot to move in an alternate direction by actuating the motors which are interfaced to it through a motor driver. Some of the project is built with the IR sensors has its own application so in our project those application is not compactable so we are using ultrasonic sensor.

Alternately this project is not designed for obstacle avoidance and also it is designed to collect all the dust particles. Manual work is taken over the robot technology and many of the related robot appliances are being used extensively also. Here represents the technology that proposed the working of robot for Floor cleaning. Households of today are becoming smarter and more automated. Domestic robots are entering the homes and people’s daily lives, but it is yet a relatively new and immature market. However, a growth is predicted and the adoption of domestic robots is evolving. The purpose of this project is to design and implement a Vacuum Robot for Autonomous dry cleaning application. Vacuum Cleaner Robot is designed to make cleaning process become easier rather than by using manual vacuum. The main objective of this project is to design and implement a obstacle avoiding and vacuum robot prototype by using Arduino Uno, motor driver shield, Motor, Ultrasonic Sensor, Motor power controller and to achieve the goal of this project. The whole circuitry is connected with 14.8V battery. On the perspection this Vacuum Robot has some criteria that are environment friendly and user-friendly.

## HARDWARE REQUIRED

> ARDUINO UNO R3 ATmega 328.                                                                                                              
> MOTOR DRIVER SHIELD  (L293D).                                                                                                           
> TOWER PRO MOTOR (SG90).                                                                                                                 
> ULTRASONIC SENSOR (HC – SR04).                                                                                                          
> DC GEARED MOTORS.                                                                                                                       
> LITHIUM – ION BATTERYS.                                                                                                                 
> MOTOR POWER REGULATOR.                                                                                                                  
> DC 9V POWER MOTOR.                                                                                                                                         
## SOFTWARE REQUIRED

OPERATING SYSTEM	:-  WINDOWS 7, 8, 8.1, 10, 11.                                                                                          
LANGUAGE			:-  C++.                                                                                                                    
SOFTWARE 			:-  ARDUINO IDE.                                                                                                            

## How Obstacles are Avoiding??

First of all, our robot car must be sensing the way if the way is clear then it move on the same path.                                    
Otherwise it move back a step and once again it will look around for the free way and then it will move on.

<img src="https://win.adrirobot.it/sonar/PING/immagini/ultrasonic_sensor_schema.jpg">

## Working Principle

The obstacle avoidance robotic vehicle uses ultrasonic sensors for its movements. Arduino is used to achieve the desired operation. The motors are connected through motor driver IC to Arduino. The ultrasonic sensor is attached in front of the robot. Whenever the robot is going on the desired path the ultrasonic sensor transmits the ultrasonic waves continuously from its sensor head. Whenever an obstacle comes ahead of it the ultrasonic waves are reflected back from an object and that information is passed to the arduino. The Arduino controls the motors left, right, back, front, based on ultrasonic signals. In order to control the speed of each motor pulse width modulation is used (PWM). When ultrasonic sensor detect the object which is kept inside the path it will send the signal toward the arduino uno and according to that it will it will rotate the motor M3 & M4 in forward direction and rotate the motor M1 & M2 in reverse direction such way that the car get moving in left direction .Similarly in every time whenever an obstacle in found to be in path of car it will detect it and rotate the car in left direction to avoid the obstacle and the it has been collecting all the dust particles surrounded in the floor with help of dust collector mounted on the robotic vehicle.
<img src="https://static.hindawi.com/articles/mpe/volume-2018/2163278/figures/2163278.fig.002.jpg">

## Conclusion

The goal of our project is to create a autonomous robot which intelligently detects the obstacle in his path and navigate according to the actions we set for it. The above Arduino controller and ultrasonic sensor were studied and the HcSR-04 ultrasonic sensor was selected, as the controlling result are satisfying for its use in the automobile prototype system bring developed. It was used to sense the obstacle and avoidance them as well as collect the dust particles.
