# CODTECH-Task1

Name: Nandigana Jyothi

Company:CODTECH IT SOLUTIONS.

ID:CT6VLSI659

Domain:VLSI

Duration:July to August 2024.

Mentor:Muzammil Ahmed.

**Overview of the project**

Project:Digital Logic Design With Verilog.

TOOL USED:EDA Playground.

Objective:The objective of this task is to design basic digital logic circuits like logic gates, adders, and multipexers using Verilog within the VLSI software. Simulate the verilog design to ensure correct functionality.Use the waveform viewer in the VLSI software to analyze the simulation results.

**4bit FULLADDER**


inputs:a, b, cin

outputs:sum,cout

Verilog module defines a FULLADDER with inputs a,b, cin where a, b are 4bit binary inputs and ouputs are sum and cout. Here sum is the 4 bit binary output.
The outputs sum and cout are reg datatypes because the outputs continuously changes as the any one of the input changes.
The code was implemented using behavioral modelling using always statement which repeats continuously throughout the duration of simulation time and starts at 0 simulation time.
The OR operation has been used and the outputs sum and cout are concatenated using concatenation operator(,). 
In TESTBENCH the dumpfile and dumpvars are used to obatain the wvaeform. and $monitor is used to print the outputs as the input chnages.

![Screenshot (177)](https://github.com/user-attachments/assets/44dd7116-b1ce-44e6-aef7-a4f13725f9c5)


**MULTIPLEXER**

inputs:in, sel

output:out


Multiplexer is a combinational circuit whose output depends only on the present inputs. Multiplexer having 2^n inputs , n sel inputs, 1 output (2^n:n:1)
Verilog module defines a multiplexer which is having 16 inputs and 1 ouput and 4 select inputs.The code is implemented using datflow modeeling with the assign stament 
using assign keyword.The output will be obtained based the select inputs.for exam the 4 select inputs are 0000 the output is i0, for 0110 the output is i6 etc.

![Screenshot (181)](https://github.com/user-attachments/assets/0fdcd693-f366-4660-bfb8-f10384460a37)

**LOGIC GATES**

inputs: i1, i2

outputs: o1,o2o3,o4,o5,o6,o7

verilog module defines all the logic gates. In verilog there are some predefined logic gates and digital circuits. Here the code is implemented using gatelevl modelling.
  AND gate: Performs the and operation of i1, i2. If both the inputs are logic 1 then the output is logic 1.
  OR gate: Performs the or operation of i1, i2. If both the inputs are logic 0 then the output is logic 0.
  NAND gate: Performs the nand operation of i1, i2. If both the inputs are logic 1 then the output is logic 0.
  NOR gate: Performs the nor operation of i1, i2. If both the inputs are logic 0 then the output is logic 1.
  XOR gate: Performs the xor operation of i1, i2. If both the inputs are different then the output is logic 1.
  XNOR gate: Performs the xnor operation of i1, i2. If both the inputs are same then the output is logic 1.
  NOT gate: The output is the complement of i1.

![Screenshot (174)](https://github.com/user-attachments/assets/cf896c88-90b8-442c-92a7-0eac23bcde3f)

