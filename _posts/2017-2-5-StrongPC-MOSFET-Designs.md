---
layout: post
title: StrongPC MOSFET Designs
---
After we designed circuits and passed logic tests, we started studying on [transistors](http://strongpc.ir/2016/07/17/Transistor-implementation.html). 
The first circuits we had designed were TTL, and for now, we migrated to _**CMOS**_  technology. 
For these designs, we've used *Alpha and Omega 6407* PMOS transistors and *Texas Instruments CSD17506Q5A* NMOS transistors. 
At this step, we designed simple logic gates, and designs are available on [Github](https://github.com/StrongPC/cmos). 

## Example
This is NOT gate designed in StrongPC :

![NOT](https://github.com/StrongPC/cmos/raw/master/circuits/not.png)

And if we apply some voltage at the input :

![Waveform analysis](https://github.com/StrongPC/cmos/raw/master/waveforms/not.png)