# Future-Engineers-I-Love-Shinan
## Team Introduction
**LIAO,YI-AN**

Shinan Junior High School

**LIN,CHING-PIN**

Taiping Junior High School

**胡賢邑**

Chung Lun Junior High School
### Vehicle Design Concept
In order to have better steering so we design the Ackerman steering in vehicle. And use the servo motor to control the steering. We download Differential at the mover motor.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/picture1.png)
### Vehicle Component
Our vehicle uses four sensors, one servo motor, one DC motor, and one controller.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/picture2.png)

#### Compass Sensor
The Compass Sensor is used to detect the direction of the vehicle.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/cmopass%20sensor.png)
### Pixy2 Camera
Pixy2 is used to identify the position and size of the red and green obstacles on the field to dodge the block obstacles. 

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/pixy2%20camera.png)
### Matrix Mini Controller
Our vehicle use the Matrix Mini Controller controller to control the motor and read the sensor value

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/Matrix%20mini.png)
### Uitrasound Sensor
Detect the distance between the fence and the vehicle to know whether the vehicle needs to turn.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/ultrasonic%20sensor.png)
### DC Motor
Drive the rear wheels of the car to control the forward and backward of the vehicle.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/DC%20motor.png)
### Servo Motor
Control the Ackerman steering mechanism to make the vehicle turn.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/Servo%20motor.png)
## Vehicle Components Introduction
We use DuPont wire and RJ495 connector to connect the sensor to the motor and the controller.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/Component%20Configuration.png)
## Vehicle Structure Introduction
### Differential
In order to solve the problem that the path taken by the outer wheels is larger than the path taken by the inner wheels when turning, we install a differential.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/Differential.png)
### Steering Mechanism
In order to have better steering, we design the steering rudder as Ackerman steering structure, and use the servo motor to control the steering of the steering rudder.
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/Steering%20Mechanism.png)

## Abstract of Robot Rogramming
### Programming Language
Arduino IDE is a hardware platform, Write the program and burn the program into the Matrix MINI. Write the program and burn the program into the Matrix MINI.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/arduino.png)
### Flowchart
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/flowchart.png)
### Programming Introduction
#### “Block_Switch_Logic” Function -Judging raffic Signs And Dodge
![image](https://user-images.githubusercontent.com/68604072/139440799-dc41f8f9-ba7f-4b4f-907e-01cb330cb4fe.png)

“Block_Switch_Logic” function will determine the distance, quantity, coordinates, area and color detected by the Pixy2 image sensor. When the traffic sign approaches, the direction of the dodge action will be executed according to the color. If there is no traffic sign or the traffic sign is far away from the organization, the dodge action will not be executed.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/Block%20switch%20function.png)
#### “Start_Decide” Function - Detect Vehicle Direction
“Start_Decide” function is used to detect the button you press to determine the direction of the vehicle. When you press button 1, it will move clockwise, and button 2 will move counterclockwise. When the program starts, it will detect the value of the electronic compass to know where it starts.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/start%20decide.png)

## Engineer Notebook
Record Date：2021.7.1
Content：
>We read the Chinese rules and discussed the length and width limitations of the organisation.We began to discuss the sensors and design and manufacture of the organisation, how >to use only one DC motor and how to make the steering structure.


