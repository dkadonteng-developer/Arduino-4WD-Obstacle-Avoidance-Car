# Arduino-4WD-Obstacle-Avoidance-Car

Introduction

A DIY four-way tracking and Ultrasonic obstacle avoidance car.
The kit is based on the popular opens-ource electronic platform Arduino. 


CODE EXPLANATION:
When the transmitting pin of the ultrasonic module detects an obstacle in front, the reflected pin will receive the signal and transmit it to the MCU through the IO pin. After the SIGNAL is received, the MCU will drive the L298N module to realize the corresponding action of the motor. For example, if an obstacle is detected in the front range of less than 30cm and larger than 10cm, the MCU will control the car to retreat successively and then turn left, while in the front range of less than 10cm, the car will stop, while in the front range greater than 30cm, the car will move forward without any obstacle detected.
