# Arduino Based CNC Plotter Machine

A working protoype for this project is demonstrated in the following YouTube video:
https://youtu.be/lp__Aw2Isxo

An Arduino-based Computerized Numerical Control (CNC) plotter machine to print any image or text onto paper with the help of a pen or pencil.

Tools used: Arduino Nano, PCB, Arduino IDE, and Processing IDE

Input image:

![WhatsApp Image 2022-01-18 at 1 01 00 AM](https://user-images.githubusercontent.com/94376039/149879867-2e55148b-9fc3-4f4d-8114-b2bbebb67b8e.jpeg)

## Objective

The use of CNC machines in universities and laboratories is increasing day by day. Therefore, there is an absolute need of cheap and less complex designed CNC machines. The components used in this machine are cost effective as well as they are easily available in the markets. Also, designing of this machine is very simple.

## Working
At first, the user has to set up the microcontroller with the required instructions that the user wants as per his requirements with the help of arduino application. Then, the user should make use of the inkscape program in order to convert the required image/logo into g code format as the microcontroller only understands the g code language. Once the image has been saved in g code format, with the help of processing application the user can transfer the g code image data into the machine to get the required output. The microcontroller converts the g code into machine understandable language in order the get the required image/logo.

The machine consists of 3 axis i.e. X, Y, Z. X and Y axis moves with the help of stepper motor from the DVD writer and these movements are controlled by the L293D IC & Motor driver. The movement of the Z axis is controlled with the help of servo motor. We have designed a PCB for the connections of the equipment’s. After debugging and multiple testing, the machine was operating as planned. The main motive of this research was to design a CNC machine with less complexity and cost efficient which we have achieved. In order to make it cost efficient we have used spare parts to construct it.

The following image is the required output that we have achieved through our machine:
![image](https://user-images.githubusercontent.com/94376039/149957039-fbf1ba3e-6e6e-4fdb-9f56-e2014bbbc8fa.png)

Initial phase of the plotting machine in action:

![image](https://user-images.githubusercontent.com/94376039/149878723-5e394e70-d2d4-4002-b9cf-9943aa58a8bf.png)

Intermediate phase:

![image](https://user-images.githubusercontent.com/94376039/149878780-f2b794d8-3d7d-45eb-9284-bd16162a86a9.png)

Final phase of the plotting machine:

![image](https://user-images.githubusercontent.com/94376039/149878824-2e742ed9-5cc6-4611-8e81-65eea06aa934.png)

Final output on paper:

![image](https://user-images.githubusercontent.com/94376039/149879288-9949ba66-c05e-43c0-a5b8-b744a94b249d.png)
