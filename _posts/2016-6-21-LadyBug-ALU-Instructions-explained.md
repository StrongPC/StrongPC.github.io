---
layout: post
title: LadyBug ALU Instructions explained
---

In this ALU, we included some parts, such as a decoder. The decoder, choose instructions for us. We use a 2 bit input called `Op` (operation) for choosing operations. 
The operations are:

1. `00` : It does bitwise `AND` on operands A and B. 
2. `01` : It does bitwise `OR` on operands A and B.
3. `10` : It adds B to A. 
4. `11` : It subtracts B from A. 

We used 4 hex digit displays, to show what happens when we use these operations, and this is how final ALU's IC looks like:

![ALU IC](http://ladybugsystems.ir/LBugALUIC.png)
