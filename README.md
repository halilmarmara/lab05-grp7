# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Kaimana Furniss & Halil Marmara
## Lab Summary
In this lab, we worked with combinational logic and built two different circuits using Verilog. We implemented Circuit A using Maxterms and Circuit B using Minterms. Then, we connected the two circuits together using the top.v file, where the output of Circuit A was used as an input for Circuit B. Finally, we used the constraints file to connect the switches and LEDs to the correct FPGA pins on the Basys3 board. We tested the combined design on the board to make sure the circuits worked correctly.
## Lab Questions

### 1 - Explain the role of the Top Level file.
The top file combines the functional blocks in the design and maps them to the hardware. In this lab top.v combines circuit_a and circuit_b, assigns switches and LEDs, and matches inputs and outputs.
### 2 - Explain the function of the Constraints file.
The Constraints file tells Vivado which FPGA pins match up to inputs and outputs in top.v. 
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
Yes, the selection was correct. Circuit A used Maxterms because we listed the input combinations where the output was 0. Circuit B used Minterms because we listed the input combinations where the output was 1. We would have chosen the same method for each circuit.
