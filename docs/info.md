<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Two selector bits are fed through a combination of NOT and AND gates alongside four inputs (to select one). These four outputs are ORed in order to get the final output.

## How to test

Inputs zero and one act as the two binary selectors (1 is MSB). Inputs two through five act as the inputs to select from. See table below for combinations.

I1 | I2 | O#
------------
0 | 0 | O2
0 | 1 | O3
1 | 0 | O4
1 | 1 | O5

## External hardware

LED.
