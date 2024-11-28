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

/* write all the steps invloved */

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: Anjali K RegisterNumber: 24900073

![Screenshot 2024-11-28 180250](https://github.com/user-attachments/assets/32283f3f-3aaf-4847-8929-00e87d122c46)

*/

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot (9)](https://github.com/user-attachments/assets/f29f568a-5662-4a6a-b8e4-98085c561ef0)



**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-11-28 180818](https://github.com/user-attachments/assets/6097fe2d-b0fe-405b-8592-43218cfad03a)
![Screenshot 2024-11-28 182054](https://github.com/user-attachments/assets/fbbe612f-230b-434f-b8d7-3113ad3708b1)



**RESULTS**
Thus the Encoder 8 to 3 in the Dataflow Modelling is designed and the truth table is verified using Quartus software.



