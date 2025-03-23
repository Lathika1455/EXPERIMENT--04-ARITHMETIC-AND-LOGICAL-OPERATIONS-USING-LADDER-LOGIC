# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME:Lathika Sree R
# REGISTER NUMBER:212224040169
# DEPARTMENT:CSE
# YEAR:2025
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).
##  Simulation Screenshots:
ADDITION
![ex 4 iiot ss1](https://github.com/user-attachments/assets/9b72ceaa-1629-4ecf-aade-f0f7bbba9883) 
![ex 4 iiot ss2](https://github.com/user-attachments/assets/a8ed21e1-84ca-4c87-82c9-723dee46a4fa)
![image](https://github.com/user-attachments/assets/5c6a8f33-b108-4b10-bd97-ee9f712912f2)
![image](https://github.com/user-attachments/assets/f9c2049a-2f33-4580-aecd-037fea17a3fb)
![ex 4 iiot ss5](https://github.com/user-attachments/assets/fa07228c-0095-4920-9ba7-b74fa06cb7b6)
![ex 4 iiot ss6](https://github.com/user-attachments/assets/80903ad2-08cd-4402-bd16-409327e5250c)

SUBTRACTION
![ex 4 ss7](https://github.com/user-attachments/assets/8a4ba860-ea3a-49df-8d0a-f97c6cd0f416)
![ex 4 ss8](https://github.com/user-attachments/assets/495afef3-8aae-4475-a842-9e104c6ab178)
![Screenshot 2025-03-23 114558](https://github.com/user-attachments/assets/377b62d6-1f58-4f6a-a569-330218f2dac0)
![ex 4 ss10](https://github.com/user-attachments/assets/a4abdffd-f694-49c8-a69d-0d6725f34b52)
![ex 4 ss11](https://github.com/user-attachments/assets/95187ad2-59ab-4d02-9b79-47349e9159e0)
![ex 4 ss12](https://github.com/user-attachments/assets/df994b86-c3da-4cb3-a144-ee859e5326f2)

MULTIPLICATION
![ex 4 ss13](https://github.com/user-attachments/assets/9aea30d9-36d8-48aa-b418-1b48a77bea24)
![ex 4 ss14](https://github.com/user-attachments/assets/6e7ea8a1-ee18-4a5b-9d19-e60d0c136fd8)
![ex 4 ss15](https://github.com/user-attachments/assets/5a810e6e-9868-4c9b-9f25-71beea03fd72)
![ex 4 ss16](https://github.com/user-attachments/assets/b2ed1677-cb27-4586-97d0-011fcb2f5c70)
![ex 4 ss17](https://github.com/user-attachments/assets/3cc9b480-84c9-4579-9565-cdaec89d077f)
![ex 4 ss18](https://github.com/user-attachments/assets/3f5d83ac-65b8-423d-86a8-5e8613459aa2)

DIVISION
![ex 4 ss19](https://github.com/user-attachments/assets/1c1f361b-014b-4faf-89fc-2e0421f43390)
![ex 4 ss20](https://github.com/user-attachments/assets/de71fa58-c44b-4d57-9ff9-2d5f3c76daab)
![ex 4 ss21](https://github.com/user-attachments/assets/1e8a6f68-73de-460f-b663-8cbde5f6ae8c)
![ex 4 ss22](https://github.com/user-attachments/assets/c96420d4-3fa6-46c8-857b-098e6c0c3a2c)
![ex 4 ss23](https://github.com/user-attachments/assets/24d5d74e-557d-44fa-a0f5-80b735a9dc61)
![ex 4 ss24](https://github.com/user-attachments/assets/6115621e-95cf-47d5-a167-ede08aaf6339)
## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
