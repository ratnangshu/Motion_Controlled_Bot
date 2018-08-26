# Motion_Controlled_Bot
Robotics Club Workshop2018

Small Arduino Prjoect, that includes interfacing the Arduino with MPU6050 sensor.
MPU6050 is a 3 Axis Gyroscope and Accelerometer.
We will use only the accelerometer data to calculate roll pitch yaw of the imu and thereby control the bot by passing that data to the motor driver via Arduino UNO.

The connection of IMU to Arduino are as follows:

VCC -> 5v

GND -> GND

SCL -> A5

SDA -> A4

INT -> D2 (used for interrupt)

SCL = Serial Clock
SDA = Serial Data

The connection of Arduino to Motor Driver are as follows:

7 -> In1

8 -> In2

9 -> In3

10 -> In4

11 -> EnA

12 ->EnB

