# 8:1MULTIPLEXER USING LOGIC GATES DYNAMIC CMOS LOGIC
AIM: Designing and implementation 8:1 mux using logic gates and dynamic cmos logic using cadence  virtuoso.

### Abstraction :
An 8:1 multiplexer is a digital circuit that selects one of eight input signals and forwards 
it to a single output line. The selection of the input signal to be transmitted is controlled 
by a set of three binary control inputs (often labeled A, B, and C). These control inputs 
determine which input signal is passed through to the output.
The 8:1 multiplexer has eight input lines and one output line. When a particular 
combination of the three control inputs is applied to the multiplexer, the corresponding 
input signal is transmitted to the output line. For example, if the control inputs are set to 
"000", the input signal on the first input line will be transmitted to the output line. If the 
control inputs are set to "001", the input signal on the second input line will be 
transmitted to the output line, and so on.
The 8:1 multiplexer is a basic building block in digital circuit design and is commonly 
used in a wide range of applications, including data transmission, memory addressing, 
and signal routing.
IMPLEMENTATION: 8 to 1 Multiplexer
In the 8 to 1 multiplexer, there are total eight inputs, i.e., A0, A1, A2, A3, A4, A5, 
A6, and A7, 3 selection lines, i.e., S0, S1and S2 and single output, i.e., Y. On the 
basis of the combination of inputs that are present at the selection lines S0, S1, and 
S2, one of these 8 inputs are connected to the output. The block diagram and the 
truth table of the 8×1 multiplexer are given below

### Block Diagram:
![1](https://github.com/madhumadhu1318/8-1-MULTIPLEXER-USING-LOGIC-GATES-DYNAMIC-CMOS-LOGIC/assets/90201844/3aaf8120-c652-44f2-8f93-72e8ae0aac44)

### Truth Table
![2](https://github.com/madhumadhu1318/8-1-MULTIPLEXER-USING-LOGIC-GATES-DYNAMIC-CMOS-LOGIC/assets/90201844/46aca58f-73c1-4155-88ab-2a9aaf7db112)

The logical expression of the term Y is as follows:
Y=S0'.S1'.S2'.A0+S0.S1'.S2'.A1+S0'.S1.S2'.A2+S0.S1.S2'.A3+S0'.S1'.S2 A4+S0.S1'.S2 
A5+S0'.S1.S2 .A6+S0.S1.S3.A7

## Logical circuit of the above expression is given below

![3](https://github.com/madhumadhu1318/8-1-MULTIPLEXER-USING-LOGIC-GATES-DYNAMIC-CMOS-LOGIC/assets/90201844/b97889f2-2db3-432c-9f7f-c0235d4da3f3)

## CIRCUITE DIAGRAM : 8:1 mux using logic gates

![4](https://github.com/madhumadhu1318/8-1-MULTIPLEXER-USING-LOGIC-GATES-DYNAMIC-CMOS-LOGIC/assets/90201844/d3d60029-d962-4621-b1b0-ab034217f53e)

## TIMING DIAGRAM:

![4 4](https://github.com/madhumadhu1318/8-1-MULTIPLEXER-USING-LOGIC-GATES-DYNAMIC-CMOS-LOGIC/assets/90201844/2772867a-6a40-4dc2-be22-515eefb243e5)

## Whenever the test cases are :
![5 1](https://github.com/madhumadhu1318/8-1-MULTIPLEXER-USING-LOGIC-GATES-DYNAMIC-CMOS-LOGIC/assets/90201844/594d5116-b86d-4d84-9e53-b00712f5b777)







