# AA-Joule-Thief
A simple Joule Thief circuit you can assemble yourself.

Short version:

Circuit board can be purchased here:

https://oshpark.com/shared_projects/EGWPEieH

Bill Of Materials

Name|Description/value|Comments
----|-----------------|--------
R1, R3|1k ohm|1/8th Watt
R2|2k2 ohm||1/8th Watt
C1|470pF|Ceramic disc
C2|100uF / 10V|Voltage rating not super-critical
D1|White LED|Any should work
L1|470uH|Suggested value
JP1|2 pin jumper|Optional for on/off switch
T1, T2|BC548B NPN-type transistor|BC549C, BC550C and others may work
|PCB mount single AA battery holder

Long version and other notes:

The value of the inductor is not critical, and the PCB was designed around a surface-mount inductor because that part was available.
I designed it in an older version of Eagle, which lead to this discussion:

https://budgetlightforum.com/node/13431?page=1#comment-547403

Today I have tested the Eagle files in Eagle 9.6.2 and they open without fuss.
One of the reasons I'm creating this repository is I always intended that people would be able to tweak and adjust the circuit to suit their requirements.
Variations on the circuit have been published since at least 1999. I like this version as you do not need to wind an inductor, or source a minature transformer.
