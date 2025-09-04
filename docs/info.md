<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A half adder is a basic digital circuit used to add two single-bit binary numbers. It has two inputs, A and B, and produces two outputs: Sum and Carry. The Sum output is obtained using the XOR (exclusive OR) operation, while the Carry output is obtained using the AND operation.

## How to test

By switching the input 1, input 2 turn ON and OFF, SUM and CARRY is generated. This can be observed from led. 

| Input 1       | input 2       | sum      | carry     |
|---------------|---------------|----------|-----------|
| 0             | 0             | 0        | 0         |
| 0             | 1             | 1        | 0         |
| 1             | 0             | 1        | 0         |
| 1             | 1             | 0        | 1         |

## External hardware

No external hardware is required.
