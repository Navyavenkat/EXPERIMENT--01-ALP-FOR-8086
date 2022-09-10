# EXPERIMENT--01-ALP-FOR-8086
Name :V.Navya
Roll no :212221230069
Date of experiment :10/09/2022





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
###
## Addition  of 8 bit ALP
```

org 100h
MOV AH,05;
MOV BH,03;
ADD AH,BH;
MOV CX,AX;
HLT;
```




## Output 
![image](https://user-images.githubusercontent.com/94165327/189480574-42257c3f-46f3-458e-8b61-88a3d9a3f422.png)

![image](https://user-images.githubusercontent.com/94165327/189480584-e77b9ce2-d520-4a60-96dd-803f979f0347.png)

![image](https://user-images.githubusercontent.com/94165327/189480590-3c5d8c1c-d3f3-42fd-a104-3285149400df.png)

![image](https://user-images.githubusercontent.com/94165327/189480602-f3856f55-3d71-4f3a-af7a-6aac75ea2386.png)


 
## Subtraction   of 8 bit numbers  ALP 
```

org 100h
MOV AH,05;
MOV BH,03;
SUB AH,BH;
MOV CX,AX;
HLT;
```

 
## Output  
![image](https://user-images.githubusercontent.com/94165327/189480619-f2e6e106-4b65-46f6-ae4f-e27a28addec4.png)
![image](https://user-images.githubusercontent.com/94165327/189480649-2c99ff19-bdd2-4dd4-a4e8-3410eeb22481.png)

## Multiplication alp
```


org 100h
MOV AH,05;
MOV BH,03;
MUL AH;
MOV CX,AX;
MOV AX,00;
HLT;
```

 ## Output 
 ![image](https://user-images.githubusercontent.com/94165327/189480678-7940c967-6529-412f-b1b7-490e70d07c95.png)
![image](https://user-images.githubusercontent.com/94165327/189480688-56e09b98-8c29-4f86-a5b0-9222bf065ac0.png)
![image](https://user-images.githubusercontent.com/94165327/189480696-b6e0e796-3495-4eca-8379-2db8d4520b1f.png)
![image](https://user-images.githubusercontent.com/94165327/189480698-887eacaf-9631-4831-ab8b-b29a1b89f9c0.png)



## Division alp
```

org 100h
MOV AH,05;
MOV BH,03;
DIV AH;
MOV CX,AX;
MOV AX,00;
HLT;
```


## Output  
![image](https://user-images.githubusercontent.com/94165327/189480709-68a15b3a-6679-4e35-9aba-cd0a1319df39.png)
![image](https://user-images.githubusercontent.com/94165327/189480819-0bdf67a4-04f8-4489-82a9-b68f649c80bf.png)
![image](https://user-images.githubusercontent.com/94165327/189480839-33016887-3b92-443a-af23-b677e91ecaba.png)
![image](https://user-images.githubusercontent.com/94165327/189480859-86b33fa2-2e72-4966-b44e-b312994f448e.png)




###
## Result :
 
    Hence ALP on fundamental arithmetic and logical operations is verified and executed.
 








