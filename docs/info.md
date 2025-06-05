<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The NAND gate is the complement of AND function. Its graphic symbol consists of an AND gate’s graphic symbol followed by a small circle. Here’s the logical representation of the NAND gate.

![image](https://github.com/user-attachments/assets/0f8d6b1a-30de-4346-8a20-2c9af35a7e89)

We start by declaring the module. module, a basic building design unit in Verilog HDL, is a keyword to declare the module’s name. NAND_2 is the identifier. Identifiers is the name of the module. The module command instructs the compiler to create a block containing certain inputs and outputs. The list in parenthesis is known as the port list, it contains the input and output ports. Then we declare other datatypes required in our design as follows:

wire Yd; 
wire in Verilog represents an electrical connection. It is internal, therefore not mentioned in the port list. Next,

and(Yd, A, B); 
not(Y, Yd); 
endmodule; 

Here and is the operation performed on A, B, to get its output in Yd. Then Yd is passed through an inverter, and the output is obtained in Y. The compiler understands the and and the not operation the same way we do. endmodule terminates the module.


## How to test

![image](https://github.com/user-attachments/assets/2bc33fde-0856-42bd-bb3e-8faa487eefe1)
