# EXPERIMENT--01-ALP-FOR-8086
```
Name :S.YOGARAJ
Roll no : 212223040248
Date of experiment : 26/08/2024
```




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
org 100h

mov al, 15h
mov bl, 22h
add al, bl
mov [5454h], al

ret
```
## Output  
 ![358999651-d42b2503-4743-4049-90f5-1ac43b7153c4](https://github.com/user-attachments/assets/ebc6d969-f133-4830-b0db-0358bae7a528)

## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h

mov al, 55h
mov bl, 21h
sub al, bl
mov [3254h], al

ret
```
## Output  
![358999268-722fddbc-53b7-489e-a1e3-f6d5e9d43848](https://github.com/user-attachments/assets/9261f88a-91b4-4d5c-b3ca-083265a08eee)

## Multiplication alp 
```
org 100h

mov al, 17h
mov bl, 4h
mul bl
mov [1234h], al

ret
```
 ## Output  
![359028766-51bcdcc4-b22b-4853-9320-2ce43297dc22](https://github.com/user-attachments/assets/7740141c-4139-4da9-8400-6e2225da7256)


## Division alp 
```

mov al, 72h
mov bl, 4h
div bl
mov [5151h], al

ret
```
## Output  
![358998513-a4173f93-bad8-4653-bfd6-480f71de57a9](https://github.com/user-attachments/assets/ef4fdca6-18fa-4c57-8682-f4392106771d)

## Programs for Logical operations

## OR Operation
```
org 100h

mov al, 15h
mov bl, 22h
or al, bl
mov [5454h], al

ret
```

## Output
![359031135-a41563f6-a008-4a04-8eff-230bfe6dacf1](https://github.com/user-attachments/assets/ecd289b2-e8de-41d3-9030-9d2d8dc0ef6b)

## AND Operation
```
org 100h

mov al, 07h
mov bl, 05h
and al, bl
mov [5000h], al

ret

```
## Output
![359032501-4d8efd41-ce19-4094-a5db-62aca9d6ad3d](https://github.com/user-attachments/assets/1dbf43b0-6f0e-4693-8663-20deba4f2072)

## XOR Operation
```
org 100h

mov ax, 0A32h
mov bx, 05B7h
xor ax, bx
mov [5050h], ax

ret

```
## Output
![359033546-a3b46d73-a612-4d8e-815a-0698f88be6b9](https://github.com/user-attachments/assets/f3d0948c-1093-497a-9dbb-7eb2aea0804a)

## NOT operation
```
org 100h

mov ax, 0F5Bh
not ax
mov [6666h], ax

ret
```

## Output
![359034236-4dde3cd8-07de-418e-9cbc-a4034ce45578](https://github.com/user-attachments/assets/569588f2-f0a6-4bd9-97bf-57e9a085b302)

## Result :
 
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.







