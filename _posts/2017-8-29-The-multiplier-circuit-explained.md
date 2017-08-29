---
layout: post
title: The multiplier circuit explained
---
Now we are proud to announce our new part of the architecture. As you may know, we didn't have any multiplier circuit in StrongPC ALU's, but now, we have a special one. Which is fast and suitable for multiplying big integers! This is the circuit: 

![Multiplier](/mul.png)

The circuit works like this : 
Imagine we have two big numbers (in this case, 16 bits per number), so we can write the number like this : 

```
A : x * 2^n + y
```
And the second number will be :

```
B : w * 2^n + z
```

So, when we multiply those two expressions we'll have : 

```
(2^n * (xw + xz + yw)) + yz
``` 

And the circuit is an implementation of that expression. 

P.S : We know it's not the best way to multiply two big integers, please help us improve it. 

Regards.
