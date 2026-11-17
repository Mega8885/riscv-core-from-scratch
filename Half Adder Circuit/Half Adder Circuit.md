**Half Adder Circuit**



* A half adder circuit adds two number and outputs the sum and the carry(output carry).
* Its called the half adder because it doesn't input any carry that might've arrived at an earlier stage, and cannot be used as it is except on the unit place.

The truth table of the half adder is as follows; where A and B denote the inputs and Cout and Sum denotes the outputs.

| A | B | Sum | Cout |

|---|---|-----|------|

| 0 | 0 |  0  |  0   |

| 0 | 1 |  1  |  0   |

| 1 | 0 |  1  |  0   |

| 1 | 1 |  0  |  1   |

Based on the truth table, the Sum is 'A XOR B' and the carry is 'A AND B'. We didn't simplify the K-maps here since the function we got was super trivial.







**Things learnt while making this circuit.**

* We already know that potential is not defined, only the difference is defined. So even when I knew this, I automatically removed the jumper pins to drop the voltage to 0(GND), but this did not work, since that is not 0V with respect to the other voltages in the IC; **This error is called a floating pin error and can cause a lot of wrong results, flickering or random things.**
* There was a lot of heat generated in my breadboard power supply, when troubleshooting I found out that all the input pins in the ICs have to be set at a particular voltage to avoid this, **Note: Only connect the input pins, not the output pins, it could create short in the circuit.**




**Materials required in making the circuit**
1) Half breadboard
2) 10-15 jumper wires
3) Pull down resistors(I didn't tell this in the things learnt since I found this out later on). 2x 10k ohm resistors
4) 4 leds
5) Current limiting resistors (220-330ohms)
6) Power supply (3.3V)
7) AND gate IC and XOR gate IC, I used the 74HC series.

