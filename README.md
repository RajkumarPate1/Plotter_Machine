# Arduino Based CNC Plotter Machine

A working protoype for this project is demonstrated in the following YouTube video:
https://youtu.be/lp__Aw2Isxo

## Summary

An Arduino-based Computerized Numerical Control (CNC) plotter machine to print any image or text onto paper with the help of a pen or pencil.

Tools used: Arduino Nano, PCB, Arduino IDE, and Processing IDE

## Objective

The use of CNC machines in universities and laboratories is increasing day by day. Therefore, there is an absolute need of cheap and less complex designed CNC machines. The components used in this machine are cost effective as well as they are easily available in the markets. Also, designing of this machine is very simple.

## Working
At first, the user has to set up the microcontroller with the required instructions that the user wants as per his requirements with the help of arduino application. Then, the user should make use of the inkscape program in order to convert the required image/logo into g code format as the microcontroller only understands the g code language. Once the image has been saved in g code format, with the help of processing application the user can transfer the g code image data into the machine to get the required output. The microcontroller converts the g code into machine understandable language in order the get the required image/logo.

The machine consists of 3 axis i.e. X, Y, Z. X and Y axis moves with the help of stepper motor from the DVD writer and these movements are controlled by the L293D IC & Motor driver. The movement of the Z axis is controlled with the help of servo motor. We have designed a PCB for the connections of the equipment’s. After debugging and multiple testing, the machine was operating as planned. The main motive of this research was to design a CNC machine with less complexity and cost efficient which we have achieved. In order to make it cost efficient we have used spare parts to construct it.

The following image is the required output that we have achieved through our machine:

![Untitled](https://user-images.githubusercontent.com/94376039/149964607-593276b7-ac13-43e3-b436-106ca17a4afe.jpg)

Input image:

![JerryMouse](https://user-images.githubusercontent.com/94376039/149964499-85957e7d-0c16-4d56-a872-528076d9256d.jpg)

Initial phase of the plotting machine in action:

![149878723-5e394e70-d2d4-4002-b9cf-9943aa58a8bf](https://user-images.githubusercontent.com/94376039/149964903-74553d86-9213-416d-bdf0-2f578e9ad9ab.png)

Intermediate phase:

![image](https://user-images.githubusercontent.com/94376039/149878780-f2b794d8-3d7d-45eb-9284-bd16162a86a9.png)

Final phase of the plotting machine:

![image](https://user-images.githubusercontent.com/94376039/149878824-2e742ed9-5cc6-4611-8e81-65eea06aa934.png)

Final output on paper:

![image](https://user-images.githubusercontent.com/94376039/149879288-9949ba66-c05e-43c0-a5b8-b744a94b249d.png)
