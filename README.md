# OVP_SNVA717
Automotive Line Transient Protection Circuit
## Overall Circuit Parameters
Figure 4 shows the full circuit schematic of the design. Considering all of the above requirements, this
resulting circuit has:
1. Essentially zero operating current during normal operation as the only conducting semiconductor in this
mode is the p-channel MOSFET.
2. Programmable over-voltage disconnect determined by selection of zener diodes.
3. Programmable in-rush current based on two R-C networks in conjunction with MOSFET and bulk input
capacitor calculations.
4. Immunity to damage in the event of a shorted input bus during operation.
5. OVP that self-resets when input voltage returns to normal operating range.
6. Does not rely on dissipative limiting.
7. Does not blow fuses when in voltage limiting mode.

![Alt text](/ovp_blockdiagram.PNG)

## PCB View

![Alt text](/Hardware/SNVA717_V1.1/SNVA717_V1.1.png)
