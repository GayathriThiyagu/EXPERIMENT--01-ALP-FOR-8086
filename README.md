# EXPERIMENT--01-ALP-FOR-8086
Name : T. Gayathri
Roll no : 212223100007





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV Al,28H
MOV Bl,19H
ADD Al,Bl
RET
```
## Output  

 ![image](https://github.com/user-attachments/assets/ca3a919f-9698-40ad-8196-8496ffd485a8)

## Subtraction   of 8 bit numbers  ALP 
```
MOV Al,28H
MOV Bl,19H
SUB Al,Bl
RET
```
## Output  

![image](https://github.com/user-attachments/assets/a17e6bcb-b333-4c02-b263-b88ad6e12074)

## Multiplication alp 
```
MOV Al,28H
MOV Bl,19H
MUL Bl
RET
```
 ## Output  

![image](https://github.com/user-attachments/assets/dbe80839-3a28-4cbf-8a80-3753943e3894)

## Division alp 
```
MOV Al,28H
MOV Bl,19H
DIV Bl
RET
```
## Output  

![image](https://github.com/user-attachments/assets/6e5d6b3a-2a7e-4473-aa79-8037088325ba)

# AND of 8 bit number ALP:
```
MOV Al,28H
MOV Bl,19H
AND Al,Bl
RET
```
# OUTPUT

![image](https://github.com/user-attachments/assets/91c15f5b-a9fe-4cce-bc4e-d7f01ead1f19)

# OR of 8 bit number ALP: 
```
MOV Al,28H
MOV Bl,19H
OR Al,Bl
RET
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/a852765f-5218-4e02-bbae-71cd7a2cfb00)

# NOT of 8 bit ALP:
```
MOV Al,28H
NOT Al
RET
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/9b1bbb98-d962-4d94-a09b-4cf0f4fb2f0e)

# XOR of 8 bit ALP:
```
MOV Al,28H
MOV Bl,19H
XOR Al,Bl
RET
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/3cda2714-d8a6-4c36-bdde-215eed1de3c2)

## Result :
 
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.







