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



Objective:4bit fulladder

![Screenshot (177)](https://github.com/user-attachments/assets/44dd7116-b1ce-44e6-aef7-a4f13725f9c5)



Verilog module defines a FULLADDER with inputs a,b, cin where a, b are 4bit binary inputs and ouputs are sum and cout. Here sum is the 4 bit binary output.
The outputs sum and cout are reg datatypes because the outputs continuously changes as the any one of the input changes.
The code was implemented using behavioral modelling using always statement which repeats continuously throughout the duration of simulation time and starts at 0 simulation time.
The OR operation has been used and the outputs sum and cout are concatenated using concatenation operator(,). 
In TESTBENCH the dumpfile and dumpvars are used to obatain the wvaeform. and $monitor is used to print the outputs as the input chnages.

Objective:Multiplexer

![Screenshot (181)](https://github.com/user-attachments/assets/0fdcd693-f366-4660-bfb8-f10384460a37)

Multiplexer is a combinational circuit whose output depends only on the present inputs. Multiplexer having 2^n inputs , n sel inputs, 1 output (2^n:n:1)
Verilog module defines a multiplexer which is having 16 inputs and 1 ouput and 4 select inputs.The code is implemented using datflow modeeling with the assign stament using assign keyword.The output will be obtained based the select inputs.for exam the 4 select inputs are 0000 the the output is i0, for 0110 the output is i6 etc.




