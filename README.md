# Future-Engineers-I-Love-Shinan
## Team Introduction
**LIAO,YI-AN**

Shinan Junior High School

**LIN,CHING-PIN**

Taiping Junior High School

**HU,SIAN-YI**

Chung Lun Junior High School

### Team Photo

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/team%20photos/2021.10.31.jpg)

### Team Funny Photo

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/team%20photos/2021.10.31-2.jpg)

### Official Photo

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/team%20photos/official.jpg)
## YouTube URL

https://www.youtube.com/watch?v=a5rj4Xyn4FA

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/team%20photos/YouTube-Photo.png)


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

“Block_Switch_Logic” function will determine the distance, quantity, coordinates, area and color detected by the Pixy2 image sensor. When the traffic sign approaches, the direction of the dodge action will be executed according to the color. If there is no traffic sign or the traffic sign is far away from the organization, the dodge action will not be executed.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/Block%20switch%20function.png)
#### “Start_Decide” Function - Detect Vehicle Direction
“Start_Decide” function is used to detect the button you press to determine the direction of the vehicle. When you press button 1, it will move clockwise, and button 2 will move counterclockwise. When the program starts, it will detect the value of the electronic compass to know where it starts.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/other/start%20decide.png)

## Engineer Notebook
Record Date：2021.7.1
>We read the Chinese rules and discussed the length and width limitations of the organisation.We began to discuss the sensors and design and manufacture of the organisation, how >to use only one DC motor and how to make the steering structure.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.1-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.1-2.jpg)

Record Date：110.7.4
>We use the rigid Matrix Mini metal kit and the easy-to-fit Lego parts manufacturing mechanism.We use the upper half of the base plate mechanism to build the Matrix Mini metal >kit.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.4-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.4-2.jpg)

Record Date：110.7.4
>We installed L298n DC Controller GA25-371 DC Controller because there was no direct GA25-371 DC Controller for our use.Since L298n DC Madonna Control Board needs to be >connected to external sources, we manufacture an electric line for Legato3S off-leave polymer line for Legato298n DC Madonna Control Board. 


Record Date：110.7.7
>After the actual test, we found that the battery could easily come off the vehicle. To solve this problem, we installed Devil's Stain on the vehicle and the battery so that it >could be more effectively attached to the vehicle.Based on actual measurements, this method is indeed feasible.

Record Date：110.7.9
>We're going to plan an ultrasound sensor on a car, use it to leave somewhere, know if it needs to be, and then it's going to flip over because of its position, so we're going >to flip it early and late, so we're going to multi-position it.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.9-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.9-2.jpg)

Record Date：110.7.13
>Today's test found that the outer wheel takes a larger path when turning than the inner wheel. To ensure smooth and accurate turning of the mechanism, we installed a >differential on the rear wheel to make the mechanism more smooth when turning.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.13-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.13-2.jpg)

Record Date：110.7.15
>In order to keep the model in a straight line, we have found that the error in the values of the model in a specific area can be too large for the model to walk in a straight >line. Attaching the model to a height can improve the accuracy of the model.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.15-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.15-2.jpg)

Record Date：110.7.17
>Although the EDT sensor has been installed in a higher position, sometimes the error value is still a bit large in the field. When we encounter this problem, we think that we >can reduce the error value of the EDT in the field by using EDT correction.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.7.17-1.jpg)

Record Date：110.8.5
>Today, we install the Pixy2 image recognition module on the vehicle and the vehicle can read the information of the Pixy2 image recognition module successfully. After the >vehicle has read the Pixy2 image recognition module steadily, we write a program to identify and dodge blocks. 

Record Date：110.8.12
>Today, we use Pixy2 image recognition team to recognize the color of blocks and dodge blocks. In order to distinguish the distance from the distance, we use Y coordinates to >judge the distance from the near blocks.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.12-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.12-2.jpg)


Record Date：110.8.13
>We made LED lamp module and installed it in the rear of the organization. Since Pixy2 video recognition module cannot display the image recognition results immediately, we used >homemade LED lamp module to indicate the result detected by Pixy2 video recognition module.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.13-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.13-2.jpg)

Record Date：110.8.15
>To test whether the Lego motor is faster than the original drive motor and the steering is better than the servo motor, we have made a car out of Lego today. The base of the >Lego vehicle follows the original vehicle design.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.15-1.jpg)

Record Date：110.8.16
>Today we're going to put the Pixie2 image identification group on EV3 and EV3 will be able to get information from the Pixie2 image identification group, establishing that EV3 >can fit with the Pixie2 image identification group, and EV3 can avoid congestion.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.16-1.jpg)

Record Date：110.8.20
>After the test we find although the camera installed on the EV3 can correctly recognize the color and coordinates of traffic signs and dodge traffic signs all right but can not >installed how many traffic sign which can not achieve the effect we need so in the end we gave up the Lego vehicle.

Record Date：110.8.21
>On actual testing, we found that although the Pixy2 image recognition module could accurately identify the colour and coordinates of the blocks on the EV3 and dodge the blocks, >it could not detect the number of blocks on the screen.We decided to give up the Lego because we couldn't get the results we needed.

Record Date：110.8.23
>After the test, we found that the Pixy2 image recognition module was exposed when installing the wide-angle mirror, so we took the wide-angle mirror, but the next traffic sign >could not be detected.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.23-1.jpg)

Record Date：110.8.24
>In order for us to detect the next object, maybe we'll decide on the mirror and jump to the specified angle so that the pixy2 image can be detected.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.24-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.24-2.jpg)

Record Date：110.8.27
>Today, we re-pick up the wire and wrap the welds in a heat shrink jacket to avoid the risk of damaging the electronic components and connecting the positive and negative poles >with other people when installing batteries.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.27-1.jpg)

Record Date：110.8.28
>This line, which is always used by 10 lines, will be open and will be used by us not only by telephone but also by telephone calls, will be able to find faster to divide and >increase efficiency.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.28-1.jpg)

Record Date：110.8.30
>We found a problem that sometimes didn't have a counterpart because when the control board went on, the LED was supposed to be light, but it didn't, and we couldn't find the >problem why it was.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.30-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.30-2.jpg)

Record Date：110.8.31
>Since we practice constantly until the battery is dead and slow down, we attach a low voltage alarm to the battery to find out how much the battery is charged. When the battery >is dead, a low voltage alarm will sound an alarm to inform you that the battery is dead.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.8.31-1.jpg)

Record Date:110.9.2
>Today we started writing a three-turn program that uses ultrasound to detect when the vehicle is about to turn and to keep the vehicle in a straight line. These two sensors are >used to drive the vehicle three times, but the program does not recognize the traffic signs.
 
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.9.2-1.jpg)

Record Date:110.9.5
>Today we are going to run the three-turn program to add the traffic sign recognition program, but this program needs to turn the vehicle to the middle of the course. If it does >not reach the middle of the course, it will make a bad decision.

![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.9.5-1.jpg)

Record Date:110.9.12
>Today, we are participating in the International Conference. We have found that Darby's product numbers are very high. There is no direct communication from car manufacturers.
 
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.9.12-1.jpg)
![image](https://github.com/la7655/Future-Engineers-I-Love-Shinan/blob/main/%E7%9B%B8%E7%89%87/notebook%20photos/110.9.12-2.jpg)
