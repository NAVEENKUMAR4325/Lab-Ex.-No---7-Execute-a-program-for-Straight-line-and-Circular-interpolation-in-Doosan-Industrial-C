# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

### Program:

![program1](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/765d5a09-d0bc-4779-9cc3-f7df924b5de9)

![program 2](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/ad32a7b9-a1ec-4de8-b060-5972d22575ff)

![program 3](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/101386bd-b2f5-4133-9b51-e22bf488d15b)

![program 4](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/38f3cd77-0df7-4e0b-b68e-404445cdedaa)

![program5](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/128fc771-0bff-42c3-94d7-b87d8a3a2430)






Linear Interpolation:

![li](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/68b04b1a-95b4-433b-b0a5-66cc57f4870c)







Circular Interpolation:

![ci](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/4a888125-bcae-4917-badb-1e5782beeff3)


### output

Linear Interpolation:

![oli](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/71bd37a7-ad3a-4a9e-9824-e115d8fafc21)

Circular Interpolation:

![oci](https://github.com/NAVEENKUMAR4325/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119479566/2a6dd7cd-18b8-4343-b5c9-4a0f37cc3c1e)







### Results:

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



 
