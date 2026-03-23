# EXPERIMENT 1 : EXECUTION OF LOGIC GATES USING PLC LADDER PROGRAM


 # NAME : Prajeeth K T
 # REGISTER NUMBER : 212222110034
 # DEPARTMENT : CSE(IOT)
 # YEAR : IV
 # DATE : 27-01-2026

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
## AND Gate:
<img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/c6c07dd3-7df0-4d4b-a3d0-02fc3530521f" />

## OR Gate:
<img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/d10702f0-c867-4bab-966d-07cd19976d59" />

## NOT Gate:
<img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/00f7586f-223c-42dd-9b73-a0afd36cfd78" />

## NAND Gate:
<img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/33c767f9-81cc-4acf-9dd1-017da5fcb2e9" />

## NOR Gate:
<img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/9c40d689-d15c-4c51-8be8-bacc7d2db8fa" />

## XOR Gate:
<img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/f530b111-6028-4945-b56d-0e2e1b868b4b" />

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS

## AND Gate:
<img width="656" height="128" alt="Screenshot 2026-01-27 182412" src="https://github.com/user-attachments/assets/f83b0ad6-df24-49e9-bdc4-15c07a1d1233" />

## OR Gate:
<img width="652" height="211" alt="Screenshot 2026-01-27 182424" src="https://github.com/user-attachments/assets/2393d027-66e9-42ef-986f-3624e9752ed6" />

## NOT Gate:
<img width="677" height="143" alt="Screenshot 2026-01-27 182432" src="https://github.com/user-attachments/assets/d9e830f9-c543-46dd-ab0b-a0dd22e0ece9" />

## NAND Gate:
<img width="645" height="272" alt="Screenshot 2026-01-27 182450" src="https://github.com/user-attachments/assets/c4d47526-cd2e-4478-a398-335f8854c335" />

## NOR Gate:
<img width="669" height="271" alt="Screenshot 2026-01-27 182502" src="https://github.com/user-attachments/assets/15939c1c-f8a0-4f2d-8869-b98050e2d2e3" />

## XOR Gate:
<img width="676" height="251" alt="Screenshot 2026-01-27 182511" src="https://github.com/user-attachments/assets/a3df55fb-2665-4438-80fa-8d37bf233f31" />


<img width="1294" height="423" alt="Screenshot 2026-01-27 182212" src="https://github.com/user-attachments/assets/a2fa40f1-83c5-4efe-9fc3-b744babffde4" />

<img width="1282" height="430" alt="Screenshot 2026-01-27 182226" src="https://github.com/user-attachments/assets/d9009b95-5323-4905-b585-e89a609a028e" />

<img width="1293" height="438" alt="Screenshot 2026-01-27 182239" src="https://github.com/user-attachments/assets/7d252906-87f5-4384-9a50-5e043e8265b9" />

<img width="1281" height="428" alt="Screenshot 2026-01-27 182258" src="https://github.com/user-attachments/assets/4394d544-e5cb-45a8-83e2-6bb0bb33b2c5" />


# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
