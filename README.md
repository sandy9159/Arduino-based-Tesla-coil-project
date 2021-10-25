# Arduino-based-Tesla-coil-project

![image](https://user-images.githubusercontent.com/19898602/138684192-c9a3feac-9e57-46b0-aba8-83005137c9e4.png)



Hello friends in this video I have made a Automatic Tesla coil winding machine

This machine can wind copper coil on long PVC tube which we can called a tesla coil
In this machine I have used two stepper motors one for rotating the PVC tube and 
One motor drive wire guider horizontally it gradually wind copper coil on the PVC tube.

All the necessary data user can directly input from a HMI, I have develop a simple GUI of user input 
Where user can provide data like how long winding has to be done and what is the thickness of wire.

Accordingly Arduino command both motor and a neat and clean winding is done on PVC tube.


# VIDEO
Here is the complete video of the project 

https://youtu.be/CWu26Ys8zlI

# COMPONENT USED

NEMA 17 Stepper motor

A4988 stepper motor driver

Arduino Nano 

Wooden board of 12mm thick

20 x 20 aluminum profile

8mm pillow bearing

8mm SS rod

T8 lead screw and nut

Timing pulley

Timing belt

9mm Linear slider


# PROCEDURE

![image](https://user-images.githubusercontent.com/19898602/138684328-14841c70-8f89-4d04-8784-490208a2b703.png)
![image](https://user-images.githubusercontent.com/19898602/138684357-ad16b3c7-9128-4432-86ff-a0dc441f2a74.png)


First I have cut the 12mm Plyboard sheet in 250 x 300 mm dimention with the help of my table saw

This 12mm wooden sheet is became the base of over machine, always we have to consider good and stong base for machine.

![image](https://user-images.githubusercontent.com/19898602/138684649-d23c75a8-3c27-4ff8-acde-2ebb99ef2337.png)

Then I take 4 20x20 aluminum profile piece of 200mm 

20x20 aluminum profile are my favourite to build any machine, because its very easy and 
Convenient to mount components on this 20x20 alu. Profile you just need some T nuts that’s it.
You can mount components with drilling any holes that is what I like about this profiles. 


![image](https://user-images.githubusercontent.com/19898602/138685256-ce84eaf6-1a43-454b-989e-b0aa77060431.png)![image](https://user-images.githubusercontent.com/19898602/138685289-623c4def-d436-4906-9cb3-1c3388f4401d.png)

Then I bring 4 qty. 8mm pillow bearing. and fix them on alu. profile.

![image](https://user-images.githubusercontent.com/19898602/138685497-75153fc9-38fd-4a39-b361-6b1bba0722ea.png)![image](https://user-images.githubusercontent.com/19898602/138685551-7a770cd1-606e-4149-b2b3-a92a7c716af6.png)


Then I insert T8 lead screw in one set pillow bearing. this arrangent is for horizontal movement of wire guider.

and I inserted 8MM ss rod in other set of pillow bearing this the arrangment for to hold the PVC tube on which winding hase to be done.

![image](https://user-images.githubusercontent.com/19898602/138685791-da04a3b0-0650-42a7-85a8-aa47562f634e.png)


Then I placed the two NEMA 17 stepper motor as seen in the image 
nema 17 motors are the best for such projects, yes to control system for stepper motors are quite compilcated

in comparison of normal DC motors, but stepper motor have huge plus points over DC motors, they have high accuracy, high toque at low RPM.
precision contorl are some key factor to choose stepper motors insted of normal DC motors. 

![image](https://user-images.githubusercontent.com/19898602/138686193-fb701913-75ab-4a03-b254-d68203570f47.png)![image](https://user-images.githubusercontent.com/19898602/138686258-0f47038f-8b17-412c-8b3b-56b566b72bbf.png)

Then I inserted timing pulley on the shaft of stepper motor and one for each 8mm rod.
Timing pulley and timing belt are beat for precious motion transfer from stepper motor to end effector this system have zero slip.


# CIRCUID DRAWING $ CUSTOM PCB

Making such projects without PCB is night mare yes trust me
you cannot get wanted result and professional touch in your project if you ignore PCB
So some days back I have developed my Multipurpose PCB.
This PCB is used to build wide range of arduino projects 

![Schematic_Multipurpose pcb_2021-09-15](https://user-images.githubusercontent.com/19898602/133383877-24044b9a-8d05-445a-808f-b6960dbe0e07.png)


followings are the some features of PCB

1. Wide range of power input 9V to 24V DC
2. Cross polarity protection
3. DC motor voltage selection 9V or 12 V DC
4. Servo motor voltage selection 5V or 9V DC
5. Manual microstepping setting for stepper motor
6. Power indication LED
7. L298N IC for heavier DC motor
8. ON board 5V and 9V regulator no need to arrange different power sources
9. Header pins and screw terminals for easy connections

List of the Components you can connect to the PCB

1. 2 DC motor ( 9V to 24V DC)
2. 2 Potentiometer
3. 2 Servo motors ( 5V to 9V DC)
4. 1 Serial device (BT module, HMI, Communication module, RX, TX)
5. 1 Encoder (2 interrupt pin & 1 PB pin)
6. 1 I2C device (SCL/SDA Device, display, MPU6050 etc)
7. 2 Stepper motors 


![MVI_0001 00_06_45_21 Still003](https://user-images.githubusercontent.com/19898602/133377296-ba24f45e-dcf4-4f97-9aa5-77aaed90175a.jpg)
![MVI_0001 00_07_21_22 Still004](https://user-images.githubusercontent.com/19898602/133377355-12dca9e1-068f-4cf5-ae58-84663ff57dde.jpg)

I have ordered PCB from [JLCPCB](https://jlcpcb.com/IAT )

This is the link of [PCB editabl file](https://oshwlab.com/sharmaz747/multipurpose-pcb)

If you seriously need quality PCB quickly in your hand then you must have to try [JLCPCB](https://jlcpcb.com/IAT ) PCB manufacturing service.
They have Special offer of $2 for 1-4 Layer PCBs, free SMT assembly monthly.
If new user signup today from this link [JLCPCB](https://jlcpcb.com/IAT ) you will get 30$ coupon from [JLCPCB](https://jlcpcb.com/IAT ).

![image](https://user-images.githubusercontent.com/19898602/138686998-33a08efe-93af-44e7-991a-c77a59e2c089.png)






