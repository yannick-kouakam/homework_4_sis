1)project description:
the goal of this execirce is to implement a PID regualtor to make the ev3 follow a wall.
2)work description
the first step of the assingment was to gather own robot and progam it to execute the task specified in the requirement .
in this case follow a wall with minimal oscillation an deviation from a given distance

to progam the robot we use the "lego mindstorms education ev3 programming software" ;
the idea is to maintain  the robot at a distance of 15 centimeter to the wall ; to do so we compute the error (difference between the derise distance and the actual distance gathered from the ultrasound sensor)
then we pass the error to our PID regulator and as output we obtain the steering nesserary to apply to the robot to compensate the error.

after programing the PID regulator we need to find appropriate coeficient Kp,Ki and Kd.
we start by setting Kp=1, Ki=0,and Kd=0 this is because we are first interested in the response time. the we vary the value of Kp untill we get appropriate(desired ) result
the same procedure is apply to the Ki and Kd.

the final value of the coeficient obtain were 

Kp=0.2
Ki= 0.003
Kd=0.6

the diffuculty in this task is to find appropriate coeficients without using analytique tools.
this approach is time  consuming and it is not possible to said if the obtain coeficient are optimal for general cases. however we did a test and the result were well egnouth

 
youtube link to the video https://youtu.be/3pjpNnF-qr0
