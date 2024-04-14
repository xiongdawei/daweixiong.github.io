---
layout: page
title: 32 BitSlice RISC-V CPU 
description: 
img: assets/img/risvcpu.jpg
importance: 1
category: academic
related_publications: false
---

I've designed the schematic and layout of the datapath of a bit-sliced RISC-V32I compliant single-cycle processor (with the exception of FENCE*, ECALL, EBREAK, and CSRR* instructions).

The design has a 32-bit register file, and can carry out comparison, shifting, addition, XOR, AND, OR operation for two 32-bit unsigned binaries. Everything is verified using Verdi and the schematic and physical layout is done using Cadence Virtuoso. 

