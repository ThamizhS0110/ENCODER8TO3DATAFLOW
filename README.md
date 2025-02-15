### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

Open Quartus Prime and create a new Verilog project.

Write the Verilog code for the Encoder 8 to 3 in dataflow modeling.

Compile the design and check for any errors.

Generate the RTL schematic to verify the circuit.

Create a testbench to simulate the encoder functionality.

Apply different input combinations and observe the output in binary as per the truth table.

Generate the timing diagram to visualize the encoder operation over time.

Validate the results by comparing the simulation output with the expected truth table.

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by:Thamizh.S RegisterNumber:24900483
*/
![Screenshot 2024-12-05 131541](https://github.com/user-attachments/assets/3f893dca-782b-4be4-a1d2-5ce03533b261)


**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
![Screenshot 2024-12-05 131722](https://github.com/user-attachments/assets/191b82ac-4865-411a-83c5-5ec0ad15dbe7)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
![Screenshot 2024-12-05 131701](https://github.com/user-attachments/assets/0cff60f1-a29b-4e28-ac10-5762fbdb21de)


**RESULTS**



The Encoder 8 to 3 was successfully implemented using dataflow modeling in Verilog, and its functionality was validated using the truth table. The output correctly corresponds to the active input line as expected.




