First run the imu testing file to confirm your sensor is responding and working properly. Next collect data and then run the code for classifier.
Running the classifier code succesfully will give you a file with the model values that are used in the Arduino IDE code. Simply copy paste those values in the Arduino IDE code in the respective places.
The Arduino code uses random values generated in the range of imu sensor values to simulate sensor data rather than use the sensor itself.
This was done as I was facing problems with libraries regrading my sensor. You can modify the code to use the actual sensor. The math functions and model predictons remain the same.
P.S. be sure to select the proper board in Arduino IDE. I used an ESP32 due to its computing capabilities and ability to run simple classifiers.

** If you do not have access to an IMU sensor you can use my recorded data for the project ;).
