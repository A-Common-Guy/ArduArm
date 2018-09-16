# ArduArm
arm controlled robot with arduino


2 arduino connected via nrf24 radio pipe:
The project exploits 2 mpu6050 3 axys gyroscope-accellerometer sensor.
the pinch is controlled by an infrared distance sensor.
An ultrasonic distantiometer can be used instead.
the code is suited for a 5 servo arm.
lot of versatile functions are included in the code.
Next release will contain a new library

nrf24 settings will probably slow down the code with internal delays.
be careful in using non-external timers.
trasmission between tx and rx uses a low speed ,high reliability protocol(self written);
possibilty of increased trasmission rate by modifing nrf24 settings.



