---
layout: project
type: project
image: images/cotton-square.png
title: Arithmetic Logic Unit (ALU)
permalink: projects/ALU
# All dates must be YYYY-MM-DD format!
date: 2020-05-12
labels:
  - VHDL
  - Verilog
  - LogicWorks
summary: I developed a simple ALU that can take in two 3-bit inputs and perform different types of calculations.
---

<img class="ui image" src="{{ site.baseurl }}/images/ALU.png">

An arithmetic logic unit (ALU) is a combinational digital circuit that performs arithmetic and bitwise operations on integer binary numbers.
My ALU takes in two 3-bit inputs in binary and performs different calculations based on what switches you set it to. Some operations it
can perform are adding with a carry, multiply input by 2, and xor operations.

To illustrate what it does:

Input1    Input2    Selector
001 = 1   010 = 2   00 = +   --> 1 + 2 = 3 --> 011
111 = 7   ----      01 = *   --> 7 * 2 = 14 --> 1110
111 = 7   010 = 2   10 = xor --> 101

Check it out in the link below!
Source: <a href="https://https://github.com/tonylong1314520/Simple-ALU-project"><i class="large github icon "></i>tony/arithmetic-logic-unit</a>

