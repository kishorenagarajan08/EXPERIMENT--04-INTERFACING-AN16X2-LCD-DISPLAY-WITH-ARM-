# EXPERIMENT--01-ALP-FOR-8086

Name :kishore.N

Roll no : 212222230106

Date of experiment : 19.08.2023

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

## Addition of 8 bit ALP  
```python
Mov AL,74H
Mov BL,69H
Add AL,BL
HLT
```
## Output  
 
![316391105-5f44a6c1-d56d-49ef-b0f9-a676ba1958e4](https://github.com/user-attachments/assets/1edc8c29-97eb-4993-8a17-5f2d57806739)

## Subtraction of 8 bit ALP
```python
Mov AL,84H
Mov BL,63H
Sub AL,BL
HLT
```
## Output

![2](https://github.com/user-attachments/assets/67dfb63a-9240-44d5-a3c3-508f2d323882)

## Multiplication ALP
```python

org 100h
MOV AL,75H
MOV BL,32H
MUL BL
HLT

ret
```
 ## Output  

![3](https://github.com/user-attachments/assets/8dbd1ca2-fb6f-4853-8ce0-3facdac515f4)

## Division ALP
```python

org 100h
MOV AL,68H
MOV BL,18H
DIV BL
HLT

ret
```
## Output  

![4](https://github.com/user-attachments/assets/cd26527a-0dcb-4964-bae9-cd3cec45a637)

## Programs for logical  operations

## AND
```python
Mov AL,33H
Mov BL,44H
AND AL,BL
HLT
```
## Output 

![5](https://github.com/user-attachments/assets/29af7b48-5241-43dc-965d-c57c751ac495)

## OR
```python
Mov AL,45H
Mov BL,66H
OR AL,BL
HLT
```
## Output

![6](https://github.com/user-attachments/assets/cc584bd3-2436-4d10-953c-d23bd67bb500)

## NOT
```python
Mov AL,65H
NOT AL
HLT

```
## Output

![7](https://github.com/user-attachments/assets/7645cbf4-d216-4035-876a-381ff4f2ece8)

## XOR
```python
org 100h
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
ret
```
## Output

![8](https://github.com/user-attachments/assets/ab23087e-23e3-4677-9e0e-893e553e94c7)

## Result :

Thus, ALP for fundamental arithmetic and logical operations are executed successfully.
 
